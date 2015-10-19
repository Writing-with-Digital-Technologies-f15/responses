## Figure and Figurecaption in HTML5

### History

Figure and figurecaption are two elements that were introduced in HTML5. Figure is used to reference something in the article for example images, graphs, videos, diagrams, e.tc. Figurecaption goes hand in hand with figure element. Every time the figure element is used anywhere, a figurecaption with an explanation of the figure should always follow.

### Exigence

Was there a need for the introduction of the figure and figurecaption element? Why can’t we just stick to img, and use text to explain the element? Every time the figure element is used, there must also be a figurecaption. Some of the images/figures are self explanatory. Is there a need to have a caption every single time?

### How it works

<figure>
  <img src="tea.jpg" alt="Tea cup with steam and pen on bed">
  <figcaption>Journaling with Tea</figcaption>
</figure>

Above is an example of how to use the figure and figcaption. As noted in the history, figure element can be used to reference different things like images (as seen above), graphs, etc. A caption usually follows every time the figure element is introduced. There should only be one figurecaption in the figure block. 

### Figure vs Img tags

Images are linked to HTML pages. The img tag creates a holding space for the referenced image. If removed from where it was placed, it affects the flow of the document. 

Content of figure element is related to the main flow. It’s position is independent to the main flow. If removed from anywhere, it shouldn’t affect the flow of the article. 

Before  the introduction of the figure element, there was no way of adding a caption to an image. The only way one could add a caption, was by writing a paragraph explaining what the figure represents. But with the introduction of figure element, it also came with the figure caption where people can add a little explanation about the figure. 

Img is one of the things that go inside the figure. Therefore, the img was not completely replaced. It comes with the figure and enables the designer to do different things. 

Figure allows the designer to add other things like audio files, code, and graphs to the pages. 

### Figurecaption vs text explanation

Figurecaption comes after the figure element is used. It enables the designer to add a brief explanation of whatever figure is introduced without necessarily writing a paragraph to explain something. 

Text explanation is something that was suggested where every time someone used img tag and wanted to explain what it meant, they started a paragraph and wrote something about it.


