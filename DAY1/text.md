ANIMATIONS

- Starting point
- Ending point 
- Duration
- Easing
- Path of the Animation


<!-- @Path OF the Anmiation 

A ------------- B 

there are Infinite ways to go from A to B



#WEB Animation 

1] css :- fast but limited
2] JS :- complex manual_optimize ,  -->

@Animation Libraray 

GSAP - simple , optimize , less code 

Green SOck Animation Platform 

syntax - 

gsap.method("element",{properties})

gsap - npm  [npm i gsap]

import {gsap} from "gsap"

4_Methods [

.to    = [From starting point to ending point]
.from = [From Final state to Initial State]
.fromTo = [give Both Start And END Properties]
.set

]

select one Element 

gsap.to('.box',{property})

for selecting all elemennts we all elements in a array

<!-- if we dont give any unit then the default is px ex 100px    we can give if we want 100vw -->


gsap.to(['.box'],{
    x:700,
    delay:0.8,  
    duration:1

 })

gsap.from(".box",{
    x:700,
    delay:0.5,
    duration:0.5,

})

gsap.fromTo(".box",{

    x:0
  
},{
    delay:0.5,
    x:400,
    y:200,
    duration:0
})


gsap.set("./box",{

})

@PROPERTIES




