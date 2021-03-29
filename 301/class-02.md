# PAIR PROGRAMMING

## Jquery

Jquery is a JavaScript file that helps the user write simplier code, it has too many methods to help the user achive many tasks in a handy way
it is used to manipulate the HTML file just like DOM but its way simplier and easier

Jquery targets the elements of the HTML by selectors which are similer to CSS selectors, how ever it need to be written in a spicific syntax.
Here is an example:
`$('#id').addClass('newClass');`

Every Jquery starts with the `$`, and in order to use Jquery you have to import the Jquery file to your directory or simply by linking the link of it.

Usually Developers tends to add the Jquery file to their page and also to link the CDN Jquery link so that if the page failed to load the online one, it can use the second option
which is the imported one, this can happen by writing a logical script to theri HTML 
`<script>window .jQuery 11 document. write (' <script src=" j s/j query- 1.10. 2 .j s 11><\jscri pt> ' )</script>`

### WHERE TO PLACE YOUR SCRIPTS

The place that you write the `<script>` element affects the speed of loading your page
as the browser starts to download the JavaScript files and pauses every other element on the page that needs to be downloaded which causes a slower website

you can avoid that from happening by inluding it right before the closig body element because in that way the whole DOM is loaded since it is rendered line by line and then it will start downloading the JS files.


## 6 Reasons for Pair Programming

pair programming is where two developers work using only one machine. Each one has a keyboard and a mouse. One programmer acts as the driver who codes while the other will serve as the observer who will check the code being written, proofread and spell check it, while also figuring out where to go next. These roles can be switched at any time: the driver will then become the observer and vice versa.