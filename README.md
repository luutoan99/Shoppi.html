# Shoppi.html
Giao dịch điện thoại bằng pi
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cửa hàng điện thoại Pi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2C3E50;
            color: white;
            padding: 10px;
            text-align: center;
        }
        .container {
            display: flex;
            justify-content: center;
            margin: 20px;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 10px;
            padding: 20px;
            width: 250px;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product h2 {
            font-size: 18px;
            text-align: center;
        }
        .product p {
            font-size: 14px;
            text-align: center;
        }
        .product .price {
            font-size: 18px;
            font-weight: bold;
            color: #27AE60;
            text-align: center;
        }
        .buy-button {
            background-color: #27AE60;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-align: center;
            width: 100%;
            margin-top: 10px;
        }
        .buy-button:hover {
            background-color: #2ECC71;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chào mừng đến với Cửa hàng điện thoại Pi</h1>
        <p>Thanh toán nhanh chóng bằng Pi Network</p>
    </header>
    
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Điện thoại mẫu">
            <h2>Điện thoại Samsung Galaxy</h2>
            <p>Điện thoại thông minh Samsung Galaxy, màn hình lớn, camera chất lượng cao.</p>
            <div class="price">Giá: 1500 Pi</div>
            <button class="buy-button" onclick="buyProduct('Samsung Galaxy')">Mua ngay</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Điện thoại mẫu">
            <h2>Điện thoại iPhone 13</h2>
            <p>iPhone 13 với màn hình Super Retina XDR, hiệu suất mạnh mẽ.</p>
            <div class="price">Giá: 2000 Pi</div>
            <button class="buy-button" onclick="buyProduct('iPhone 13')">Mua ngay</button>
        </div>
    </div>

    <footer style="text-align: center; padding: 20px; background-color: #2C3E50; color: white;">
        <p>&copy; 2025 Cửa hàng điện thoại Pi. Tất cả các quyền được bảo lưu.</p>
    </footer>

    <script>
        function buyProduct(product) {
            alert("Bạn đã chọn mua " + product + ". Hệ thống thanh toán bằng Pi sẽ được kích hoạt.");
            // Thêm mã tích hợp thanh toán Pi Network ở đây
        }
    </script>
</body>
</html>
