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