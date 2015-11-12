## ShortDesc

Short descriptions can be difficult to compose because they are heavily reused throughout DITA documents. The text may appear in search engine results, previews for links, the first paragraph of a topic. In order to have the text make sense and be purposeful wherever it appears, short descriptions should follow certain guidelines. Short descriptions should not refer to text that may appear later in a topic, since that text may not always be present. The description should also not refer to the topic they're in (In this topic... etc.) as the text may appear outside of that topic, and it is an inefficient use of words.  Complete sentences of less than 35 words make the best short descriptions, but there can be exceptions to this. Lastly, the content of the short description should give the user a description the topic and why they'd want to read the topic.

## DITA Maps

DITA maps create the layout and structure that holds all of the DITA topics together. The organization of information can be very important, as it will define what topics are related to each other. Some topics can be parents of several other topics, while another topic may stand better alone. DITA maps control what topics gets included in a document; certain topics can be set to not be included in certain document types (not included in print, for instance).  If a topic is not in a DITA map, it will not be in the document. Lastly, it may be useful to make multiple DITA maps so the map does not get too long and categories of topics can be easily found.

## Linking

DITA allows for a hierarchy of topics and an order of topics. Collection type links can be used to show these relationships. There are four collection types. Sequence collection types will label  the numerical order of links in the order they should be performed. Choice collection types lets the user choose which of the steps they're going to perform (such as what beverage they'll make). Unordered collection types are for links that are related in some way, but have no set order and they will not be linked to one another. Family collection types will display the hierarchy between links, but this type does not imply an order, just that the topics are related and can be linked between each other. Deciding what collection type is needed can help better organize the document and let the user navigate between related items easily.

## Thoughts

I feel like I understand DITA maps and hierarchy pretty well, but I'm a little foggy on collection types. The biggest point of confusion is the purpose of choice vs family. Is it just a descriptive thing? They both link to the other files without a descriptive number, and seem very similar.

I think if I practiced using the collection types, I'd 'get' it better, but just reading it isn't enough to deeply understand it. I understand the short description needs better, but I think I'll only get skilled at those through practice.

# Task Analysis

Task: Use Jekyll to Create a Website/Blog

### What is the User’s Goal? 

To set up a basic website using Jekyll as hosted on Github.io


### Who Performs the Task? 

A user who is familiar with CSS and HTML and needs to create a website hosted for free.

### What does the User Need To Know About the Task?

It may take an hour or so to initially set up, but then updating the website will be easier in the future. 

This task may be too advanced for a new web programmer, but does not take advanced skills.

How Jekyll navigation/URLs work

how Jekyll variables work

How to write and name a post

how to link content to layout

how to import content from other files

### What Tasks Does the User need to perform to Accomplish the Goal?

Installing Jekyll

Setting up the folder structure

Writing a config file

Setting up variables

Create a layout

Write a post

Push content to Github


### When and Under What Conditions is The Task Performed?

People would use Jekyll if they wanted to have customized urls and a reusable page layout for their website. They would use Jekyll to create a new website, most likely.

### What is the Sequence of Tasks?

1) Install Jekyll

2) Create a GitHub Repo/Branch

3) Create Folder Structure

4) Create the config file

5) Create an index.html file

6) Create a base layout file

7) Create a design using includes

8) Create a post

9) Link to post from index.html page.

10) Declare additional, reusable variables

11) Push to GitHub

### What are the mental and physical steps required for each task?

Mental:

The user must have an idea for a website layout and content in mind. They user may need to decide what URLs and File names they prefer.

Physical:

The user will spend an hour or so at their computer setting up Jekyll files and code. The user will need to be able to use a computer and the internet.
  
### What are the potential distractions to accomplishing this goal?

The Jekyll URL structure/file layout does not work with the personal goals of the user.

The user needs advanced web programming features that would require a server-side scripting language.

### What is the expected result?

The website will be functional and appear on GitHub as it appeared on the user’s computer.
