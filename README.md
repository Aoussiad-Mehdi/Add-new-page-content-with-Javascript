Add New Page Content Recap : 


    .createElement() to create new elements
    .appendChild() to add a child element to a parent element as its last child
    .createTextNode() to create a text node
    .insertAdjacentHTML() to put HTML text anywhere around an element

Some important things to note are:

    if an element already exists in the DOM and this element is passed to .appendChild(), the .appendChild() method will move it rather than duplicating it
    an element's .textContent property is used more often than creating a text node with the .createTextNode() method
    the .insertAdjacentHTML() method's second argument has to be text, you can't pass an element
