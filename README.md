# BINGO generator
This program allows you to generate randomized 5x5 BINGO cards. The BINGO elements are words that you can input through a csv file. It is currently only designed for 5x5 grid size, but can be modified for other grid sizes as well.

## Usage
The `bingo.ipynb` notebook is the meat of the code. There are two blocks of code, the first one generates a card with all words filled, except the center, which is free. The second block generates a 5x5 grid, with 3 words per row. The rest of the words are blank and filled with some image if you want. 

Both work by reading in the `Bingo words - Sheet1.csv` file. The first column of this file should be all the words, and the first row will be skipped. Then, the word order is randomized, and the order of blank squares is also randomized. The grid is then filled, and the blank squares are filled with an image of your choice.

Choose how many cards you want to generate and hit run. They will be saved in `jpg` files.