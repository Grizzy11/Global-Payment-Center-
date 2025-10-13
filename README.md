<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Global Payment Center</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f0f2f5;
        margin: 0;
        padding: 0;
        text-align: center;
    }
    header {
        background: #007BFF;
        color: white;
        padding: 30px 20px;
    }
    header h1 {
        margin: 0;
        font-size: 28px;
    }
    .instructions {
        max-width: 900px;
        margin: 20px auto;
        background: #fff;
        border-radius: 10px;
        padding: 20px;
        text-align: left;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .instructions h2 {
        margin-top: 0;
        color: #007BFF;
    }
    .instructions ol {
        padding-left: 20px;
    }
    .payment-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
        gap: 15px;
        padding: 30px;
        max-width: 1200px;
        margin: auto;
    }
    .payment-btn {
        background: #fff;
        border: 2px solid #ccc;
        padding: 10px;
        border-radius: 10px;
        text-decoration: none;
        color: #333;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        transition: all 0.3s ease;
        height: 100px;
    }
    .payment-btn:hover {
        background: #007BFF;
        color: #fff;
        border-color: #007BFF;
    }
    .payment-btn img {
        max-width: 40px;
        margin-bottom: 5px;
    }
    footer {
        margin-top: 30px;
        padding: 20px;
        background: #f4f4f4;
        color: #555;
        font-size: 14px;
    }
</style>
</head>
<body>

<header>
    <h1>🌎 Global Payment Center</h1>
</header>

<div class="instructions">
    <h2>How to Pay</h2>
    <ol>
        <li>Choose your preferred payment method from the buttons below.</li>
        <li>If you select Flutterwave, you will be redirected to our secure Flutterwave payment page.</li>
        <li>For other payment methods, click the button and follow the instructions provided for that service.</li>
        <li>Enter the amount you want to pay and complete the payment.</li>
        <li>After payment, keep a screenshot or reference number for confirmation.</li>
        <li>If needed, contact our support for help with any payment issues.</li>
    </ol>
</div>

<div class="payment-grid">
    <!-- 50 Payment Buttons -->
    <a class="payment-btn" href="https://flutterwave.com/pay/xafeversend" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Flutterwave_logo.png" alt="Flutterwave">
        Flutterwave
    </a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" alt="PayPal">PayPal</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Cash_App_logo.svg" alt="CashApp">CashApp</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Zelle_Logo.png" alt="Zelle">Zelle</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/42/PIX_Logo.png" alt="PIX">PIX</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Multibanco_Logo.png" alt="Multibanco">Multibanco</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/MB_Way_logo.png" alt="MBWAY">MBWAY</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/UPI_Logo.png" alt="UPI">UPI</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Bank_icon.png" alt="Trinidad Bank">Trinidad Bank</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Bank_icon.png" alt="Angola Bank">Angola Bank</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Bank_icon.png" alt="PNG Bank">Papua New Guinea Bank</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/6/61/Revolut_logo.svg" alt="Revolut">Revolut</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Skrill_logo.png" alt="Skrill">Skrill</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Neteller_Logo.svg" alt="Neteller">Neteller</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Payoneer_logo.png" alt="Payoneer">Payoneer</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Wise_logo.svg" alt="Wise">Wise</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Venmo_logo.png" alt="Venmo">Venmo</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Google_Pay_Logo.png" alt="Google Pay">Google Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/f/fa/Apple_Pay_logo.png" alt="Apple Pay">Apple Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/89/Samsung_Pay_logo.svg" alt="Samsung Pay">Samsung Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/09/Stripe_Logo%2C_revised_2016.png" alt="Stripe">Stripe</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Alipay_logo.svg" alt="Alipay">Alipay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/WeChat_logo.svg" alt="WeChat Pay">WeChat Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Paytm_logo.png" alt="Paytm">Paytm</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/1/16/M-Pesa_logo.svg" alt="M-Pesa">M-Pesa</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Orange_Money_logo.png" alt="Orange Money">Orange Money</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/38/MTN_Mobile_Money_logo.svg" alt="MTN Money">MTN Money</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Tigo_Money_logo.png" alt="Tigo Money">Tigo Money</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/Airtel_Money_logo.png" alt="Airtel Money">Airtel Money</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/EcoPayz_logo.png" alt="EcoPayz">EcoPayz</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/83/WorldRemit_logo.svg" alt="WorldRemit">WorldRemit</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Remitly_logo.png" alt="Remitly">Remitly</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Western_Union_logo.png" alt="Western Union">Western Union</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/42/MoneyGram_logo.png" alt="MoneyGram">MoneyGram</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Bank_icon.png" alt="Bank">Bank Transfers</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/UnionPay_logo.png" alt="UnionPay">UnionPay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Binance_logo.png" alt="Binance Pay">Binance Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/46/Bitcoin.svg" alt="BTC">Crypto BTC</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Ethereum-icon-purple.svg" alt="ETH">Crypto ETH</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/7/71/Tether-logo.svg" alt="USDT">Crypto USDT</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Google_Wallet_icon.svg" alt="Google Wallet">Google Wallet</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Facebook_Pay_logo.png" alt="Facebook Pay">Facebook Pay</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/48/Shopify_logo.png" alt="Shopify">Shopify Payments</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/Klarna_logo.svg" alt="Klarna">Klarna</a>
    <a class="payment-btn" href="#" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Afterpay_logo.svg" alt="AfterPay">AfterPay</a>
</div>

<footer>
    &copy; 2025 Global Payment Center. All rights reserved.
</footer>

</body>
</html>