# SCSE-HTML

This is a self contained file/app that uses html, css, and js with the library marked to enable simple editing, saving, and printing of "documents".

Read more bellow to get a better understanding of how this works.

## Books

The main unit of this app is a book.

The selected book is at the top of the page. The currently selected book sould be 'Quick guide'.

You can change name, delete, or add a new book using the buttons to the right of the selected book.

Depending on the selected book sections for that book will be showed.

## Sections

Everything is organized in sections. Sections have a title and markdown content. So far this is the third section. The others before being 'Books' and the intro.

### Main Title

The main title is the first thing in the section and is underlined by a double line.

### Markdown Content

Everything under the double lines of the title is the markdown content

### Editing

#### Creating

To add sections press the top or bottom '+' buttons.

#### Edit area

To open the edit area click on the 'Edit' button on the right side of sections.

##### Deleting

After opening the edit area press the '🗑' button. After deleting recovery is not possible.

##### Title

The title is edited as a single line string at the top of the edit area.

##### Content

The content is edited as markdown in a multi line textbox in the edit area below the title.

#### Moving

To move sections use the up/down arrow buttons in the edit area.

## Saving

Saving is done with Ctrl + s. You can name the html file anything as long as it ends with '.html'. The resulting file will have the content and everything necesary to be opened in a browser.

Any changes are not saved in any way untill pressing Ctrl + s.

## Images

Adding images is done with Ctrl + i.

The markdown format is

    ![](# "img-example")

and will appear as

![](# "img-example")

## Printing

To print (to a printer or as PDF) press Ctrl + p. This will open the browsers print dialog.

When printing the selected book, the title occupies the first page and appears framed. Also, each section begins on a new page.
