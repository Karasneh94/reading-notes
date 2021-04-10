# SENDING FORM DATA

The `<form>` element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are action and method.

* action

The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

`<form action="/students">`

* method

The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method

`<form action="/student method="GET">`

`<form action="/student method="POST">`

## Viewing HTTP requests

steps to view http request using chrome browser

1. Open the developer tools.
1. Select "Network"
1. Select "All"
1. Select "the route" in the "Name" tab
1. Select "Headers"
