<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Công cụ tính BMI</title>
    <style>
        /* Phần CSS: Làm đẹp giao diện */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            background-color: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            width: 350px;
            text-align: center;
        }

        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
        }

        .input-group {
            margin-bottom: 15px;
            text-align: left;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }

        input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 6px;
            box-sizing: border-box; /* Đảm bảo padding không làm vỡ khung */
            font-size: 16px;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #2980b9;
        }

        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 6px;
            display: none; /* Ẩn đi khi chưa tính */
        }
        
        /* Màu sắc cho các kết quả khác nhau */
        .normal { background-color: #d4edda; color: #155724; border: 1px solid #c3e6cb; }
        .warning { background-color: #fff3cd; color: #856404; border: 1px solid #ffeeba; }
        .danger { background-color: #f8d7da; color: #721c24; border: 1px solid #f5c6cb; }
    </style>
</head>
<body>

    <div class="container">
        <h2>Tính Chỉ Số BMI</h2>
        
        <div class="input-group">
            <label for="height">Chiều cao (cm):</label>
            <input type="number" id="height" placeholder="Ví dụ: 170">
        </div>

        <div class="input-group">
            <label for="weight">Cân nặng (kg):</label>
            <input type="number" id="weight" placeholder="Ví dụ: 65">
        </div>

        <button onclick="calculateBMI()">Xem kết quả</button>

        <div id="result"></div>
    </div>

    <script>
        function calculateBMI() {
            // 1. Lấy giá trị từ ô nhập liệu
            const heightCm = document.getElementById('height').value;
            const weight = document.getElementById('weight').value;
            const resultDiv = document.getElementById('result');

            // 2. Kiểm tra dữ liệu đầu vào
            if (heightCm === "" || weight === "" || heightCm <= 0 || weight <= 0) {
                alert("Vui lòng nhập chiều cao và cân nặng hợp lệ!");
                return;
            }

            // 3. Tính toán (Chuyển cm sang m rồi tính)
            const heightM = heightCm / 100;
            const bmi = (weight / (heightM * heightM)).toFixed(2); // Làm tròn 2 số thập phân

            // 4. Phân loại và hiển thị
            let message = "";
            let cssClass = "";

            if (bmi < 18.5) {
                message = `BMI của bạn là <strong>${bmi}</strong>. <br>Đánh giá: <em>Thiếu cân</em> 🥗`;
                cssClass = "warning";
            } else if (bmi >= 18.5 && bmi < 24.9) {
                message = `BMI của bạn là <strong>${bmi}</strong>. <br>Đánh giá: <em>Bình thường</em> ✅`;
                cssClass = "normal";
            } else if (bmi >= 25 && bmi < 29.9) {
                message = `BMI của bạn là <strong>${bmi}</strong>. <br>Đánh giá: <em>Thừa cân</em> ⚠️`;
                cssClass = "warning";
            } else {
                message = `BMI của bạn là <strong>${bmi}</strong>. <br>Đánh giá: <em>Béo phì</em> 🚨`;
                cssClass = "danger";
            }

            // Hiển thị kết quả ra màn hình
            resultDiv.style.display = "block";
            resultDiv.className = cssClass; // Gán class màu sắc tương ứng
            resultDiv.innerHTML = message;
        }
    </script>
</body>
</html>
