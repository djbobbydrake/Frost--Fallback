Frost--Fallback
---

Frost-Fallback is a fallback library written in sass. It's created so you can use new features without having to care about older browsers

## Install

* Git clone `git clone https://github.com/Itrulia/Frost--Fallback.git`
* Bower install `bower install frost--fallback`
* [Download newest version here](https://github.com/Itrulia/Frost--Fallback/archive/master.zip)

**Warning:** if you install it without Bower, you have to download the dependency on your own. The dependency can be found [here](https://github.com/Itrulia/Frost--Unit)

## Getting started

First off you have to import *_frost--fallback.scss* in your project.

From here you cann call `@include rem-fallback(property, values)`. 

As an example:

````
body {
	@include rem-fallback(padding, 1rem, 1.5rem);
}
````

which will output as:

````
body {
	padding: 16px 24px;
	padding: 1rem 1.5rem;
}
````

## Thank you

Thank you for using one of my libraries, if you need support , or have feedback, feel free to contact me (email or github).

