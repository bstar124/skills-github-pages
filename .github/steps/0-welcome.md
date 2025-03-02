<!-- readme -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Football Dugout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0073e6; /* Blue background */
            color: white;
        }
        .container {
            display: flex;
        }
        .sidebar {
            width: 200px;
            background-color: #005bb5; /* Darker blue for sidebar */
            padding: 20px;
            height: 100vh;
        }
        .sidebar ul {
            list-style-type: none;
            padding: 0;
        }
        .sidebar ul li {
            margin: 20px 0;
        }
        .sidebar ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        .main-content {
            flex: 1;
            padding: 20px;
        }
        .welcome-message {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .welcome-message h1 {
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Sidebar Menu -->
        <div class="sidebar">
            <ul>
                <li><a href="#">Top 5 Series</a></li>
                <li><a href="#">Latest Articles</a></li>
                <li><a href="#">Tactical Breakdowns</a></li>
                <li><a href="#">Upcoming Coaches</a></li>
                <li><a href="#">Underrated Player of the Week</a></li>
            </ul>
        </div>

        <!-- Main Content -->
        <div class="main-content">
            <div class="welcome-message">
                <h1>Welcome to The Football Dugout!</h1>
                <p>Your go-to destination for all things football. Hosted by Bethel Moyo, we bring you the latest insights, tactical analysis, and much more.</p>
            </div>
        </div>
    </div>
</body>
</html>
