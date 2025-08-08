<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zepter Catalog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #444;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        h1 {
            margin: 0;
        }
        .catalog {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .item {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            text-align: center;
            padding-bottom: 15px;
        }
        .item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .item h3 {
            margin: 10px 0 5px;
            font-size: 18px;
        }
        .item p {
            margin: 5px 0;
            font-size: 14px;
            color: #666;
        }
        .price {
            color: #c00;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Zepter Catalog – 19 Items</h1>
    </header>
    <div class="catalog">
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-565.jpg" alt="Casserole 6.3L">
            <h3>Casserole 6.3L</h3>
            <p>Ø 24 × 13.5 cm with Lid</p>
            <p class="price">$650</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-450.jpg" alt="Casserole 3.1L">
            <h3>Casserole 3.1L</h3>
            <p>Ø 20 × 10 cm with Lid</p>
            <p class="price">$450</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-410.jpg" alt="Casserole 1.6L">
            <h3>Casserole 1.6L</h3>
            <p>Ø 16 × 8 cm with Lid</p>
            <p class="price">$250</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-610.jpg" alt="Frypan 2.9L">
            <h3>Frypan 2.9L</h3>
            <p>Ø 24 × 6.5 cm with Lid</p>
            <p class="price">$450</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-20.jpg" alt="Suction Knob">
            <h3>Suction Knob</h3>
            <p>Accessory</p>
            <p class="price">$20</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-430.jpg" alt="Saucepan 1.8L">
            <h3>Saucepan 1.8L</h3>
            <p>Ø 16 × 9 cm with Lid</p>
            <p class="price">$250</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-178.jpg" alt="Steamer">
            <h3>Steamer</h3>
            <p>Ø 22 × 9.5 cm</p>
            <p class="price">$178</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-74.jpg" alt="Frying Basket">
            <h3>Frying Basket</h3>
            <p>With Helping Handle</p>
            <p class="price">$74</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/u/s/us-210.jpg" alt="Mixing Bowl">
            <h3>Mixing Bowl</h3>
            <p>Ø 20 × 7 cm with Lid</p>
            <p class="price">$210</p>
        </div>
        <div class="item">
            <img src="https://shop.zepter.com/media/catalog/product/cache/1/image/800x800/9df78eab33525d08d6e5fb8d27136e95/a/c/accessories.jpg" alt="Bakelite Mat">
            <h3>Bakelite Mat × 2pcs</h3>
            <p>Accessory</p>
            <p class="price">$50</p>
        </div>
    </div>
</body>
</html>
