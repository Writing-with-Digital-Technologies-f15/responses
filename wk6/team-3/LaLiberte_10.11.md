##Sources & Annotations: `<SPAN>`

###[fwd:Fonts (Benjamin C.W. Sittler & responses)](http://lists.w3.org/Archives/Public/www-style/1995Jul/thread.html#msg11)
W3 Public Mailing Lists, July 1995

This email chain begins with Benjamin C.W. Sittler proposing sway to select individual font characters by attributes and a better way to select fonts. He also suggests a "generic character-level text container tag in HTML 3.0” that could be used to apply styles to select text blocks: `<TEXT></TEXT>`. This tag, recommends Sittler, would only apply styles to its contents if it were attached to a stylesheet; the contents would otherwise appear unchanged.

Responses to Sittler’s email largely focus on his '<TEXT>' element. Alex Hopmann quickly replies that he has already proposed a character formatting element. '<C>', and asks if there are positive attributes to calling the element `<C>` (for “character”) rather than `<TEXT>`. (Other replies suggest `<FONT>`, `<ELEMENT>`, `<STRING>`, and `<MARK>`.) This sparks a discussion on readability and users, which is derailed by Paul Prescod, who dismisses the idea of semantically neutral tags like `<C>` or `<TEXT>` entirely. Prescod considers semantically neutral tags "incredibly,  horrifically easy to abuse when you don’t [sic] feel like looking up a tag in the HTML Spec.” Prescod’s harsh words are rebutted by Michal Young.

<q>You can't make html idiot-proof, because idiots are just too clever.  If semantically meaningless tags are rigorously excluded from html, some idiots will misuse semantically meaningful tags to obtain formatting effects (which will of course have bizarre effects in browsers that use different default stylistic conventions for the same semantic tags).</q>

This introduction to an early argument for a `<span>`-like element is a really interesting look into both the development of the idea and the surrounding conversation. Invested contributors defend and favor their own suggestions or modifications over other options, and ignoring dissent is as simple as not replying to someone’s reply. (Although it’s possible this email archive is incomplete, it’s interesting how few people responded directly to Prescod’s concerns.)

###["You can still use div"](http://html5doctor.com/you-can-still-use-div/)
Mike Robinson

My second source focuses on `<SPAN>`'s close cousin, `<DIV>`. In the face of new HTML5 semantic elements, Robinson makes the case for continuing to use `<DIV>`—when it's the best choice.

Both `<SPAN>` and `<DIV>` are semantically neutral elements, which means they do not stylistically change their contents unless the `style` attribute is added or a CSS stylesheet says otherwise. `<DIV>` is a _block-level_ (or flow content) _element_, which means it should be used for larger sections of content, like an image + caption, or a paragraph or paragraphs. Meanwhile, `<SPAN>` is a _character-level element_, meant to be used within sentences. Many HTML elements act like `<SPAN>` and `<DIV>` with semantics—instead of using `<DIV="article">`, with HTML5 you can now just use `<ARTICLE>`.

Robinson states:

> You will certainly use `<div>` less often in HTML5 than you did in HTML 4, but it’s still a valuable element to have in your toolkit. Sure, it’ll be picked last for the team because everyone else is better, but it’ll be the best damn generic container element there is!

This reflects where the `<SPAN>` element stands today, too. While there are other ways to semantically style and differentiate text, `<SPAN>` is what you should use when there isn't an element explicitly for a specific purpose.

##Memo

My historicizing project will focus on the `<SPAN>` element. So far, I've identified a few key ideas about the `<SPAN>` element and its development that I would like to touch on in the final historicizing project. I'm not sure what's too broad of a scope, or too narrow, so please let me know if you have ideas! I'm still working out the influence of print media on `<SPAN>` development, so feel free to chime in there, too.

- Clarifying the relationship between `<SPAN>` and `<DIV>` (inline/character-based and block elements/flow content) as well as that of semantically neutral and semantically meaningful HTML elements
- Introducing the ongoing developer discussion of separating content and styling/presentation/semantics, which ties into discussions of accessibility and semantically correct use
- Consolidation and politics in the history of `<SPAN>` development

Another source I've been reading is the [Internationalization of the Hypertext Markup Language](http://tools.ietf.org/html/draft-ietf-html-i18n-01). This draft first officially introduces the `<SPAN>` element as a way to mark text in different languages, potentially read from right-to-left. `<C>` was included as the generic character-level container of choice in an early HTML draft, but was eventually replaced by `<SPAN>`. This was proposed during a [larger discussion](http://lists.w3.org/Archives/Public/www-style/1995Dec/0039.html) about using the `style` attribute in HTML.



