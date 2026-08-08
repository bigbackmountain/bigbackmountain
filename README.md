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


// Source - https://stackoverflow.com/q/49670619
// Posted by antzshrek, modified by community. See post 'Timeline' for change history
// Retrieved 2026-08-08, License - CC BY-SA 3.0

function startTimer(duration, display) {
    var timer = duration, minutes, seconds;
    setInterval(function () {
        minutes = parseInt(timer / 60, 10)
        seconds = parseInt(timer % 60, 10);

        minutes = minutes < 10 ? "0" + minutes : minutes;
        seconds = seconds < 10 ? "0" + seconds : seconds;

        display.textContent = minutes + ":" + seconds;

        if (--timer < 0) {
            timer = duration;
        }
    }, 1000);
}

window.onload = function () {
    var fiveMinutes = 60 * 5,
        display = document.querySelector('#time');
    startTimer(fiveMinutes, display);
};


