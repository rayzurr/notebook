## Markdown Syntax Guide

### Basic Syntax

* **Headings:** Use hash symbols (#) to create headings. More hashes indicate a smaller subheading.
   * Heading 1 (# H1)
   * Heading 2 (## H2)
   * Heading 3 (### H3)

* **Bold and Italic:**
   * Wrap text in asterisks (*) for italics or double asterisks (**) for bold.
   * You can also use underscores (_) for italics and double underscores for bold.

* **Blockquotes:** 
   * Prefix text with a greater than symbol (>) to create blockquotes.

* **Lists:**
   * Ordered lists use numbers followed by a period (.) and a space.
   * Unordered lists use hyphens (-) or asterisks (*) followed by a space.

* **Code:**
   * Wrap inline code with backticks (`).

* **Horizontal Rule:**
   * Use three or more hyphens (-) or underscores (_) to create a horizontal line.
   
* **Links:**
   * Enclose link text in square brackets ([ ]) followed by the URL in parentheses ( ). You can optionally add a title within the parentheses.
   * Title: [https://www.example.com](https://www.example.com) 
   
* **Images:**
   * Use exclamation mark (!) followed by bracketed alt text ( ) and the image URL in parentheses ( ).
   * Alt text: image.jpg

### Extended Syntax (Not all applications support these)

* **Tables:**
   * Create tables using pipes (|) to separate columns and rows.
   * Add headers and define the table structure.
* **Fenced Code Blocks:**
   * Use three backticks followed by a language specifier (optional) on a new line to create a code block.
   * ```language
   {
       "firstName": "John",
       "lastName": "Smith",
       "age": 25
   }
   ```
* **Footnotes:**
   * Add citations using bracketed numbers after the text ([^1]). 
   * Define the footnote content below the text, preceded by the corresponding number and a colon ([^1]: This is the footnote).

* **Heading IDs:**
   * Assign a unique ID to a heading by adding {#custom-id} after the heading text. 

* **Definition Lists:**
   * Use a colon (:) to define terms after their listing.

* **Strikethrough:**
   * Wrap text in two tildes (~~) to create strikethrough.
   * ~~The world is flat.~~ 

* **Task Lists:**
   * Use hyphens (-) followed by a space for tasks. Add an "x" before the hyphen to mark a completed task.
   * - [x] Write the press release
   * - [ ] Update the website
   * - [ ] Contact the media

* **Emoji:**
   * You can include emojis directly in your Markdown text.
   * That is so funny! :joy:
   
* **Highlight:**
   * Double equal signs (==) enclose highlighted text.
   * I need to highlight these ==very important words==.

* **Subscript and Superscript:**
   * Use tilde (~) for subscript (H~2~O) and caret (^) for superscript (X^2^) 