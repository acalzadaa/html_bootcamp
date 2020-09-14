# HELP

## HTML Helping tables

| element  | description          | example            |
| -------- | -------------------- | ------------------ |
| br       | inserts a breakline  | `<br />`           |
| cite     | indicates citation   | `<cite>`           |
| em       | emphasis             | `<em>`             |
| h1,h2,h3 | indicates headers    | `<h1><h2><h3>`     |
| p        | inserts a paragraph  | `<p>some text</p>` |
| strong   | indicates importance | `<strong>`         |

### Commonly used core HTML attributes

| attribute          | description                                                                                                     |
| ------------------ | --------------------------------------------------------------------------------------------------------------- |
| class="text"       | Defines the general classification of the element                                                               |
| dir="ltr/rtl/auto" | Defines the text direction of the element content as left-to-right, right-to-left, or determined by the browser |
| hidden             | Indicates that the element should be hidden or is no longer relevant [HTML5]                                    |
| id="text"          | Provides a unique identifier for the element                                                                    |
| lang="text"        | Specifies the language of the element content                                                                   |
| style="definition" | Defines the style or appearance of the element content                                                          |
| tabindex="integer" | Specifies the tab order of the element (when the tab button is used to navigate the page)                       |
| title="text"       | Assigns a title to the element content                                                                          |

### Header Metadata elements

| Element | Description                                                                                                                |
| ------- | -------------------------------------------------------------------------------------------------------------------------- |
| base    | Specifies the document's location \ for use with resolving relative hypertext links                                        |
| head    | Contains a collection of metadata elements that describe the document \ or provide instructions to the browser             |
| link    | Specifies an external resource that the document is connected to                                                           |
| meta    | Provides a generic list of metadata values such as search keywords, viewport properties, and the file’s character encoding |
| script  | Provides programming code for programs to be run within the document                                                       |
| style   | Defines the display styles used to render the document content                                                             |
| title   | Stores the document’s title or name, usually displayed in the browser title bar or on a browser tab                        |

### Attributes of the meta element

| Attribute                                      | Description                                                                                         |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| charset=”encoding”                             | Specifies the character encoding used in the HTML document HTML5                                    |
| content=”text”                                 | Provides the value associated with the http-equiv                                                   | or name attributes |
| http-equiv=”content-type/defaultstyle/refresh” | Provides an HTTP header for the document’s content, default style, or refresh interval (in seconds) |
| name=”text”                                    | Sets the name associated with the metadata                                                          |

### HTML sectioning elements

| Element               | Description                                                                                                                            |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| address               | Marks contact information for an individual or group                                                                                   |
| article               | Marks a self-contained composition in the document such as a newspaper story HTML5                                                     |
| aside                 | Marks content that is related to a main article HTML5                                                                                  |
| body                  | Contains the entire content of the document                                                                                            |
| footer                | Contains closing content that concludes an article or section HTML5                                                                    |
| h1, h2, h3,h4, h5, h6 | Marks major headings with h1 representing the heading with the highest rank, h2 representing next highest-ranked heading, and so forth |
| header                | Contains opening content that introduces an article or section HTML5                                                                   |
| nav                   | Marks a list of hypertext or navigation links HTML5                                                                                    |
| section               | Marks content that shares a common theme or purpose on the page HTML5                                                                  |

| Element    | Description                                                                                                                                |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| blockquote | Contains content that is quoted from another source, often with a citation and often indented on the page                                  |
| dd         | Contains the description or definition associated with a term from a description list                                                      |
| div        | Contains a generic grouping of elements within the document                                                                                |
| dl         | Marks a description list containing one or more dt elements with each followed by one or more dd elements                                  |
| dt         | Contains a single term from a description list                                                                                             |
| figcaption | Contains the caption associated with a figure HTML5                                                                                        |
| figure     | Contains an illustration, photo, diagram, or similar object that is cross-referenced elsewhere in the document HTML5                       |
| hr         | Marks a thematic break such as a scene change or a transition to a new topic (often displayed as a horizontal rule)                        |
| li         | Contains a single item from an ordered or unordered list                                                                                   |
| main       | Marks the main content of the document or application; only one main element should be used in the document HTML5                          |
| ol         | Contains an ordered list of items                                                                                                          |
| p          | Contains the text of a paragraph                                                                                                           |
| pre        | Contains a block of preformatted text in which line breaks and extra spaces in the code are retained (often displayed in a monospace font) |
| ul         | Contains an unordered list of items                                                                                                        |

### HTML text-level elements

| Element | Description                                                                                            |
| ------- | ------------------------------------------------------------------------------------------------------ |
| a       | Marks content that acts as a hypertext link                                                            |
| abbr    | Marks an abbreviation or acronym                                                                       |
| b       | Indicates a span of text to which attention should be drawn (text usually appears in bold)             |
| br      | Represents a line break within the grouping element                                                    |
| cite    | Marks a citation to a title or author of a creative work (text usually appears in italics)             |
| code    | Marks content that represents computer code (text usually appears in a monospace font)                 |
| data    | Associates a data value with the marked text with the value attribute providing the value [HTML5]      |
| dfn     | Marks a defined term for which a definition is given elsewhere in the document                         |
| em      | Indicates content that is emphasized or stressed (text usually appears in italics)                     |
| i       | Indicates a span of text that expresses an alternate voice or mood (text usually appears in italics)   |
| kbd     | Marks text that represents user input, typically from a computer keyboard or a voice command           |
| marks   | Contains a row of text that is marked or highlighted for reference purposes [HTML5]                    |
| q       | Marks content that is quoted from another source                                                       |
| s       | Marks content that is no longer accurate or relevant (text is usually struck through)                  |
| samp    | Marks text that represents the sample output from a computer program or application                    |
| small   | Marks side comments (text usually in small print)                                                      |
| span    | Contains a generic run of text within the document                                                     |
| strong  | Indicates content of strong importance or seriousness (text usually appears in bold)                   |
| sub     | Marks text that should be treated as a text subscript                                                  |
| sup     | Marks text that should be treated as a text superscript                                                |
| time    | Marks a time value or text string [HTML5]                                                              |
| u       | Indicates text that appears stylistically different from normal text (text usually appears underlined) |
| var     | Marks text that is treated as a variable in a mathematical expression or computer program              |
| wbr     | Represents where a line break should occur, if needed, for a long text string [HTML5]                  |


### HTML embedded elements

| Element | Description                                                                       |
| ------- | --------------------------------------------------------------------------------- |
| audio   | Represents a sound clip or audio stream [HTML5]                                   |
| canvas  | Contains programming scripts used to construct bitmap images and graphics [HTML5] |
| embed   | Contains general embedded content including application or interactive content    |
| iframe  | Contains the contents of an external web page or Internet resource                |
| img     | Contains a graphic image retrieved from an image file                             |
| object  | Contains general embedded content including application or interactive content    |
| video   | Represents a video clip or video stream with captions [HTML5]                     |
