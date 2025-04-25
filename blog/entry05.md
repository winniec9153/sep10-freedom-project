# Entry 5
##### 4/11/25

## Content:
The tool I have been learning and researching about is [Animate.css](https://animate.style/#documentation). Through this I learned stuff like knowing how to add time `animation-duration`, use it for interactions, animation-repeats, `animation-iteration-count`, use `@Keyframe` for my animation, and use animation to change the direction for the rotation of the element. I learned my tool by watching YouTube videos and following along with them as the video goes on. I also tinker through changing the code, trying to see what each code does and what will occur if certain things happen.

#### Using iteration count and duration:  
The `animation-iteration-count` allows you to choose how much time it pops up and repeat the actions. So putting animation-iteration-count: infinite; it just repeats nonstop but if you put animation-iteration-count: 3; it does it three times and stops. For example in my pick code, I used to tinker in. I change the `animation-iteration-count` of my first section box to 10. This made the section go in and out 10 times.  While for ` animation-duration` it determined the speed of my section box. When I put it at 1 the box comes in super fast, but when I set the duration count to 10, it will come at a very slow pace. So the example code below shows the section coming in at a duration of 1 and an iteration count of 10.  
 **Example CSS Code:**
 ``` CSS
   #section-1{
    animation-duration: 1s;
    animation-iteration-count:10;
}
```
#### Using Animation delay with animation slide-in:
Through making the `class="animate__animated animate__slideInDown">` there will be a cool animation of the text sliding down
you can make it slide in from the left using `class="animate__animated animate__slideInLeft"` and for sliding in front the right it would be the same thing but u change left to right. This really cool when you  add on delay. I did that to my section  class which have `animate__animated animate__slideInLeft`. I gave my section 1 a delay of 1 while giving my section 2 a delay of 2 through putting `animation-delay`in my _CSS_.  
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
Image of my section 1 coming in first from the left while my section 2 shows it coming in from the right a second after section 1.
![image](https://github.com/user-attachments/assets/bf73851e-5c30-4963-a21f-39722c949420)
## Skills:
Based on this learning experience of my tool, some skills that I got from this was knowing how to add animation durations. So I learned how to control how long an animation lasts using `animation-duration`. So this allows you to adjust the speed of an animation. Another skill I achieved was knowing how to apply iteration count, I gained an understanding of how to repeat animation using `animation-iteration-count`, including how to make an animation repeated using infinite. I also got skills such as knowing how to use animation classes and knowing the basic use of _CSS animations_.






[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
