# Tool Learning Log

## Tool: **Animate.css**

---

### 3/7/25:
* used [ Animate.css ](https://animate.style/) and read through it
* watched a beginner tortial to get a better understanding [VIDEO](https://www.youtube.com/watch?v=VzbBcVRquYA)
* I modified the code by changing the animation from "`bounce`" to "`flash`"
    * allowing me to see how different effects function.
* tried using animate_repeat to make it last longer
    * but I realised it can only do up to 3 times
    * I changed the repeat to infinite so now it just keep bouncing up and down without stopping
* Next time I will try to expand my learning and try more cool animations
* animation borders



### 3/14/25:
* I watch this  [VIdeo](https://www.youtube.com/watch?v=S2KCXKAView) trying out the code they are doing using the animate.css
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

### 3/23/25
* I watch this  [VIdeo](https://www.youtube.com/watch?v=S2KCXKAView) trying out the code they are doing using the animate.css
* `<button class="animate__animated animate__bounce">Bounce Button</button>` this create a button with the animation bouce when pressed on it
* animate__repeat-1 (once)
* animate__repeat-2 (twice)
* animate__infinite (loops forever)
   * example code: `<div class="animate__animated animate__pulse animate__infinite">Infinite Pulse</div>`
* we can trigger animations with Java script
* we can combine multiple animations together which make things way easier
   * example: `<div class="animate__animated animate__zoomIn animate__delay-1s">Zoom and Delay</div>`
### 3/24/25
* i realized that you can also us ejava script to make ur animation alittle better
* you can also put `animation-iteration-count: # ` which allows you to choose how much time it pops up and repeat the actions.
* so by putting ` animation-iteration-count: infinite;` it just repaet non stop but if you put ` animation-iteration-count: 3;` it does it three time and stop
* I watch this viedo [Keyframe animation.css](https://www.youtube.com/watch?v=Bhj4miRkSOc)
* You can use @keyframe to rotate. keyframe can be used to make a detailed specification you want for an animaton.
 * you can use it to make something dirve which u can use the code:
    ``` CSS
      @keyframes drive {
           from {
               transform: translateX(10%);
            }
           to {
               transform: translateX(500%);
             }
        }
      ```

* each keyframe can define the CSS properties to apply at that specific point in the animation time line. example:
``` CSS
  @keyframes bounce {
0%, 20%, 40%, 60%, 80%, 100%{
tansfrom: translateY(0px);
}
  10% {
      transform: translateY(-200px);
      background-color: orange;
  }
  }
 30% {
      transform: translateY(-150px);
      background-color: yellow;
  }
 50% {
      transform: translateY(-100px);
      background-color: seagreen;
  }
 70% {
      transform: translateY(-50px);
      background-color: crimson;
  }
 90% {
      transform: translateY(-20px);
      background-color: deeppink;
  }
  ```
   * example code of rotation:
  ``` CSS
  @keyframes moveRotate {
  to {
      transform: translateX(-80vw) rotate(360deg)scale(5);
  }
  }
  ```
   * You can control the timeing of this animations forexample:
     ``` CSS
     .box{
     animation: moveRotate 2s ease infinite alternate-reverse;
     }
     ```
* you can aplly geometric transformation to an elemnt such as moving which is `transform: translateY(400px);`, scaling which is `transform: scale(2);`, rotating which is `transform: rotate(45deg);`, or skewing which is `transform: skew(50deg);`
   * translate(x,y)
      * move element horizaontally and vertically
   * scale(x,y)
      * scale and element by a specified factor in horizaontal and vertical direction, so it can be wide or long or both
   * rotate(deg)
      * roate a element clockwise
   * skew(x,y)
* you can also add animation when you hover over an element
  ``` CSS
  .box:hover {
  transfrom: rotate(135deg);
  }

 ### 4/6/25
 I watched [Master CSS Animation Property in 11 Minutes [Full Tutorial] 🚀](https://www.youtube.com/watch?v=Bhj4miRkSOc)
 * animite duration can be specified in milisecond or seconds.
 * animater iteration count determined how many time the animation repeats its action
 * animation direction defiend whether the animation will run normal or in reverse
    * example code (css):
     `animation-direction: alternate;` or `animation-direction: alternate-reverse;`
* Animation fill mode will defined how the animation will apply the styles from out keyframe  before and after its execution.
   * Example code : `animtion-fill-mode: both;`
* Animtion play state allows you to puase and resume
  * so forexample if you make it to running `animation-play-state: running; ` it will be running but if u want to pause the animation through hovering u can add a hover state.
     * code for hover state when having a box
       ``` CSS
       .box:hover{
       animation-play-state: paused;
       }
       ```
       So by doing this the animation will pause when you hover your arrow over the "box" which i Used for my animation.





<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
