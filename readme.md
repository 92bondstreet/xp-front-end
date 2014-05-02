# Extreme Programming for Front-End Developers

12 Steps to adopt XP principles. 

Steps are listed from the simplest to the most complicated to implement in a Front-End team.

For each principle, we try to give some Front-End tips and best practices.

## Principle 1. Develop Coding Standards

	Conventions and code guidelines help developers 
		1. to communicate through their code  
		2. to educate developers about their team values (like working together)	
### HTML Code Guidelines

#### Doctype
Start with a proper doctype declaration for browsers

	<!DOCTYPE html>

#### Encoding
Use UTF-8 for internationalization

	<meta charset="utf-8">

#### Indentation
Indent nested and child elements

	<div class="tweet">
		<a href="path/to/somewhere">
	</div>

#### Naming
Name class and id with meaning

	<div class="top light" id="tweet-list">

#### Lower case
Lower case for tag and attribute

	<div class="top" id="header" attribute="value">

#### Close tag
Place a comment on closing div/section tags to indicate closing elements

	</div> <!-- Facebook post list -->

#### Double quotes
Double quotes on attributes value

	<img src="path.png" alt="Logo">

#### Reducing markup
Simple DOM design: less is more in markups using

	<!-- Not so great -->
	<span class="avatar">
		<img src="...">
	</span >
	
	<!-- Better -->
	<img class="avatar" src="...">

#### Deep diving
Sources and documentation

	https://github.com/necolas/idiomatic-html
	http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml
	http://make.wordpress.org/core/handbook/coding-standards/html/
	http://isobar-idev.github.io/code-standards/
	http://mdo.github.io/code-guide

### CSS Code Guidelines

#### Selectors
Selectors are evaluated right to left and should be as broad as possible. Really specific selectors are unnecessary and hinder performance.

	a.nav {
	  color: blue;
	}

#### Blocks
Use multi-line blocks and combination to make CSS cleaner and easier to read: Each style gets its own line

	.someDiv {
	  background: red;
	  padding: 2em;
	  border: 1px solid black;
	}

	h1, h2, h3 {
	  font-family: tahoma;
	  color: #333
	}

#### Comments
Use comments to denote groups.

	/* Here's how you comment CSS */

#### Whitespace
Put before and after each style block.

	a.nav {
	  color: red;
	}

	.some-class {
	  background: @purple;
	}

#### Naming conventions
Use meaningful class and id names

	.link.first {
	  color: red;
	}

#### Reset
The reset allows your layout look consistent in all browsers.

	<link rel="stylesheet" type="text/css" href="reset.css" />

#### Structure
Create Your HTML First and Organize the css file with a Top-down Structure.

	/* Generic classes */
	Style goes here...

	/* Header */
	Style goes here...

	/* Content */
	Style goes here...

#### Multiple classes
Add multiple classes to an element.

	<div class="box right"></div>

#### Shorthand
Combine styles in one line.

	#box {
	  margin: 8px 7px 0px 5px; // top, right, bottom, and left values, respectively.
	}

#### Alphabetize your Properties
Improved readability

	#cotton-candy {
	  color: #fff;
	  float: left;
	  font-weight:bold;
	  height: 200px;
	  margin: 0;
	  padding: 0;
	  width: 150px;
	}

#### Generic classes
Create generic classes to readability

	.left {
	  float:left
	}
	
	.right {
	  float:right
	}

#### Use Multiple Stylesheets
Make smaller and css multiple files.

	<link rel="stylesheet" type="text/css" href="reset.css"/>
	<link rel="stylesheet" type="text/css" href="style.css"/>
	<link rel="stylesheet" type="text/css" href="widget.css"/>

### Javascript Code Guidelines

## Principle 2. Develop a Common Vocabulary

	Describe systems, features, defects... with metaphor and imagery.
	Simplify and clarify that everyone can tell about how the system works.

## Principle 3. Code and Design Simply
	
	In progress...

## Principle 4. Adopt Test-Driven Development

	In progress...

## Principle 5. Play the Planning Game

	In progress...

## Principle 6. Integrate Continually

	In progress...

## Principle 7. Adopt Collective Code Ownership

	In progress...

## Principle 8. Refactor Mercilessly

	In progress...

## Principe 9. Add a Customer to the Team

	In progress...

## Principe 10. Release Regularly

	In progress...

## Principe 11. Work at a Sustainable Pace

	In progress...

## Principe 12. Practice Pair Programming

	In progress...

## Deep diving

[Extreme Programming Wiki](http://c2.com/cgi/wiki?ExtremeProgramming)

[Extreme Programming Pocket Guide by Chromatic](http://shop.oreilly.com/product/9780596004859.do)


## Authors and contributors

### Current
* [Yassine Azzout](http://yass.io) (Creator)

### License
[MIT license](http://www.opensource.org/licenses/Mit)