<!--
**Jins10/Jins10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


-->
##Dog Scanner
-Set dog breed lists that I want to include
-Collect dog photos via Web Crawler
-Create model using Teachable Machine (https://teachablemachine.withgoogle.com/)
-Create model using own built Tensorflow code (https://medium.com/nanonets/how-to-easily-build-a-dog-breed-image-classification-model-2fd214419cde)
-Compare Accuracy and Loss per Epoch
-Improve dog model
https://jins10.github.io/Profile/dogScanner.html

##Tetris with Javascript, Css, Html
-Generate a playground that will store grid
-Generate grid with 25 px per square (GAME_COLS, GAME_ROWS), initialize GAME_COLS as 10, GAME_ROWS as 20.
-Each Rows should be prepended to the top of the grid. Using two for-loops, prepend lines. When all 20 Rows are generated add class top_line to the lastly added Row, prepend one extra Row and add class invisible. Invisible line will have value display:none, but will allow blocks to be able to be rotated right after it is rendered at the top line.
-When lines are deleted, new lines are prepended to the top. Add class invisible to lastly added line, and set  previous invisible to top_line.
-Make blocks.js that stores coordinate values of each block. Blocks will have different shape per rotatiob. Blocks will be render receiving block_type and direction as a parameter.
-make render block function that adds "moving" class. Blocks with "moving" class moves to y direction with down_interval that is pre-defined. Set initial x value of new block as 4, y as 1.
-make a seize function that removes down_interval, moving class and adds seized class.
-Add preview grid and make it render a block of random block_type. Whenever new block is seized(), render block with current block_type in preview. Preview is renewed and renders new random block of random block_type.
-Make a checkMatch() goes through each row and checks if entire row has block with seized class. It runs after each seized(). CheckMatch() removes line with full of seized class, adds score. If multi lines are removed at one seize, add bonus score. 
-Add more game features such as Stages, sound, multi_line removal display, etc.
https://jins10.github.io/Profile/games.html
