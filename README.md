<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Connect With Me</title>

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>

  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, sans-serif;
    }

    body {
      background: #0d1117;
      color: #e6edf3;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .connect-container {
      background: #161b22;
      padding: 32px 40px;
      border-radius: 14px;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.45);
      width: 100%;
      max-width: 420px;
      text-align: center;
    }

    .connect-container h2 {
      font-size: 22px;
      font-weight: 600;
      margin-bottom: 25px;
      letter-spacing: 0.5px;
    }

    .button-group {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .btn {
      text-decoration: none;
      padding: 14px 20px;
      border-radius: 10px;
      font-size: 16px;
      font-weight: 500;
      color: #ffffff;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      transition: all 0.25s ease;
    }

    .btn i {
      font-size: 18px;
    }

    .btn:hover {
      transform: translateY(-4px) scale(1.01);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.45);
    }

    /* Individual button colors */
    .email {
      background: linear-gradient(135deg, #22c55e, #16a34a);
    }

    .linkedin {
      background: linear-gradient(135deg, #0a66c2, #004182);
    }

    .github {
      background: linear-gradient(135deg, #6e7681, #30363d);
    }

    /* Mobile responsiveness */
    @media (max-width: 480px) {
      .connect-container {
        padding: 26px;
      }
    }
  </style>
</head>

<body>

  <section class="connect-container">
    <h2>📬 Connect With Me</h2>

    <div class="button-group">
      <a href="mailto:gopi15062006@gmail.com" class="btn email">
        <i class="fa-solid fa-envelope"></i>
        Email
      </a>

      <a href="https://www.linkedin.com/in/gopi15" target="_blank" class="btn linkedin">
        <i class="fa-brands fa-linkedin"></i>
        LinkedIn
      </a>

      <a href="https://github.com/GOPIKRISHNAN-S-15" target="_blank" class="btn github">
        <i class="fa-brands fa-github"></i>
        GitHub
      </a>
    </div>
  </section>

</body>
</html>
