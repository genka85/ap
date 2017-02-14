```
{
    "invoice": 3,
    "unp": 300451566,
    "date": "19.01.2017",
    "products": [
        {"product": "Банка 20,0 л д 340", "count": "210"},
        {"product": "Банка 0,725 л д 170", "count": "0.05"}
    ]
}
```

- `invoice` - № счёт-фактуры, int
- `unp` - УПН контрагента, int
- `date` - дата счёт-фактуры, string
- `products` - массив содержащий объекты с продукцией, array
    - `product` - наименование продукции, string
    - `count` - кол-во продукции, string
