# Overview
CrewGuru is a site that connects you to the freelance professionals that can get the job done. 

# Bugs
Please report any bugs in the [GitHub Issue Tracker](https://github.com/crewguru/prototype/issues)

# Building
This prototype was built using a practice called [atomic design](http://bradfrost.com/blog/post/atomic-web-design/) - Building a series of related, modular components that can be assembled into pages. 

## Sass
To support the atomic design process, the styling for the app is broken up into:
- Tools
- Modules
- Pages
- Vars

***SMACSS***
[SMACSS](https://smacss.com/) is a style guide for writing modular style-sheets. This build system adapts that style in Sass format. 

Example:

```css
.searchBox{padding: 10px}
.searchBox--inputField{background: white}
```

*or*

```sass
.searchBox
	padding: 10px
	&--inputField
		background: white
```		

***Bourbon***
[Bourbon](http://bourbon.io/) is a simplified mixin library similar to Compass. (but only the good bits)

## Jekyll
The prototype is built using [Jekyll](https://jekyllrb.com/), a static page generator. Jekyll will pull from the `/includes` folder to populate corisponding modules from the `/sass` directory. 






