# csscrashcourse
## Overview
Hands-on coding exercises to learn CSS (Cascading Style Sheets) by following [CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI&t=1s)

The video is about 1 hour and half long, which covers styles, selectora, declarations, etc. It teaches how to build a CSS cheat sheet that we can keep as a resource and we will also create a baisc website layout.


## What is CSS
CSS is a style sheet language NOT a programming language. It is used for website layout and design.


## Methods For Adding CSS
* Inline CSS: Directly in the html (not recommended)
* Internal CSS: Using `<style>` tags within a single document (not recommended)
* External CSS: Linking an external .css file (recommended)

Note: try to keep the presentation, functionality and styling completely seperate or as much as possible.


## CSS Selector
`selector { property: value; }`


## Colors In CSS
* Color Names
* HTML5 Color names
* Hexadecimal
* RGB


## Box Model

    +--------------------------------------------------------------------------------------------------+
    |                                           top margin                                             |
    |             +---------------------------------------------------------------------+              |
    |             |                             top border                              |              |
    |             |             +----------------------------------------+              |              |
    |             |             |              top padding               |              |              |
    |             |             |              +---------+               |              |              |
    | left margin | left border | left padding | content | right padding | right border | right margin |
    |             |             |              +---------+               |              |              |
    |             |             |             bottom padding             |              |              |
    |             |             +----------------------------------------+              |              |
    |             |                           bottom border                             |              |
    |             +---------------------------------------------------------------------+              |
    |                                         bottom margin                                            |
    +--------------------------------------------------------------------------------------------------+


## Margin & Padding Shorthand
Syntax:

    p {
        margin-top:5px;
        margin-bottom:5px;
        margin-right: 10px;
        margin-left:10px
    }

Shorthand:

    p {
        margin: (top) (right) (bottom) (left);
    }

    p {
        margin: 5px 10px 5px 10px;
    }

Shorthand for top/bottom is the same and right/left is the same:

    p {
        margin: (top/bottom) (right left);
    }

    p {
        margin: 5px 10px;
    }
    

## Positioning in CSS
* Static
* Relative
* Absolute
* Fixed
* Initial
* Inherit

