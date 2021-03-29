# MUSTACHE and FLEXBOX

## Templating with Mustache

Mustache is a logic-less template syntax because it only works with tags and some tags are replaced with values

We need to include the mustache.js file in order to start using it.

Mustache is written inside curly braces `{{ value }}`, whatever is inside the curly braces, mustach will look for the name property and replace it with its actual value just like in the example here : `Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });` `// returns: Hello, Sherlynn`

## Flexbox

Flexbox layout helps to provide a better way to lay out and align elements in CSS
as its intended to be used to fill any unused space in the container by stretching or shriking element so that an overflow wont happen

which means that the actual size of an element doesnt matter , this is a positive way to support many different screen sizes as its gonna shrink/expand the empty spaces just fill the empty places

flex has too many useful properities to help the developer place the elements in a flexable ways, just like `flex-wrap` which helps to wrap the content instead of shrinking them to fit in a one line ex: `.container {flex-wrap: nowrap | wrap | wrap-reverse;}`
or `flex-grow` as it helps in how the items in the container should take a size more than the other items by giving each item a flex grow value, ex: `.item {  flex-grow: 4; /* default 0 */}`
If all items have flex-grow set to 1, the remaining space in the container will be distributed equally to all children. If one of the children has a value of 2, the remaining space would take up twice as much space as the others (or it will try to, at least).
