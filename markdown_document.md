# What is Markdown?

**Nearly all Markdown applications support the basic syntax outlined in the original Markdown design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.

#### Headings
>To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (<h3>), use three number signs (e.g., ### My Header).


###### Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
######### Heading level 6

**Note:** Markdown applications don’t agree on how to handle a missing space between the number signs (#) and the heading name. For compatibility, always put a space between the number signs and the heading name.

---
## Emphasis
#### You can add emphasis by making text bold or italic
#### Bold

I just love **bold text**. 	
I just love __bold text__. 	
Love**is**bold

#### Italic
Italicized text is the _cat's meow_.

#### Blockquotes

> Dorothy followed her through many of the beautiful rooms in her castle.

#### Nested Blockquotes
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Lists

#### Ordered Lists
1. First item
2. Second item
3. Third item
4. Fourth item 

#### Unordered Lists
- First item
- Second item
- Third item
- Fourth item 

#### another type of list data
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item 

---
###### Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
# Heading IDs
###### Many Markdown processors support custom IDs for headings — some Markdown processors automatically add them. Adding custom IDs allows you to link directly to headings and modify them with CSS. To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading.

### My Great Heading {#custom-id}
---
##### Definition Lists

###### Some Markdown processors allow you to create definition lists of terms and their corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

# Strikethrough

##### You can strikethrough words by putting a horizontal line through the center of them. The result looks like this. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, **use two tilde symbols (~~) before and after the words.**

~~The world is flat.~~ We now know that the world is round.



