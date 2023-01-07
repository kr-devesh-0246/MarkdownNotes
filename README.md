<!-- Headings of diff sizes -->
<!--
# Heading 1
## Heading 2
### Heading 3
Can go upto no 6-->
#Markdown syntax Notes

<!-- Italicise -->
## Italicisation>
There are two ways to make italic text:-
#### 1. Using astericks
*This text* is in italics
#### 2. Using underscores
_This text_ is also in italics
Similarly we can do strong text using double astericks or double underscores.

<!-- Strong -->
##Strong
#### 1. Using double astericks
**This text** is made bold using astericks
#### 2. Using double underscore
__This text__ is made bold using underscores

<!-- Strikethrough -->
##Strikethrough
~~This text~~ is strikethrough

//Note- If you want to disable a special char put \before it
\*This text\* will not be italicised now

<!-- Horizontal Rule -->
##Horizontal Rule
There are two ways to do this:-
#### 1. Using triple hyphen
---
#### 2. Using triple underscore
___

<!-- Blockquote -->
## Blockquote
> This is a blockquote, i.e. it is enclosed inside a block

<!-- Links -->
##Links
[Youtube](https://www.youtube.com/ "Click to go to Youtube")

<!-- Unordered List -->
## Unordered List
Use '*','+' or '-' to make an unordered list
* Item a
    * Nested item 1
    * Nested item 2
* Item b
* Item c

+ Item d
+ Item e
+ Item f

- Item g
- Item h
- Item i

<!-- Ordered List -->
## Ordered List
Use numberings to make an ordered list
1. First item
2. Second item
3. Third item

<!-- Images -->
## Images
Syntax: ![<Name instead>](url of image)
![Github-Logo](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

<!-- Code blocks -->
A code is used to show the code stub enclosed in a block markdown file.
>We get it done using triple quotations
```bash
npm install
npm start
``` 

```python
n = int(input("Input a dog's age in human years:"))

if 0<n<=2:
    h_year = n*10.5
    print(f"The dog's age in dog's years is {h_year}")

elif n>2:
    h_year = (n*10.5) + (n-2)*4
    print(f"The dog's age in dog's years is {h_year}")

else:
    pass
``` 

<!-- Tables -->
| Name      | Year of invention |
| --------- | ----------------- |
|Python     | 1991              |
|C          | 1972              |
|C++        | 1985              |
|Java       | 1995              |

<!-- Task list -->
* [x] Task a
* [] Task b
* [] Task c
# Markdown-Notes
# MarkdownNotes
