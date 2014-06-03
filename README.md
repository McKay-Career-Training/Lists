#Lists

For this assignment you will be creating a web page that has 3 different types of lists. You will need one unordered list, one ordered list, and one definition list. Within one of the previously mentioned lists, you also will need to insert a nested list.

Leaving the nest
---

Incase you don't remember from the book how to make a nested list. Let's go over it again. Take a look at the markup below.

	<ul>
		<li>List item 1</li>
		<li>List item 2
			<ul>
				<li>List item 2.1</li>
				<li>List item 2.2</li>
			</ul>
		</li>
		<li>List item 3</li>
		<li>List item 4</li>
	</ul>

Notice that in order to nest a list properly, you must start the *child* `<ul></ul>` before the *parent* `<li></li>` closes.

Keep in mind that each of these lists should have their own header to identify them. (`<h1></h1>`, `<h2></h2>`, `<h3></h3>`, etc). The lists probably aren't related to each other in any way, shape or form also. Remember back to the text assignment when we learned about a certain element that is used to seperate different thematic sections of content, be sure to take advantage of it in this assignment.

TL;DR
---

One last thing before you go, your requirements for this assignment are as follows.

- 1 HTML page named index.html
- Content is marked up correctly
- 1 Header for each list
- 3 distinct lists. (Ordered, Unordered, Definition)
- 1 of the lists must have a nested list within it
- A thematic way of seperating the lists

You may now begin writing your **HTML**. Have fun!!

