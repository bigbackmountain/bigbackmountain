<div align="center">
<img src="https://i.ibb.co/8D2J1hVH/bootty.jpg" alt="bootty" border="0" style="width: 75%; height: auto;">
<img src="https://i.ibb.co/ccvwDtFm/divider3.png" alt="divider3" border="0" style="width: 75%; height: auto;"> 
<div align="center">

<div align="center">
<img src="https://visitor-badge.laobi.icu/badge?page_id=username.bigbackmountain&left_text=sweethearts&left_color=%23020101&right_color=%233D0b0D" alt="visitor badge"/>
<div align="center">

<div align="center">
DAZ + ANY PRNS 
<div align="center">
19 || c+h enc || w2i 
<div align="center">
  veinfei geek
<div align="center">
  
$\color{#9B0000}{\textup{I block/hide freely}}$

<div align="center">
<img src="https://i.ibb.co/s9qm0tQ2/banner2.jpg" alt="banner2" border="0" style="width: 35%; height: auto;">
<div align="center">
<img src="https://i.ibb.co/gLXx0W4H/tumblr-a36ff705139b78663cb46ab1f63606cc-19c0565b-2048.png" alt="tumblr a36ff705139b78663cb46ab1f63606cc 19c0565b 2048" border="0" style="width: 35%; height: auto;">
<div align="center">

<div align="center">
ft student + employed
<div align="center">
always on roblox or doing hw 
<div align="center">

<img src="https://i.ibb.co/274mJkgP/pic1.png" alt="pic1" border="0" style="width: 10%; height: auto;">


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Countdown Timer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117; /* GitHub dark theme background */
            color: #c9d1d9;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        h1 {
            color: #58a6ff;
            margin-bottom: 20px;
        }
        #countdown {
            font-size: 3rem;
            font-weight: bold;
            letter-spacing: 2px;
            background: #161b22;
            padding: 20px 40px;
            border-radius: 10px;
            border: 1px solid #30363d;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>

    <h1>Project Launch Countdown</h1>
    <!-- The countdown text will inject here -->
    <div id="countdown">Loading...</div>

    <script>
        // SET YOUR TARGET DATE HERE (YYYY-MM-DDTHH:MM:SS)
        const targetDate = new Date("2027-01-01T00:00:00").getTime();

        const timerInterval = setInterval(function() {
            const now = new Date().getTime();
            const timeLeft = targetDate - now;

            // Time calculations for days, hours, minutes and seconds
            const days = Math.floor(timeLeft / (1000 * 60 * 60 * 24));
            const hours = Math.floor((timeLeft % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((timeLeft % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((timeLeft % (1000 * 60)) / 1000);

            // Output the result in the element with id="countdown"
            document.getElementById("countdown").innerHTML = 
                days + "d " + hours + "h " + minutes + "m " + seconds + "s ";

            // If the countdown is finished, write some text
            if (timeLeft < 0) {
                clearInterval(timerInterval);
                document.getElementById("countdown").innerHTML = "LAUNCHED!";
            }
        }, 1000);
    </script>

</body>
</html>


