# Tool Learning Log

## Tool: **Animate.css**

---

### 3/7/25:
* used [ Animate.css ](https://animate.style/) and read through it
* watched a beginner tutorial to get a better understanding [VIDEO](https://www.youtube.com/watch?v=VzbBcVRquYA)
* I modified the code by changing the animation from "`bounce`" to "`flash`"
    * allowing me to see how different effects function.
* tried using animate_repeat to make it last longer
    * but I realised it can only do up to 3 times
    * I changed the repeat to infinite so now it just keep bouncing up and down without stopping
* Next time I will try to expand my learning and try more cool animations



### 3/14/25:
* I watch this  [VIde])(https://www.youtube.com/watch?v=S2KCXKAView) trying out the code they are doing using the animate.css
* through making the `class="animate__animated animate__slideInDown">` there will be a cool animation of the text sliding down
* you can make it slide in from the left using `class="animate__animated animate__slideInLeft"`
* and for sliding in front the right it would be the same thing but u chnage `left` to `right`
* I can make it have a delay so I did that to my text which have a `animate__animated animate__slideInLeft` and gave a delay through putting a style in the `head` using the code: 
``` CSS
<style>
        .animate__animated.animate__slideInLeft{
    animation-delay: 3s;
}  
    </style>
```
* you can also put `animation-iteration-count: # ` which allows you to choose how much time it pops up and repeat the actions.
* so by putting ` animation-iteration-count: infinite;` it just repaet non stop but if you put ` animation-iteration-count: 3;` it does it three time and stop


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
