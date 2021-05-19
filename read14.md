## Transforms
- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.
-  Three-dimensional transforms work on both the x and y axes, as well as the z axis. 
#### Rotate
- the rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. 
- syntax:- 
   transform: rotate(20deg)

#### scale
-the default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.   

- syntax:-
transform: scale(.75);
transform: scale(.5, 1.15);

* # Combining Transforms
- syntax:
 transform: rotate(25deg) scale(.75);



 ## Transitions
 - There are four transition related properties in total, including transition-property, transition-duration transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

 - example:-
   .box {
    background: #2db34a;
    border-radius: 6px
    transition-property: background, border-radius;
    transition-duration: 1s;
    transition-timing-function: linear;
  }
  .box:hover {
    background: #ff7b29;
    border-radius: 50%;
  }

  - not all properties may be transitioned.

  - handful of the more popular transitional properties include the following:
background-color
background-position
border-color
border-width
border-spacing
bottom
clip
color
crop
font-size
font-weight
height
left
letter-spacing
line-height
margin
max-height
max-width
min-height
min-width
opacity
outline-color
outline-offset
outline-width
padding
right
text-indent
text-shadow
top
vertical-align
visibility
width
word-spacing
z-index


## Animations (Animations Keyframes , Animation name)

- To set multiple points at which an element should undergo a transition, use the @keyframes rule.
- example:
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
 then
  .stage:hover .ball {
  animation-name: slide;
}

