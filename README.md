
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Invitation - สยาม & วรรณษา</title>
    <style>
        body {
            font-family: 'Tahoma', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f3f2e9, #d5d5c3);
            color: #4a4a2e;
            text-align: center;
        }
        header {
            background: #6e8f59;
            color: white;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        section {
            margin: 20px;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .gallery img {
            width: 45%;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        .rsvp {
            margin: 20px auto;
        }
        .flower-effect {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }
        .flower {
            position: absolute;
            width: 20px;
            height: 20px;
            background: url('clover.png') no-repeat center/contain;
            animation: fall linear infinite;
        }
        @keyframes fall {
            from {
                transform: translateY(-100px);
                opacity: 1;
            }
            to {
                transform: translateY(100vh);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>งานแต่งงานของ สยาม & วรรณษา</h1>
        <p>1 พฤศจิกายน 2568</p>
    </header>

    <section>
        <h2>สถานที่จัดงาน</h2>
        <p>ร้าน ษญา (SAYA)</p>
        <a href="https://maps.app.goo.gl/dvf7VQnSa4Z5hMry8" target="_blank">ดูแผนที่</a>
    </section>

    <section>
        <h2>เรื่องราวของเรา</h2>
        <p>จากวันแรกที่พบกันจนถึงวันนี้ เรื่องราวของเราคือการเดินทางที่เต็มไปด้วยความรักและความทรงจำที่งดงาม<br>เราหวังเป็นอย่างยิ่งที่จะได้แบ่งปันช่วงเวลานี้กับคุณ</p>
    </section>

    <section>
        <h2>แกลเลอรีภาพ</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/400" alt="Gallery Image 1">
            <img src="https://via.placeholder.com/400" alt="Gallery Image 2">
            <img src="https://via.placeholder.com/400" alt="Gallery Image 3">
            <img src="https://via.placeholder.com/400" alt="Gallery Image 4">
        </div>
    </section>

    <section>
        <h2>ตอบรับคำเชิญ</h2>
        <form class="rsvp" action="#" method="POST">
            <label for="name">ชื่อ:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="attending">จะเข้าร่วม:</label><br>
            <select id="attending" name="attending">
                <option value="yes">ใช่</option>
                <option value="no">ไม่</option>
            </select><br><br>
            <button type="submit">ส่ง</button>
        </form>
    </section>

    <section>
        <h2>มอบของขวัญให้บ่าวสาว</h2>
        <img src="QRpp.jpg" class="mx-auto d-block" style="width:50%" alt="QR Code">
    </section>

    <div class="flower-effect">
        <div class="flower" style="left: 10%; animation-duration: 10s;"></div>
        <div class="flower" style="left: 30%; animation-duration: 8s;"></div>
        <div class="flower" style="left: 50%; animation-duration: 6s;"></div>
        <div class="flower" style="left: 70%; animation-duration: 12s;"></div>
        <div class="flower" style="left: 90%; animation-duration: 9s;"></div>
    </div>
</body>
</html>
