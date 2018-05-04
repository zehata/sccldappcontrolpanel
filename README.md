### SCCL D'App Control Panel

Dependencies: -vanilla.js
To run: Use a mouse

The control panel uses a card layout, and a card can be added or edited at will.

To add a card and fill it up with contents you want,

`fillcontents(int, str, array)`

where int is an integer that is the index of the card that you would like to add. If you would like to place some contents in the third card, but the data for filling up the first two cards have not been obtained, simply let int be 3 and the first two cards will be created automatically where it will be blank, ready to filled up when you obtain the data.

str is the title of the card you wish to create, or the new title if you are updating the card.

array is an array of the contents you want to list out in the card that you want to create/ edit.

To edit a card, do as you will to create the card, the other cards will not be affected.

There is a sample in index.html, to see it in action, uncomment `//fillcontents(0,"Hello! I am a card.",["and","we","are","the","contents"])` on line 53.
