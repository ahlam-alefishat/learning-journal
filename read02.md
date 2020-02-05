# Markdown is a way to style the text on the web, here are some instruction on how you can use it.

## You have to be aware that you will use few non-alphabetic characters thrown in, like # or * included in your text.

FOR TEXT
1. ### Headers

# One hashtag for h1 tag
## Two hashtags for h2 tag
###### Six hashtags for h6 tag

2.  ### Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

3. ### Unordered Lists
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
  ### Ordered lists 
  1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
   4. ### Images
   ![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

5. ### Links
http://github.com - automatic!
[GitHub](http://github.com)

6. ### Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.

7. ### Inline code
I think you should use an
`<addr>` element here instead.


## GitHub Flavored Markdown
1. ### Syntax highlighting

Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
2. ### Task Lists :If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests! 
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

3. ### Tables:you can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:
for example :

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

4. ### Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.










