# CodeLou_FrontEnd


## Description
```
This website is a simple project designed to help a fantasy football league I am apart of keep track of things throughout the year easier.  You can look back at past year's drafts 
along with player records and news updates.
```

## Custom CSS Classes
```
The class(es) I created are:

1. .main-content.  This sytles the content of the page, depending on the 
size of the screen, specifically padding and margin.

2. .col.  This styles individual columns within the main content section 
for uniformity between content and pages.

3. .playoffs.  This styles within a standings column to change the 
background color depending on the position in table.

There are many more, but I've only included three in the README.
```

## Custom JavaScript Functions
```
The javascript functions I created are:

1. function dropDown() {
	var x = document.getElementById("myTopnav");
	if (x.className === "topnav") {
	    x.className += "responsive";
	} else {
	    x.className = "topnav";
	}	
}

A dropdown function, that when the user is in a mobile browser, 
collapses the menu that can expand on a button press.

2.  fuction myFunction() {
	var element = document.getElementById("toggle");
	element.classList.remove("hidden");
}	

A hidden button, that when clicked, displays additional content 
within a section.
```
