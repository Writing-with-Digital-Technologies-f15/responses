## The canvas of my <'canvas'>
I have a picture of my proposed site map to use as a model. From the homepage, I have two major content blocks, an overview of the element and how it relates to video gaming, that each split into more specific sections and group related content together. As you get deeper into the site, the subtopics become more specific. I’ll write more about the content blocks I’m planning here. I will add more details and content to each block as I compose my thoughts and research.
+
## Overview
The <'canvas'> element creates a rectangle space on a web page for a developer to manipulate JavaScript to draw graphs and animations as well as handle photo compositions and video processing.

## Overview - How does it work / specs
The element itself is easy to form in an HTML document. The only code needed to build a canvas is a call for the element and settings for the width and height. To demonstrate, "<'canvas width="300" height="225"'><'/canvas'>" will build a 300x225 pixel canvas. Once formed, a developer calls the canvas from the Document Object Model (DOM) with code like this: 

/*function draw_b() {
  var b_canvas = document.getElementById("b");
  var b_context = b_canvas.getContext("2d");}*/
  
This code grabs a canvas with an id=b and defines it as a 2D plane. This creates the canvas's drawing context, where the drawing methods and properties used for the canvas itself are defined. Now, JavaScript bits and even CSS properties like fileStyle can manipulate the canvas.

## Overview - The Prompting Exigency (Historical context)
The story of <'canvas'>'s development begins in 2004, with Apple developing the tag for use with their own Safari browser and OSX WebKit component to operate Dashboard items. According to WHATWG specification writer Ian Hickson, Apple developed and introduced <'canvas'> to the Web "without going through any sort of standardization first (not even unofficial standardization like the WHATWG)..." (http://ln.hixie.ch/?start=1089635050&count=1), though WHATWG eventually did standardize the element. The managing editor of sitepoint.com, Adam Roberts, describes a situation that <'canvas'> responds to: 

"With HTML5’s Canvas API, we’re no longer limited to drawing rectangles on our sites. We can draw anything we can imagine, all through JavaScript. This can improve the performance of our websites by avoiding the need to download images off the network. With canvas, we can draw shapes and lines, arcs and text, gradients and patterns. In addition, canvas gives us the power to manipulate pixels in images and even video." (http://www.sitepoint.com/web-foundations/introduction-html5-canvas-element/)

By bringing JavaScript into the picture, <'canvas'> greatly expanded what kinds of graphics web developers could use for their pages.

## How does <'canvas'> relate to video gaming?
The <'canvas'> element actually can be used to create video games to be played in a web browser. JavaScript code is used to build the game elements, such as a player character, an image background and game rules such as win conditions and collision detection, which display to the player through the canvas. As one could imagine, browser games built in <'canvas'> are quite the different experience compared to more traditional video games played on a PC or dedicated game consoles.

## <'canvas'> and gaming - Trends / practices in its use

## Discourse - How do gamers / game developers fit in to discourse on canvas?
As relatively new as <'canvas'> is among web technologies, using it for game development is an even newer idea still. I would suspect that game developers are not quite prominent figures in the discourse surrounding how <'canvas'> works, and that their concerns and desires are not considered as heavily. Conversations saved in the W3C mailing-lists seems to confirm my theory. When the features that favor games are even brought up, developers favor them less to ensure other facets of the HTML work. Quoted from a discussion on GPU acceleration in <'canvas'>:

"It seems to me that one way or another we have to break something. Canvases drawn into once with no animation loop may go blank with GL-based hardware acceleration, whereas most video games will not function properly without it. I much prefer the former to the latter."

"No, we can't break the current implementation. It's perfectly reasonable for an author to draw into a canvas once and expect that the browser will manage it properly."

## Discourse - Where are canvas games in discourse around gaming as a whole?
Games developed for the web are relative newcomers in the gaming realm, having only gained a foothold aided by <'canvas'> in the mid-2000's while industry giants like Nintendo and Sony have been operating with dedicated consoles for decades already. The majority of discourse in gaming revolves around these few big names, with "indie" developers off to the side. 

Still, it seems to me that browser games have grown very quickly in terms of what they are capable of, and have a few advantages to tout over more traditional forms of gaming. While not developed with <'canvas'>, the browser game _Pokémon Showdown!_ uses JavaScript to faithfully recreate the battle gameplay of the _Pokémon_ games, while adding a ladder-based random matchmaking system that lets a player battle with other players on the site. Feats like this show that browser games are capable of matching up to even the most popular console titles of today. 

Geoff Blair, co-founder of web-based game company Lost Decade Games, describes ease of access as an advantage for web-based games; "People can just play your game right away..." (https://www.youtube.com/watch?v=QThg49A3qqI) as opposed to needing to purchase a physical copy from a retail vendor that requires the proper game console to play it. Yet, being a web-based independent game company in the current gaming realm has struggles as well, and perhaps a reason why newer web-based developers aren't in the main spotlight; Blair states that smaller companies "have to bring a lot of their own traffic" because they aren't already in the public eye, and that "just having a game that plays in a web browser is not enough to build a product on." HTML5 and <'canvas'> make it easier than ever to develop a game and distribute it to others, but one small game will have difficulty standing out amongst multitudes of browser games like it, let alone the biggest releases from a company like Nintendo.
