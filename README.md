<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>🎁 Free Fire Diamond Giveaway | Klaim 5000 Diamond!</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #0a0f1e 0%, #1a1f2e 100%);
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 400px;
            width: 100%;
            background: linear-gradient(145deg, #1a1f30, #0f1422);
            border-radius: 48px;
            overflow: hidden;
            border: 1px solid rgba(255, 215, 0, 0.3);
            box-shadow: 0 20px 40px rgba(0,0,0,0.5), 0 0 20px rgba(255, 215, 0, 0.1);
        }

        .banner {
            background: linear-gradient(135deg, #ffd700, #ff8c00);
            padding: 30px 20px;
            text-align: center;
        }

        .banner .diamond-icon {
            font-size: 50px;
            margin-bottom: 10px;
        }

        .banner h1 {
            font-size: 26px;
            color: #1a1a2e;
        }

        .banner p {
            font-size: 14px;
            color: #1a1a2e;
            margin-top: 5px;
        }

        .countdown {
            background: rgba(0,0,0,0.7);
            padding: 12px;
            text-align: center;
            color: #ffd700;
            font-weight: bold;
            font-size: 18px;
        }

        .content {
            padding: 24px 20px;
        }

        .offer-text {
            background: rgba(255, 215, 0, 0.1);
            border-radius: 24px;
            padding: 16px;
            text-align: center;
            margin-bottom: 24px;
            border: 1px solid rgba(255, 215, 0, 0.3);
        }

        .offer-text .big {
            font-size: 32px;
            font-weight: bold;
            color: #ffd700;
        }

        .form-group {
            margin-bottom: 18px;
        }

        .form-group label {
            display: block;
            color: #aaa;
            font-size: 12px;
            margin-bottom: 6px;
        }

        .form-group input {
            width: 100%;
            padding: 14px 16px;
            background: #0a0f1a;
            border: 1px solid #2a3456;
            border-radius: 28px;
            color: white;
            font-size: 14px;
            outline: none;
        }

        .form-group input:focus {
            border-color: #ffd700;
            box-shadow: 0 0 10px rgba(255, 215, 0, 0.3);
        }

        .btn-claim {
            width: 100%;
            background: linear-gradient(95deg, #ffd700, #ff8c00);
            border: none;
            padding: 16px;
            border-radius: 60px;
            font-weight: bold;
            font-size: 18px;
            color: #1a1a2e;
            cursor: pointer;
            margin-top: 10px;
            font-weight: 800;
        }

        .btn-claim:active {
            transform: scale(0.97);
        }

        .testimonials {
            margin-top: 24px;
            padding-top: 16px;
            border-top: 1px solid #2a3456;
        }

        .testimonial {
            background: #0a0f1a;
            border-radius: 20px;
            padding: 10px 12px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .testimonial .avatar {
            width: 35px;
            height: 35px;
            background: #ffd700;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: #1a1a2e;
        }

        .testimonial .text {
            flex: 1;
        }

        .testimonial .text .name {
            color: white;
            font-weight: bold;
            font-size: 12px;
        }

        .testimonial .text .msg {
            color: #aaa;
            font-size: 10px;
        }

        .footer {
            text-align: center;
            padding: 16px;
            background: #0a0f1a;
            font-size: 10px;
            color: #5a6a8a;
        }

        .toast {
            position: fixed;
            bottom: 30px;
            left: 20px;
            right: 20px;
            background: #1a1f30;
            padding: 12px;
            border-radius: 60px;
            text-align: center;
            color: #ffd700;
            font-size: 13px;
            opacity: 0;
            transition: 0.2s;
            z-index: 1000;
            border: 1px solid #ffd700;
        }

        .modal {
            position: fixed;
            top: 0;
            left: 0;
            righ