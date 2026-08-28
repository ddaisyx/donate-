<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>ddaisy ♡ Donate</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            min-height: 100vh;
            font-family: Arial, "Noto Sans Thai", sans-serif;
            background:
                radial-gradient(circle at top left, #fff8fb 0%, transparent 35%),
                linear-gradient(135deg, #fff0f6, #ffd6e8, #ffeaf3);
            color: #6d3b50;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 25px 15px;
        }

        .container {
            width: 100%;
            max-width: 520px;
        }

        .card {
            background: rgba(255, 255, 255, 0.92);
            border-radius: 30px;
            padding: 38px 25px;
            text-align: center;
            box-shadow: 0 15px 45px rgba(214, 105, 150, 0.20);
            border: 2px solid rgba(255, 255, 255, 0.95);
        }

        .flower {
            font-size: 42px;
            margin-bottom: 8px;
        }

        h1 {
            font-size: 40px;
            color: #d85b91;
            margin-bottom: 6px;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 15px;
            color: #b16b87;
            margin-bottom: 25px;
        }

        .welcome {
            background: #fff5f9;
            border-radius: 20px;
            padding: 20px;
            line-height: 1.8;
            margin-bottom: 28px;
            font-size: 15px;
        }

        .welcome strong {
            color: #d85b91;
            font-size: 18px;
        }

        .section-title {
            font-size: 19px;
            color: #d85b91;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .donate-button {
            display: block;
            width: 100%;
            padding: 15px;
            margin: 12px 0;
            border: none;
            border-radius: 16px;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s ease;
        }

        .donate-button:hover {
            transform: translateY(-2px);
        }

        .promptpay {
            background: #e56b9b;
            color: white;
            box-shadow: 0 7px 15px rgba(229, 107, 155, 0.25);
        }

        .truemoney {
            background: #ff9fbd;
            color: white;
            box-shadow: 0 7px 15px rgba(255, 159, 189, 0.25);
        }

        .payment-box {
            display: none;
            background: #fff5f9;
            border-radius: 18px;
            padding: 18px;
            margin-top: 10px;
            margin-bottom: 15px;
            border: 1px solid #f7c5d8;
        }

        .payment-box.show {
            display: block;
        }

        .payment-name {
            font-weight: bold;
            color: #d85b91;
            margin-bottom: 8px;
        }

        .payment-number {
            background: white;
            border-radius: 12px;
            padding: 12px;
            margin: 10px 0;
            font-size: 18px;
            font-weight: bold;
            color: #6d3b50;
            letter-spacing: 1px;
        }

        .copy-button {
            background: #d85b91;
            color: white;
            border: none;
            border-radius: 10px;
            padding: 9px 16px;
            cursor: pointer;
            font-size: 14px;
        }

        .qr-section {
            margin-top: 25px;
            padding: 22px;
            background: #fff5f9;
            border-radius: 20px;
        }

        .qr-image {
            width: 230px;
            height: 230px;
            object-fit: contain;
            display: block;
            margin: 15px auto;
            background: white;
            border-radius: 15px;
            padding: 8px;
        }

        .qr-text {
            font-size: 14px;
            line-height: 1.7;
            color: #9c607b;
        }

        .thank-you {
            margin-top: 27px;
            font-size: 14px;
            line-height: 1.8;
            color: #a85b78;
        }

        .heart {
            color: #e56b9b;
        }

        .footer {
            margin-top: 25px;
            font-size: 13px;
            color: #c0809b;
        }

        @media (max-width: 480px) {
            .card {
                padding: 30px 18px;
            }

            h1 {
                font-size: 36px;
            }

            .qr-image {
                width: 210px;
                height: 210px;
            }
        }
    </style>
</head>

<body>

    <div class="container">

        <div class="card">

            <div class="flower">🌸</div>

            <h1>ddaisy</h1>

            <p class="subtitle">
                Donate & Support ♡
            </p>


            <div class="welcome">

                <strong>สวัสดีค้าบ ♡</strong>

                <br><br>

                กำลังหาค่าขนมเล็ก ๆ น้อย ๆ อยู่ค่ะ 🍰🎀

                <br>

                ถ้าอยากสนับสนุนหรือส่งกำลังใจให้กัน
                สามารถโดเนทได้ทางช่องทางด้านล่างเลยนะคะ

                <br><br>

                ขอบคุณสำหรับทุกการสนับสนุนเลยนะ 🥺💗

                <br>

                ทุกยอดมีความหมายกับเรามาก ๆ
                และช่วยเป็นกำลังใจให้ทำผลงานต่อไปค่ะ ✨

            </div>


            <div class="section-title">
                💌 ช่องทางสนับสนุน
            </div>


            <!-- PromptPay -->

            <button
                class="donate-button promptpay"
                onclick="togglePayment('promptpay-box')">

                💗 Donate ผ่าน PromptPay

            </button>


            <div id="promptpay-box" class="payment-box">

                <div class="payment-name">
                    💗 PromptPay
                </div>

                <p>
                    สามารถโอนผ่านหมายเลข PromptPay ด้านล่างได้เลยค่ะ
                </p>

                <div class="payment-number" id="promptpay-number">
                    098-937-0361
                </div>

                <button
                    class="copy-button"
                    onclick="copyNumber('promptpay-number')">

                    📋 คัดลอกหมายเลข

                </button>

            </div>


            <!-- TrueMoney Wallet -->

            <button
                class="donate-button truemoney"
                onclick="togglePayment('truemoney-box')">

                🎀 Donate ผ่าน TrueMoney Wallet

            </button>


            <div id="truemoney-box" class="payment-box">

                <div class="payment-name">
                    🎀 TrueMoney Wallet
                </div>

                <p>
                    สามารถโอนผ่าน TrueMoney Wallet
                    ตามหมายเลขด้านล่างได้เลยค่ะ
                </p>

                <div class="payment-number" id="truemoney-number">
                    098-937-0361
                </div>

                <button
                    class="copy-button"
                    onclick="copyNumber('truemoney-number')">

                    📋 คัดลอกหมายเลข

                </button>

            </div>


            <!-- Bank QR Code -->

            <div class="qr-section">

                <div class="section-title">
                    🏦 QR Code ธนาคาร
                </div>

                <img
                    src="IMG_0219.jpeg"
                    alt="QR Code สำหรับโดเนท"
                    class="qr-image"
                >

                <p class="qr-text">
                    📱 เปิดแอปธนาคารแล้วสแกน QR Code
                    <br>
                    เพื่อสนับสนุน ddaisy ได้เลยค่ะ 💗
                </p>

            </div>


            <div class="thank-you">

                🌷 ขอบคุณที่สนับสนุนกันนะคะ 🌷

                <br>

                ขอให้วันนี้เป็นวันที่น่ารักสำหรับคุณเหมือนกันนะ

                <span class="heart">♥</span>

            </div>


            <div class="footer">
                © 2026 ddaisy ♡
            </div>

        </div>

    </div>


    <script>

        function togglePayment(id) {

            const box = document.getElementById(id);

            box.classList.toggle("show");

        }


        function copyNumber(id) {

            const number =
                document.getElementById(id).innerText;

            navigator.clipboard.writeText(number);

            alert("คัดลอกหมายเลขเรียบร้อยแล้วค่ะ 💗");

        }

    </script>

</body>
</html>
