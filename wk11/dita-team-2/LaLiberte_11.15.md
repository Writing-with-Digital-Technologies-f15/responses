## Reading Responses
###Short Descriptions
In Chapter 5, "Short Descriptions," Bellamy, Carey, and Schoffeldt discuss the DITA element &lt;shortdesc&gt;. The authors describe this element as a challenge to use appropriately, largely because the element has multiple roles. Short descriptions act as:
- the introductory/first paragraph of the topic
- a link preview for child or related links
- an abstract for search engine results

Because short descriptions, like DITA topics themselves, can be viewed and used in multiple contexts, it's important for authors to recall these possible contexts when writing a topic's short description. 

General tips for writing short descriptions:
- **35 words or fewer:** in some cases, short descriptions can be up to 50 words, but usually 35 words should be the limit
- **Consistent use:** include short descriptions for every topic
- **Remember the context:** short descriptions are often displayed separately from the rest of the text, so don't use the description to introduce tables, lists, or figures
- **Remember the reader:** readers may be confused by inconsistency or sentence fragments, so always use complete, grammatical sentences
- **Create useful short descriptions:** don't simply repeat the content of the title; make sure every short description has useful, new information for the reader
- **Avoid self-referential statements:** these statements add to the word count without aiding understanding

The authors also discuss tips for writing short descriptions for specific topic types: task, concept, and reference. Finally, the authors discuss the abstract element, which can be used to place elements in the topic introduction that shortdesc doesn't allow or to include multiple, conditional short descriptions.

###DITA Maps and Navigation
DITA maps are the XML files that define and organize DITA topics. Just like a paper map, a DITA map shows the paths your user may follow.

Bellamy, Carey, and Schlotfeldt define three uses of DITA maps:
- including topics in an information set
- defining information architecture
- creating relationships between topics

Only topics included in the DITA map file are displayed in the output. Within the DITA map file, you can give task, concept, and reference topics a heirarchy so users know which topics are closely related and what to read next.

You can also make multiple DITA maps for overlapping content. The printed quick-installation guide for your Exprezzoh machine probably includes some different information than the Exprezzoh online help website, for example. The online help may have more detailed information on using extra features of the Exprezzoh machine, while the quick-installation guide may have focused on a small number of topics necessary to quickly and easily set up the machine.

The authors also discuss the value of information modeling, which allows to you map out and visualize where topics go and what topics are linked. Information modeling in the professional field is often done using modeling tools such as the Information Architecture Workbench. I doubt we'll use these tools in our class, but it would be interesting to see an example of their use in the workplace. 

Bookmaps allow DITA PDF output in a book-style format. The authors recommend using a regular DITA map if you produce multiple output formats from the same DITA map. However, if your only output is a book, bookmaps let you use an existing template.

DITA maps can contain other DITA maps (or submaps). By referencing other DITA maps within a single DITA map, you can organize all topics about, say, Exprezzoh, into sections based on use: installation, trouble-shooting, making a specific beverage... These submaps can also help groups of writers determine who should own, write, or edit what. Using DITA maps, you can also link to non-DITA content, override topic titles and short descriptions, and suppress topics from the table of contents.

###Linking (Excerpts)
Linking is an important part of creating navigable, user-friendly DITA output. Hierarchical links and collection-type links are two ways to link DITA content. 

Hierarchical links are created by nesting &lt;topicref&gt; elements in the DITA map. The output then displays these parent and child topics as nested topic links, which allows readers to understand how different topics are related. This also places a link to the "parent topic" at the bottom of each child topic.

You can use the collection type attribute to define the relationship between a set of nested topics. The collection-type attribute can be applied to &lt;topicref&gt; elements, &lt;topicgroup&gt; elements in a relationship table, and columns in a relationships table. 

There are four collection-type values:
- **Sequence:** numbers child topics; links to parent topic, previous sibling topic, and next sibling topic
- **Choice:** lists different topics as "choices" (no bullet points or numbers); links to parent topics but not sibling topics
- **Unordered:** lists different topics (no bullet points or numbers); links to parent topics but not sibling topics
- **Family:** lists different topics (no bullet points or numbers); links to both parent and sibling topics

###Thoughts & Feelings

I found it interesting that the selected chapters all mentioned relationship tables. I assume that we won't be making enough topics to warrant a relationship table, as I think these tables need more than three topics to be a good demonstration of how relationship tables work. However, it would be interesting to see an example of a fully fleshed out relationship table "in the wild."

My understanding is that the difference between "choice" and "unordered" collection-type values is not in the output presentation, but instead in the semantic difference of representing each topic as an exclusive choice instead of a dead-end in a list. Assuming I'm correct, this is an interesting look at semantic attributes and their value, as only someone looking at the output code would recognize the difference between topics organized as choices or simply an unordered list. However, by separating the two using different attribute values, the creators of DITA allow writers the option of presenting choices and unordered lists differently using a stylesheet.

##Task Analysis
1. **What is the user's goal?**

	The user's goal is to select and identify text in an HTML document using the SPAN or DIV element.

2. **What tasks does the student need to perform to accomplish this goal?**
  * Open the HTML document in a text editor
  * Find appropriate text
  * Determine whether the container should be block-level or inline
  * (Decide to use the DIV or SPAN element)
  * Insert the opening and closing tags
  * Add an identifying attribute
  * Save file/commit changes
  
3. **What are the mental and physical steps required for each task?**
  * Physical: Using device(s) (mouse, computer) to access text editor; navigating with mouse and keyboard; typing with keyboard
  * Mental: Understanding basic HTML, understanding the difference between block-level and inline elements
  
4. **Who performs the task?**
  * Audience: Users who want to apply meaning or styling to a particular part of their HTML document/website
  * Experience: Novice/Intermediate - basic prior knowledge of HTML and its elements but may not fully grasp use of specific elements
  
5. **When and under what conditions is the task performed?**
  * Reqirements: Text editor must be installed, HTML document must be written/present
  * Limitations: The user may not be clear on the use of many HTML elements, and may (once introduced to generic containers) go on to misuse SPAN/DIV; user must know enough to edit/write a basic HTML document; user may not know much about CSS or how attributes + CSS work together
  * Environment: The user is likely sitting down at a computer
  
6. **What are potential distractions to accomplishing the goal?**
  * Troubleshooting: The user's existing HTML document may not validate
  * Alternative path: The user may decide to use a semantic element instead of a generic container
  * Exception path: The user does not already have an HTML document
  
7. **What does the user need to know about the task?**
  * Duration: If the user has not already written the HTML document, this task could take a few hours or even a few days, depending on the desired length of the HTML document. If the document is already written and the text to be selected identified, this task could take less than 10 minutes.
  * Complexity: Easy for users familar with HTML and the difference between inline/block elements, difficult for users editing in HTML the first time 
  * Frequency: The user may decide to use this selector again within this HTML document or within other files associated with the same stylesheet.
  
8. **What is the sequence of tasks?**

	**1.** Open the HTML document in a text editor
    
	**2.** Find appropriate text
    
	**3.** Determine whether the container should be block-level or inline
    
	_(Decide to use the DIV or SPAN element)_
        
	**5.** Insert the opening and closing tags
    
	**6.** Add an identifying attribute
    
	**7.** Save file/commit changes
    
	**8.** Open the HTML file in a browser/check file in HTML validator

9. **What is the expected result?**

	The expected result of this task is the selection of text at the block- or inline-level. This will allow users to indicate something about the contained text and may lead to integration between this HTML document and a stylesheet.
