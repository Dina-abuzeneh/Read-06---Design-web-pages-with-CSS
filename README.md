# Read-06---Design-web-pages-with-CSS
**What is CSS?**
- CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.




# What is CSS for?
-[x]As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

-[x] A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

-[x] Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.


# CSS syntax
- CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."


# CSS Modules
- As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module. For example, you could take a look at the MDN reference to the Backgrounds and Borders module to find out what its purpose is, and what different properties and other features it contains. You will also find links to the CSS Specification that defines the technology (see below).

- At this stage you don't need to worry too much about how CSS is structured, however it can make it easier to find information if, for example, you are aware that a certain property is likely to be found among other similar things and are therefore probably in the same specification. 

- For a specific example, let's go back to the Backgrounds and Borders module — you might think that it makes logical sense for the background-color and border-color properties to be defined in this module. And you'd be right.



# How To Add CSS:
There are three ways of inserting a style sheet:

1- External CSS
2- Internal CSS
3- Inline CSS


1- External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.


2- Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.
  
  
  3- Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
  
  
  
  **CSS color Property**
  - CSS Syntax
- color: color|initial|inherit;
  
  # Example
Set the text color with a HEX value:

body {color: #92a8d1;}
  
  #Example
Set the text color with an RGB value:

body {color: rgb(201, 76, 76);}
  
  
  
  
  # CSS reference
- Use this CSS reference to browse an alphabetical index of all of the standard CSS properties, pseudo-classes, pseudo-elements, data types, functional notations and at-rules. You can also browse key CSS concepts and a list of selectors organized by type. Also included is a brief DOM-CSS / CSSOM reference.

1- Basic rule syntax
- Style rule syntax
style-rule ::=
    selectors-list {
      properties-list
    }
  
  - Style rule examples
1- strong {
  color: red;
}

2- div.menu-bar li:hover > ul {
  display: block;
}
For a beginner-level introduction to the syntax of selectors, see our guide on CSS Selectors. Be aware that any syntax error in a rule definition invalidates the entire rule. Invalid rules are ignored by the browser. Note that CSS rule definitions are entirely (ASCII) text-based, whereas DOM-CSS / CSSOM (the rule management system) is object-based.
  
  # selecotor:
 # Basic selectors
Basic selectors are fundamental selectors; these are the most basic selectors that are frequently combined to create other, more complex selectors.

1- Universal selector *, ns|*, *|*, |*
2- Type selector elementname
3- Class selector .classname
4- ID selector #idname
5- Attribute selector [attr=value]
  
