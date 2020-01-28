Evan needs your help again! The bushfires got to his home and he's been bravely fending it off with his garden hose. However, that's putting way too much strain on his house's plumbing system and it's only a matter of time before his pipes break and he runs out of water! It's your job to develop a system to find the leaks and fix them so he can continue fending off the flames and survive to post his next video.

**Rules:**\
  **a.** Input will consist of nesting brackets ("[]"s) containing coma separated 4 bit unsigned integers, the brackets are not separated by commas, spaces, dots, or any other kind of separator. The nested brackets will form a n*m square grid similar to a 2d Array. For example, [[3,3][9,6]] will represent a 2x2 grid.\
  **b.** Each 4 bit unsigned integer will represent one of 16 tiles (┃, ━, ┏, ┓, ┛, ┗, ┣, ┳, ┫, ┻, ╋, ╹, ╺, ╻, ╸, and the empty tile).\
  **c.** For encoding a tile, start with 0, add 1 if it's going up, 2 if it's going right, 4 if it's going down, and 8 if it's going left (┫ becomes 1+4+8=13).\
  **d.** Your program must rotate the tiles to form a loop and output the values of the rotated tiles in the same format as the input, or output -1 if a loop is not possible.

  **Bonus.** Working code that performs better than O(4^(n\*m)) gets an additional point in the leaderboard

Example: [[9,12,12,6][10,13,13,5][3,3,9,3]] must output [[6,12,6,12][5,7,13,5][3,9,3,9]]

**Understanding the input and output:**
```
Input           Output
9  12 12 6      6  12 6  12
10 13 13 5      5  7  13 5
3  3  9  3      3  9  3  9

┛┓┓┏            ┏┓┏┓
━┫┫┃            ┃┣┫┃
┗┗┛┗            ┗┛┗┛
```
<br/>

***
### Scores:
\- RShields: `4 points`\
\- Musty_Smell: `2 points`