<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team ExoCode - Climate Change Awareness</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: #1f1f2e;
            color: #e8e8e8;
        }

        header {
            background: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 28px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }

        nav {
            display: flex;
            justify-content: flex-end;
            background: #34495e;
            padding: 15px 0;
            position: sticky;
            top: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            z-index: 1000;
        }

        nav a,
        .dropdown select {
            color: #e8e8e8;
            margin: 0 15px;
            padding: 10px 15px;
            background: transparent;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
            font-size: 16px;
            transition: color 0.3s, background 0.3s;
        }

        nav a:hover {
            background: #1a252f;
        }

        .dropdown {
            margin-left: 10px;
            position: relative;
        }

        .dropdown select {
            color: #e8e8e8;
            background: #34495e;
            border: 1px solid #444;
            font-size: 16px;
            padding: 10px 30px 10px 15px;
            border-radius: 5px;
            appearance: none;
            outline: none;
            position: relative;
            cursor: pointer;
        }

        .dropdown select:hover {
            background: #1a252f;
        }

        /* Custom arrow for dropdown */
        .dropdown select {
            background-image: url('data:image/svg+xml;charset=US-ASCII,<svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24"><polygon points="0,0 12,12 24,0" fill="white"/></svg>');
            background-repeat: no-repeat;
            background-position: right 15px center;
            background-size: 12px 12px;
        }

        .intro {
            padding: 30px;
            background: #2c3e50;
            margin: 20px;
            border-radius: 10px;
            color: #f1f1f1;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        .video-panel {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }

        .video {
            margin: 10px;
            width: 320px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            background: #34495e;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .video:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }

        .video iframe {
            width: 100%;
            height: 200px;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 30px;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.5);
        }

        @media (max-width: 600px) {
            .video {
                width: 90%;
            }

            nav {
                flex-direction: column;
            }

            nav a {
                margin: 10px 0;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to Team ExoCode!</h1>
    </header>

    <nav>
        <a href="#overview">Overview</a>
        <a href="#about">About</a>

        <!-- Dashboard Dropdown with white arrow -->
        <div class="dropdown">
            <select onchange="location = this.value;">
                <option value="" disabled selected>Dashboard</option>
                <option value="dashboard_topic1.html">Topic 1 Dashboard</option>
                <option value="dashboard_topic2.html">Topic 2 Dashboard</option>
                <option value="dashboard_topic3.html">Topic 3 Dashboard</option>
            </select>
        </div>

        <!-- Videos Dropdown with white arrow -->
        <div class="dropdown">
            <select onchange="location = this.value;">
                <option value="" disabled selected>Videos</option>
                <option value="https://www.youtube.com/watch?v=VIDEO_ID_1">Video 1</option>
                <option value="https://www.youtube.com/watch?v=VIDEO_ID_2">Video 2</option>
                <option value="https://www.youtube.com/watch?v=VIDEO_ID_3">Video 3</option>
            </select>
        </div>

        <!-- Resources Dropdown with white arrow -->
        <div class="dropdown">
            <select onchange="location = this.value;">
                <option value="" disabled selected>Resources</option>
                <option value="https://www.resource1.com">Resource 1</option>
                <option value="https://www.resource2.com">Resource 2</option>
                <option value="https://www.resource3.com">Resource 3</option>
            </select>
        </div>
    </nav>

    <div class="intro" id="overview">
        <h2>About Our Project</h2>
        <p>Climate change is something that affects all of us, from the air we breathe to the weather we experience every day. It’s no longer just about the future—it’s happening now, and we all have a role to play in addressing it.</p>
        <p>We’ve put together a short, 3-minute video to help explain what climate change is, why it’s happening, and what we can do to make a difference.</p>
    </div>

    <footer>
        <p>&copy; 2024 Team ExoCode. All rights reserved.</p>
    </footer>

</body>

</html># hack
