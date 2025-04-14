# Entry 5
##### 4/11/25

## Content:
The tool I been learning and researching about is Animate.css. Through this I learned many stuff like knowing how to add time `animation-duration`, using it for interactions, animation-repeats, `animation-iterartion-count`, using `@Keyframe` for my animation and using animation to change the direction for the roation of the elemeent. I learned my tool through watching youtube video and following along with them as the video goes on. I also tinker through chnaging the  code, trying to see what each code does and what will occurs if certain things happens.

#### Using iteration count and duration:  
The `animation-iteration-count` allows you to choose how much time it pops up and repeat the actions. So through putting animation-iteration-count: infinite; it just repaet non stop but if you put  animation-iteration-count: 3; it does it three time and stops. For example in my pickcode i use to tinker in. I change the `animation-iteration-count` of my first section box to 10. This made the section goes in and out 10 times.  While for ` animation-duration` it determined the speed of my section box. when I put it at 1 the boc comes in super fast, but when i set the duration count to 10, it will come in a very slow pace. So in the example code below it shows the section coming in at a duration of 1 and an interation count of 10.
 **Example CSS Code:**
 ``` CSS
   #section-1{
    animation-duration: 1s;
    animation-iteration-count:10;
}
```
#### Using Animation delay with animation slide in:
Through making the `class="animate__animated animate__slideInDown">` there will be a cool animation of the text sliding down
you can make it slide in from the left using `class="animate__animated animate__slideInLeft"` and for sliding in front the right it would be the same thing but u change left to right. This really cool when you  add on delay. I did that to my section  class which have `animate__animated animate__slideInLeft`. I gave my section 1 a delay of 1 while giving my section 2 a delay of 2 through putting `animation-delay`in my CSS.  
**Example:**
``` CSS
   #section-1{
    animation-delay: 1s;
    animation-duration: 1s;
    animation-iteration-count:10;
}  
 #section-2{
    animation-delay: 2s;  
   
 }
```
## Skills:
Image of my section 1 coming in first from the left while my section 2 shows it coming in from the right a second after section 1.
![image](https://github.com/user-attachments/assets/bf73851e-5c30-4963-a21f-39722c949420)





[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
