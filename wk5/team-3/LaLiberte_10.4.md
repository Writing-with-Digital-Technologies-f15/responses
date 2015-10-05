##Summary of Haas

Haas frames the case study in Chapter 6 as an argument that the shape, version, and existence of every literary technology is the result of a variety of _human factors_. Instead of viewing a particular technology as the winner of a survival of the fittest scenario, Haas calls for us to view this end product as the survivor of many different, and sometimes conflicting, human decisions. Haas finds this particularly true with computer writing tools, as humans consciously coded each piece to work as intended. These human decisions, warns Haas, may be based in politics, history, logistics, and theory, as well as someone’s personal idea of improvement.

Haas relates this to Vygotsky’s concept of meditational means by reinforcing that different writing tools have different effects on the process of writing. She also discusses the context and history of writing tools/technologies, noting that writers don’t make new technologies isolated from previous technologies and outside influence. 

The case study Haas chooses is the development of two aspects of the Andrew Toolkit, the programming library section of an educational computing system known as the Andrew Project at Carnegie Mellon University. Haas was part of one of many development groups for the project, specifically, the User Interface Group. She traces the histories of the scrollbar and menu interface in the toolkit, focusing on not just the immediate history of the scrollbar, but the conversation and situation surrounding changes. 

I found the author’s mention of status levels within the User Interface Group particularly interesting. Haas said that the “user advocates” were mostly academics in the humanities with less technical background and lower average education. The user advocates also tended to be women. It was also interesting that Haas brought up this context for the user advocates recommending changes, and then walked through issues potentially caused by the “ambiguous political status” of the user advocates. I’m interested to see if my historicizing topic has a similar interplay of technical and non-technical people and any issues with hierarchical drama. 

The discussion on customization was also pretty interesting. I’m a Firefox user, so I’ve seen some very limited customization in my own browser and witnessed angry discussions about power users threatening to leave if their options were curbed. I wonder if there are many HTML elements that are tailored to power users and can be used to replace other, stricter elements.

##HTML5 Implications

Duckett and the HTML5 boilerplate discuss some difficulties in implementing backwards-compatible HTML5. Both because of differences in how new/old and differently branded browsers behave, Duckett and the HTML5 boilerplate mention specific ways to deal with old browsers, especially old Internet Explorer. To style HTML5 elements using CSS in older versions of IE, Duckett explains how to ask old browsers to use Javascript to view the page. The HTML5 boilerplate directs users to force IE versions to render websites in the most recent possible mode by using `<meta>` tags for compatibility in the header. The ordering of `<head>` and `<meta>` tags is also more important in HTML5 because of the placement of the charset declaration and this compatibility `<meta>` tag.

##Historicizing Ideas

###Idea A: `<span>` HTML element

I have a months-long running battle with the `<span>` element. As part of my work with CLA websites, I show department administrators how to use a content managment system, and how to transfer over content from their old site or other online documents into the new one. The `<span>` element tends to show up when these admins don't strip the formatting of copied and pasted text (and/or they don't paste as plain text). The `<span>` element, in my experience, brings in weird extra formatting like special text heights and colors that render strangely. I know the element [allows specific targeting of areas](https://html.spec.whatwg.org/multipage/semantics.html#the-span-element), so I'd like to find out more about the original purpose and existing purpose of the element. Are people using the element as intended? I think I've seen it used to add highlighting formatting, so I wonder if it pre-dates or works with CSS styling.

I use this element (or don't) as part of adjusting formatting, but it's use seems really general. Was there a particular issue this element was created to address?

###Idea B: `<mark>` HTML semantic element

I found the specs for the `<mark>` element super interesting—to me, the [definition of use for this element](https://html.spec.whatwg.org/multipage/semantics.html#the-mark-element) indicates clear input by writers, as this element is supposed to be a form of highlighting added by a second reader, which would be the case in academic writing when discussing/reviewing a paper or book. My hope would be that digging into `<mark>`'s history would find a different community or userbase asking for this feature than might be typical, as may be indicated by Mike Robinson's ["Draw attention with mark"](http://html5doctor.com/draw-attention-with-mark/) post and some of the comment section.

I'm a little unclear on how else the `<mark>` element can be used—it looks like using a search bar within a website, or potentially the CTRL-F function, could trigger the use of the `<mark>` element? I just wonder how you'd indicate an "if search, use CSS styling for `<mark>`" or if some of that is already assummed by the browser.
