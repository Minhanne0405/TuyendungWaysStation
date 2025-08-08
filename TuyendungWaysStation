<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ứng Tuyển Ways Station</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
            margin: 0;
            padding: 20px;
        }
        h1, h2 {
            color: #333;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
        }
        label {
            display: block;
            margin-top: 15px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            margin-top: 20px;
            background: #007bff;
            color: white;
            border: none;
            padding: 12px;
            border-radius: 5px;
            cursor: pointer;
        }
        .thank-you {
            margin-top: 20px;
            color: green;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Ứng Tuyển Ways Station</h1>
    <p><strong>Ways Station LNA</strong> là quán do cựu nhân viên tự mở, mong muốn tạo cơ hội việc làm thân thiện và chuyên nghiệp.</p>

    <h2>Vị Trí Tuyển Dụng</h2>
    <ul>
        <li>Phục vụ net</li>
        <li>Phục vụ bida</li>
        <li>Thu ngân net bida</li>
        <li>Giữ xe</li>
        <li>Phục vụ gym</li>
        <li>Thu ngân gym</li>
    </ul>

    <form id="applyForm">
        <label for="fullname">Họ và tên</label>
        <input type="text" id="fullname" name="fullname" required>

        <label for="phone">Số điện thoại</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="position">Vị trí ứng tuyển</label>
        <select id="position" name="position" required>
            <option value="">-- Chọn vị trí --</option>
            <option>Phục vụ net</option>
            <option>Phục vụ bida</option>
            <option>Thu ngân net bida</option>
            <option>Giữ xe</option>
            <option>Phục vụ gym</option>
            <option>Thu ngân gym</option>
        </select>

        <label for="shift">Ca làm</label>
        <select id="shift" name="shift" required>
            <option value="">-- Chọn ca làm --</option>
            <option>Full-time (12 tiếng)</option>
        </select>

        <label for="note">Ghi chú thêm (nếu có)</label>
        <textarea id="note" name="note" rows="3"></textarea>

        <button type="submit">Gửi Ứng Tuyển</button>

        <div class="thank-you" id="thankYou" style="display: none;">
            Cảm ơn bạn đã ứng tuyển, chúng tôi sẽ liên hệ lại qua số 0399013426.
        </div>
    </form>
</div>

<script>
    document.getElementById('applyForm').addEventListener('submit', function(e) {
        e.preventDefault();
        document.getElementById('thankYou').style.display = 'block';
        this.reset();
    });
</script>

</body>
</html>
