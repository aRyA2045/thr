# thr
minta maaf dan kasih thr
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohon Maaf & Terima Kasih</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 85%;
            animation: fadeIn 1.5s ease-in;
        }
        h2 { color: #2d3436; margin-bottom: 10px; }
        p { color: #636e72; line-height: 1.6; font-size: 15px; }
        .thr-button {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background-color: #00b894;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: 0.3s;
            opacity: 0;
            animation: slideUp 1s ease-out 4s forwards;
        }
        .message {
            opacity: 0;
            animation: fadeIn 2s ease-in forwards;
        }
        .delay-1 { animation-delay: 1s; }
        .delay-2 { animation-delay: 2.5s; }

        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideUp { 
            from { opacity: 0; transform: translateY(20px); } 
            to { opacity: 1; transform: translateY(0); } 
        }
    </style>
</head>
<body>

<div class="container">
    <h2 class="message">Selamat Idul Fitri ✨</h2>
    
    <p class="message delay-1">
        Aku mau jujur... Selama ini aku sering repotin kamu, sering nyalahin kamu atas kekecewaanku sendiri. Ternyata akulah alasannya, bukan kamu.
    </p>
    
    <p class="message delay-2">
        Makasih ya udah jadi alasan aku bertahan sampai sekarang, meskipun aku sadar aku sering nyebelin. Maafin aku lahir dan batin ya.
    </p>

    <a href="https://link.dana.id/kaget/..." class="thr-button">Klik untuk Ambil THR 🎁</a>
</div>

</body>
</html>
