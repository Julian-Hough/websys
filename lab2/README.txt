Name: Julian Hough
Class: Web Systems Development

Part 0:
	Didn't use virtual host to serve this lab. Used Notepad++ and Chrome.

Part 1:
	I used unordered lists and created list items within that made up the columns of my table without
	using a table tag. As such each list item had an embedded unordered list made up of more list items
	that were of a different category. This is semantically correct since lists can be within more lists
	and can be organized by columns or rows depending on coder's preference. As such for the artist, album,
	track, genre, and year, only text was necessary. Each column's list item has their own class which helps
	organize the table and make css alterations easier. The albumcover and website columns used image tag and
	a tag respectively which are semantic considering they reference to something outside of the document. 
	

Part 2:
	For the XML part of this lab, I organized my playlist differently compared to the HTML version. In this
	it makes hierarchical sense since the root node is playlist, with song child nodes. Each song node has
	each category allowing additional songs to be added easier to implement. The first song node acts as the
	header allowing viewers of the page know which column is which. Viewers of the code can easily see
	that the columns are easily recognized since the tags used matched with the category.

Part 3:
	Part 3's html is the same one used in part 1 except that the CSS used is external and fundamentally different.
	The CSS starts off with .covers class being set to 100x100 pixels so testing images won't be huge when implemented.
	The table id has a 1 px border with overflow set to auto to ensure the border is actually around the contents.
	List-style is set to none to get rid of unecessary bullet points. Then the li ul under table id centers the text
	making sure it's center relatively by margin-left and margin-right. To allow albumcovers to skip over the other items,
	it was floated right, while the other elements were floated left. The header class was implemented for the desired
	output and uses !important to make sure that is will stay in that format without being overwritten. Then each class
	of the different categories are adjusted to complete part 3's output and width and height to look like a table. 
	The final touch of the footer id is set to allow it to stay in the middle and bottom of the page while still
	being in the table unordered list.
	

Part 4:
	The CSS implementation was widely different from the implementation used in part 3 with the HTML document. 
	To allow for the table look in that format, the display for the song and category nodes were set to inline-block.
	Without the display, the "table" would be condensed within one line wrapping around to the next. Basic requirements
	were met by calling upon certain categories such as track, albumcover, artist, and album. To allow the HTML tags to 
	work, special coding was used within the root element to allow images and hyperlinks to work. Track was floated left
	and albumcover was floated right, while everything else was text-aligned centered to fit the requested format. 

	
Note:
	On the lab page it states :
	This time, in order to be able to display your image and hyperlink using the HTML tags, you will need to add the html namespace to your XML file by adding an attribute to the root_element tag - which is done by adding;

	<root_element xmlns:html="http://www.w3.org/1999/xhtml">

	to your XML file after the stylesheet directive.
	
	However, it didn't work unless it was altered to <root_element xmlns="http://www.w3.org/1999/xhtml">. 
	I probably will have asked about it, but wanted to make sure it wasn't an error on the lab page for
	future students of Web Systems Development.
	
	
	
	
