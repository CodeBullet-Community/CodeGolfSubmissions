You all know that Code Bullet (Evan) hasn't uploaded in quite some time. You might think he's just being lazy, but there is actually a very good reason for that! As you may know, he lives in Australia where falling into space is a rather common occurrence! Most of the time he would just come back quickly but this time he got lost in an asteroid field. Help him get back by counting the asteroids!

**Rules:**\
    **a.** To represent 3d space the input notation consists of nesting brackets ("[]"s) so that the outer brackets represent the space itself, the group of brackets immediately inside those represent each plane, and the brackets inside those represent each line, the elements inside each line are not separated by commas, spaces, dots, or any other kind of separator. For example, [[[00][00]][[00][00]]] represents a 2x2x2 space filled with 0s, [[[00][00][00]][[00][00][01]]] represents a 2x3x2 space filled with 0s and a 1 in one corner.\
    **b.** The input will always represent a rectangular prism.\
    **c.** In the input, the value 0 is used to represent empty space and 1 is used to represent the presence of an asteroid\
    **d.** If 2 or more 1s are next to each other, including diagonally, they are part of the same asteroid\
    **e.** Your program must output the number of asteroids

**Example:** [[[011][100][001]][[000][000][001]][[111][100][000]]] must return 3
 
**Understanding the input:**
```
   v no object at coord (0,0,0)
[[[011][100][001]][[000][000][001]][[111][101][001]]]
        there is an object at coord (2,1,2) ^
```
```
[ space
  [ plane 1
      [011] line 1
      [100] line 2
      [001] line 3
  ] /plane 1
  [ plane2
      [000] line 1
      [000] line 2
      [001] line 3
  ] /plane2
  [ plane3
      [111] line 1
      [101] line 2
      [001] line 3
  ] /plane3
] /space
```
<br/>

***
### Scores:
