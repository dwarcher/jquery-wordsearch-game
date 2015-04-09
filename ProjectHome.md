This jQuery widget creates a grid of letters with words from the wordlist
These words are randomly placed in the following directions
  1. Horizontal
  1. Vertical
  1. Left-Diagonal
  1. Right-Diagonal
In addition, the letters are placed in forward or reverse order, randomly
Provision is made to overlap words

The User is expected to click on a letter and drag to the last letter of the
word. If the selected letters form a word that is in the word list the UI
will indicate that by crossing it out from the wordlist

If the user cannot find a word, she can click on that word in the
Wordlist. The UI will highlight that word in the grid and cross it out.

Check it out here: https://jquery-wordsearch-game.googlecode.com/svn/trunk/demo.html

**UPDATE:**
I've just added a version that includes support for touch devices. You'll find it in the `/branches/touch` branch. Please test and let me know if it works.

Check it out here: https://jquery-wordsearch-game.googlecode.com/svn/branches/touch/demo.html

Credit goes to [neelskruger](https://code.google.com/u/112077390852870612977/) and [Bartosz Idczak](https://code.google.com/u/110129208263466508546/) for the code in this development and test branch


---

**Usage:**
```
	$("#aDiv").wordsearchwidget({"wordlist" : words,"gridsize" : 12});

	parameters:
	gridsize - Size of grid to generate (this will be a square)
	wordlist - Comma separated list of words to place on the grid
```