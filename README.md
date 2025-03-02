<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            margin: 50px auto;
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px gray;
        }
        iframe {
            width: 100%;
            height: 400px;
            border: none;
        }
    </style>
</head>
<body>

    <header>Welcome to My Portfolio</header>

    <div class="container">
        <h2>About Me</h2>
        <p>Hello! I'm [Shalini], a data analyst passionate about creating insightful dashboards.</p>
        
        <h2>My Dashboards</h2>
        <!-- Embed a read-only Tableau/Power BI dashboard -->
        <iframe src="https://public.tableau.com/views/SampleDashboard" title="My Dashboard"></iframe>

        <h2>Contact</h2>
        <p>Email: shalinishalu12559@gmail.com</p>
    </div>

</body>
</html>
