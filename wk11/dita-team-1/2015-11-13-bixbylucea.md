##Short Descriptions

This chapter explains the primary functions of the short description. It is not only used to introduce a topic, but is often also used as an abstract for search engines or in child topic links. Therefore, short descriptions might be the only thing a reader sees of your topic, and it has to be enough to get their attention. Short descriptions must be concise and carefully written to meet certain standards. Some of the standards that Bellamy et al describes are: introducing the topic and stating its significance; brevity; not starting a list; focusing on the benefits of the task; providing an overview of a procedure; concentrating on goals rather than product function; keeping it self-contained (no cross references or referencing other topics as though they are consecutive); and generally explaining the what, why, and how. To do more creative things with your short description—possible, even though all these rules seem a bit smothering—you can use the abstract element.

##DITA Maps

This chapter explains the DITA map, which allows users to connect topics and information in different ways. Using topicref, you can organize parent and child relationships between different topics, including task, concept, and reference, that support each other. The chapter describes some different ways to work with or display DITA maps, like information modeling, which helps you structure a hierarchy of topics through linking, and bookmaps, which makes book-like information appear with specific book-like qualities in a pdf. DITA submaps help organize a large amount of content. You can link to things outside the DITA map as well, using topicref. Finally, the chapter describes navigation within a DITA map. Once again topicref gives various options for customizing the way short descriptions, topic titles, and links appear in the DITA file. There are also ways to make certain content not appear in the table of contents or pdf if you had a reason for wanting to do that. I think “suppression” is an interesting concept and I’m curious in what context it would be used.

##Linking

Hierarchical links are the connection between parent and child topics. They occur when topicrefs are “nested” inside each other in a DITA map. The map output displays the child links underneath the parent links, like sub-information. Child topics can also stand on their own but include links to the parent topic. I think this seems like a good usability strategy--the hierarchy makes it easy for readers to tell how the topics relate to each other.
Collection type is an attribute of the topicref. There are four values for this attribute, which are sequence, choice, unordered, and family. Each value organizes parent and child links in a different way. Sequence develops a numbered list of child topics. This is helpful if your task has steps that need to be completed in a specific order. A child topic will link to its parent and its “siblings” on either side (this format reminds me suspiciously of the way the emails are set up in the W3C archive).

Choice collection type lists the child topics as options for a reader to choose. So the child topics are related to the parent but they are not as related to each other. (An example similar to the one in the book: parent topic: how to use an oven. Child topics: to melt cheese / to broil / to cook raw meat. Etc.) The unordered collection type is similar in that is does not order the child topics. But the child topics are not just “pick one,” they are all related to the parent topic but do not need to be read in any specific order. The child topics display a link to the parent topic.

Finally, the family collection type is also unordered but shows links to the parent and sibling topics and so creates a more visible relationship between all of them.
The end of this section describes using collection types in relationship tables.
 
##Questions

If you make short descriptions the hover text for links, how would readers necessarily know it was there? I feel like I would prefer it as plain text, even if it takes up more space.

I’m still not sure I understand what constitutes a good short description. There are a lot of rules laid out in the chapter and I would think it would be difficult to prioritize all of them. Which ones are most important to focus on? Additionally, I thought some of the example short descriptions were not very good, so even if there were specific rules to focus on most, I’m not sure I agree with their effectiveness.

I also don't completely understand what a relationship table is and how you use it.

##Task Analysis

Task: How to center text in CSS

###What is the goal?

To use CSS to center a specific item of text on a web page.

###What tasks does the user need to perform to accomplish the goal?

Navigate to the CSS for their HTML document or create an internal CSS

Select the text they want to center (is it h1s? a table? all paragraphs? block quotes?)

Add the attribute (most likely text-align)

Add the value (center)

Test the web page

###What are the mental and physical steps involved in each task?

Mental: decide what text should be centered based on stylistic goals and choices

Physical: All steps using the computer and writing the CSS: Adding the necessary code in the correct place

###Who performs the task?

Audience: A designer or code writer for a website

Experience: Any level; this could be achieved by someone with a low to medium level but could also be performed by an advanced user. The person who needs directions is probably low-experience. Could be for personal or professional use.

###When and under what conditions is the task performed?

Requirements: Either an external or internal CSS must have been developed

User must be on a computer and have the capability to be writing with code

Limitations: User must know how to write with CSS and HTML

User must know how to test an HTML document

Environment: On a computer with sufficient equipment and programs

Probably in a quiet location like an office or study space

###What are potential distractions to accomplishing the goal?

Incorrect coding; the code must me totally correct or it will not be displayed the right way if at all.

There must be a CSS (internal or external) for the coder to work from with enough detail to affect the web page (like correct head and everything) (I know when I was working on my project, only certain types and levels of CSS coding would do anything on my page. If something was off, nothing on the page would work).

Other stylistic decisions that might affect the way the page looks

Internal HTML vs CSS

Lack of knowledge on coding

###What does the user need to know about the task?

Duration: super speedy if you know what you are doing!

Complexity: Easy if you are familiar with coding software and terms
In general, it would be a good idea to know about coding and writing HTML and CSS. You should know how CSS is involved with HTML and how it works. You should know about element vs. attribute vs. value. You might be able to figure this out by using a base template that already has all the elements and/or attributes, but it will be trickier to figure out exactly how and where the values are used and you might need to use outside tutorials on HTML and CSS as well.

###What is the sequence of tasks or steps?

1) Decide what part of text you would like centered
2) Access CSS
3) Enter the correct element (p, h1, h2, blockquote, etc) and don't forget the space and then the bracket afterwards!
4) Enter the attribute text-align after a space
5) Enter the value center after a colon and a space
6) Close the brackets
7) Save the CSS or CSS/HTML file
8) Open it in a new web page to see if everything looks correct

###What is the expected result?

The desired text is fixed to the center of the space where it is located on the web page.
