# HTML

## TEXT

* ***When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.***

- **Structural markup: the elements that you can use to describe both headings and paragraphs.**

- **Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.**

* *Headings:*HTML has six "levels" of headings start from < h1 > to < h6 >

* *Paragraphs:*To create a paragraph, surround the words that make up the paragraph with an opening < p > tag and closing < /p > tag.

* *Bold & Italic:*
- By enclosing words in the tags < b > and < /b > we can make characters appear bold.
- By enclosing words in the tags< i > and < /i > we can make characters appear italic.

* *Superscript & Subscrip:*
- The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.
- The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

* *White Space:*In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines .

* *Line Breaks & Horizontal Rules:*
- As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag < br />.
- To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections sing the <hr /> tag.

### Semantic Markup

* *Strong & Emphasis:*
- The use of the < strong > element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.
- The < em > element indicates emphasis that subtly changes the meaning of a sentence. 

* *Quotations:*
- The < blockquote > element is used for longer quotes that take up an entire paragraph. Note how the < p > element is still used inside the < blockquote > element. 
- The < q > element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the < q > element, however Internet Explorer does not — therefore many people avoid using the < q > element.

* *Abbreviations & Acronyms:*
If you use an abbreviation or an acronym, then the < abbr > element can be used. A title attribute on the opening tag is used to specify the full term.

* *Citations & Definitions:*
- When you are referencing a piece of work such as a book, film or research paper, the < cite > element can be used to indicate where the citation is from.
- The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is
known as the defining instance of it.

* *Author Details:*
The <address> element has quite a specific use: to contain contact details for the author of the page.

* *Changes to Content:*
- The < ins > element can be used to show content that has been inserted into a document, while the < del > element can show text that has been deleted from it.
- The element indicates something that is no longer accurate or relevant (but that should not be deleted).


### Adding HTML5 Audio to Your Pages

HTML5 introduced the < audio > element to include audio files in your pages. As with HTML5 video, browsers expect different formats for the audio. The < audio > element has a number of attributes which allow you to control audio playback: src This attribute specifies the path to the audio file.

***EXAMPLE:***< audio src="audio/test-audio.ogg" controls autoplay >

* ***Browsers that support the HTML5 elements do not all support the same video and audio formats, so you need to supply your files in different formats to ensure that everyone can see/hear them.***



## Css

***CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.***


* *CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.*

* *CSS rules usually appear in a separate document, although they may appear within an HTML page.*


## JAVASCRIPT
***A script is a series of instructions that a computer can follow one-by-one.Each individual instruction or step is known as a statement. Statements should end with a semicolon.***

* *You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.*

* *A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.*

* ***JavaScript distinguishes between numbers,strings, and true or false values known as Booleans.***


#### ARRAYS
***An array is a special type of variable. It doesn't just store one value; it stores a list of values.*** 

* *You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).* 

* *Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).*



#### EXPRESSIONS
***An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.***

* *Expressions rely on things called operators; they allow programmers to create a single value from one or more values.* 



- ***JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class.*** 




### Decisions & Loops
***the code can take more than one path, which means the browser runs different code in different situations.*** 


* *Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or fa 1 se).* 

* Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands. 


* if ... else statements allow you to run one set of code if a condition is true, and another if it is false. 