# MaerskDemo
Solution build on .net core 3.1 
Created serverless function using azure http trigger function 
Get API :- GetSkus :- Return list of SKUs
Post API :- CheckOutProduct :- Return total amount value
Request Body :- 
[
    {
        "SKU": "A",
        "Quantity":5
    },
    {
        "SKU": "B",
         "Quantity":5
    },
    {
        "SKU": "C",
         "Quantity":1
    },
    {
        "SKU": "D",
        "Quantity":1
    }
]
