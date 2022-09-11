SELECTORS:
selectors consist of classes, html element, Id's etc that are used in a css stylesheet to target a particular element in the document for the purpose of styling. a selector body consist of 4the declaration property and value of the declared property.

simple selectors: 
    This type of selectors target html tags, id's classes and othere attributes added to the HTNL tag.

Universal selector:
    A universal selector also known as a wildcard is used to target every element in the document.

Type selector:
    This type of selector matches a particular HTML element directly. example
    article{
        padding:10px;
    }
    this causes every html article tag to have a padding of 10px.

Class Selector:
    This type of selector selects different types of html elements with the same class applied to them.

ID selector:
    An html element with an id should be the only element with that id value. No more that one element should share an id with the same value. An element with a single type Id, cannot be re used in the styles elsewhere.

Attribute selector:
    This involves using a certain attribute of an htmlo element or both attribute and its value to select an html element for stying purpose.
    example: [data-type='primary' s]{
        color:red;
    }
    s = case sensitive
    i = case insensitive

    Along with case operators, you have access to operators that match portions of strings inside attribute values.


    /* A href that contains "example.com" */
    [href*='example.com'] {
    color: red;
    }

    /* A href that starts with https */
    [href^='https'] {
    color: green;
    }

    /* A href that ends with .com */
    [href$='.com'] {
    color: blue;
    }

Grouping Selectors:
    This is the grouping of more than one html elements and sepatrating them with commas.

    strong,
    em,
    .my-class,
    [lang] {
    color: red;
    }

Pseudo Classes:
    This is used to target HTML element and put them in a state or change their state with certain state attributes when they are interracted with.
    example:

    a:hover{
        color: red;
    }

Pseudo Elements:
    This acts like it is inserting a new element in the targeted html element using css and is syntactically denoted using double-colon (::)
    example:
        a::before{
            
        }


