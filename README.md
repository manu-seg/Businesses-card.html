<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business Card</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Helvetica Neue', sans-serif;
            background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .card {
            background-color: #fff;
            padding: 25px 35px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            text-align: center;
            max-width: 350px;
            width: 90%;
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #4e54c8;
            object-fit: cover;
            margin-bottom: 15px;
        }
        h1 {
            font-size: 28px;
            margin: 10px 0 5px;
            color: #333;
        }
        h2 {
            font-size: 18px;
            color: #555;
            margin-bottom: 15px;
        }
        p {
            font-size: 14px;
            color: #777;
            margin-bottom: 20px;
        }
        .info a {
            display: block;
            margin: 10px 0;
            color: #4e54c8;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.2s ease;
        }
        .info a:hover {
            color: #3b3f90;
        }
        @media (max-width: 480px) {
            .card {
                padding: 20px;
            }
            h1 {
                font-size: 24px;
            }
            h2 {
                font-size: 16px;
            }
            p {
                font-size: 13px;
            }
        }
    </style>
</head>
<body>
    <section class="card">
        <img src="profile.jpg" alt="Profile" class="profile-pic">
        <h1>Manu</h1>
        <h2>Frontend Developer</h2>
        <p>Passionate about building modern web interfaces and user experiences.</p>
        <div class="info">
            <a href="mailto:manutiru07@gmail.com">📧 manutiru07@gmail.com</a>
            <a href="tel:+918789809335">📞 +91 87898 09335</a>
            <a href="https://linkedin.com/in/manydev" target="_blank">🔗 LinkedIn Profile</a>
        </div>
    </section>
</body>
</html>
