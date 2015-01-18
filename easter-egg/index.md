---
layout: page
title: Easter Egg
excerpt: "Easter Egg"
sitemap: false
---

<br>
<br>
<br>

## How to feel sick

I like to put Easter Eggs in the things I make. But please if you're having an headache while watching this, just stop immediately. I don't want to have the responsibility if you feel sick. ;)
<br>
<br>
<br>


<script>
// this code was written by Johnson Zhong (http://johnsonzhong.me/evaluations/skulecourses/) but there are some little changes by me (for example the speed increases gradually, or the restart function)
var speed = 50; // the greater this value is the lower the speed is
var increaseSpeedEveryMs = 1;
var speedTimer = 0;
var timer = setInterval(transform, 2000);
var degreez = 0;
var allSet = false;
var bellybutton;

function transform()
{
    if (!allSet)
    {
        var transOrigin = "50% 50%";
        document.body.parentElement.style.height = "100%";
        document.body.style.minHeight = "100%";
        document.body.style.transformOrigin = transOrigin;
        document.body.style.webkitTransformOrigin = transOrigin;
        document.body.style.mozTransformOrigin = transOrigin;
        bellybutton = document.createElement("button");
        bellybutton.innerHTML = "Stop";
        bellybutton.style.position = "absolute";
        bellybutton.style.left = "48%";
        bellybutton.style.top =  "48%";
        bellybutton.style.width = "80px";
        bellybutton.style.height =  "25px%";
        document.body.appendChild(bellybutton);
        bellybutton.onclick = stoppuking;
        allSet = true;
    }
    var transString = "rotate(" + degreez + "deg)";
    document.body.style.transform = transString;
    document.body.style.webkitTransform = transString;
    document.body.style.mozTransform = transString;
    if(speedTimer >= increaseSpeedEveryMs)
    {
        speedTimer = 0;
        if(speed > 1)
            speed--;
        if(increaseSpeedEveryMs <= 100)
            increaseSpeedEveryMs++;
        clearInterval(timer);
        timer = setInterval(transform, speed);
    }
    speedTimer++;
    degreez += 1;
}
function stoppuking()
{
    clearInterval(timer);
    /*var transString = "";
    document.body.style.transform = transString;
    document.body.style.webkitTransform = transString;
    document.body.style.mozTransform = transString;*/
    //document.body.removeChild(bellybutton);
    bellybutton.innerHTML = "Start";
    bellybutton.onclick = restart;
}

function restart()
{
    speed = 50;
    increaseSpeedEveryMs = 1;
    speedTimer = 0;
    timer = setInterval(transform, speed);
    bellybutton.innerHTML = "Stop";
    bellybutton.onclick = stoppuking;
}
</script>