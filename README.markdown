Impact Scrum for Trello
===========

This is a fork of [sbalkum](https://github.com/sbalkum/TshirtScrumForTrello)'s Chrome extension that 
goes beyond the t-shirt sizing and introduces tags via square brackets, and helpful tag management additions.

T-shirt Scrum for Trello
===========

This is a fork of [Q42](http://q42.com)'s Chrome extension that uses T-shirt sizing rather than the
Fibonacci series. This is based on experience blogged at [stephenbalkum.com](http://www.stephenbalkum.com/archive/2014/08/18/what-metrics-to-collect-in-a-scrum-sprint-cycle/).

Also, the size delimiters have been changed to {} and || since parentheses and brackets are
frequently used in titles.

Scrum for Trello
===========

Scrum for Trello adds functionality to the awesome trello.com for use in Scrum projects.

Trello is the perfect online equivalent of the whiteboard with sticky notes aka the Scrum
board. One element we use are the storypoints. TrelloScrum gives you the ability to
make use of story points in Trello.

Setup
-----

This is a Chrome extension and you can install it via by loading the ImpactScrumForTrell 
folder as an unpacked extension.

How does it work?
-----------------
In the card titles you can add the estimated storypoints between curly braces. 
You can assign actual storypoints between pipe characters.
The points will be picked up by TrelloScrum and displayed in the upper right corner of the card.

For each list the total amount of story points will be calculated and shown in the title
of the list. Blue is estimated, and gold represents actual storypoints.

Once per second the story points will be detected and calculated. 
So changing a number or moving a card will be reflected almost immediately.


Credits
-------
ImpactScrumForTrello was developed by [Aaron Murray](https://github.com/akmurray/ImpactScrumForTrello)
TshirtScrumForTrello was developed by  [Stephen Balkum](https://github.com/sbalkum/TshirtScrumForTrello)
TrelloScrum was developed by [Marcel Duin](http://webglmarcel.q42.net/) and [Jasper Kaizer](https://twitter.com/jkaizer)
during our pet projects time at [Q42](http://q42.com).

Great improvements made by @nicpottier and @paullofte:
* The point value is moved to be a badge on the card.
* Added support for Zero Point Cards (0), Unknown Point Cards (?), Decimal Value Cards (.5)
* In addition I added the functionality to have the list total reflect the current filtered set of cards.


