Note-Taking-Local-Storage-App

# Note Taking Local Storage App

A web page application that writes and deletes notes taken on it, displays existent notes from previous executions and looks nice. My motivation for this project is to show case a practical application of the local storage API.

# Screenshot of the Product

![screenshot](https://i.imgur.com/AOJSj4d.png)

## Getting Started

Clone the repo or copy desired text.

## Deployment

Any web browser can open this project, any device can run it too. For more details on the functionality of the local storage API you may consult the MDN entry on localStorage.

## Built With

- jQuery
- localStorage API

## Contributing

I encourage to make our own version of this project. For the logic aspect all you need is this file:

```
storage.js
```

You will also need to keep it consistent with the HTML classes and id's. That is detailed in (it's also a short file):

```
index.html
```

## Authors

- **Ray Garcia** - [My own portfolio](https://portfolio-v5.herokuapp.com/)

## License: MIT

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Acknowledgments

- Inspired by one of the lectures from this course: [the Web Developer Bootcamp by Colt Steele on Udemy](https://www.udemy.com/the-web-developer-bootcamp/learn/v4/overview). You can also see how the styling and HTML layout inspired my own solution.
- Help on solving the issue with deleting notes dynamically on this StackOverflow post:https://stackoverflow.com/questions/51804538/web-deleting-chosen-list-items-with-the-localstorage-api-and-jquery

## Live Demo

[Here](https://note-taking-website.herokuapp.com/index.html). Go ahead and give it a spin! Enter some notes. Copy the URL. Exit the browser. Reopen it and greet your notes again.

You will notice that I'm using Heroku as the host, given the name of the URL. That is because Heroku is an amazing product that I use to deploy most opf my projects. Furthermore, I will not be purchasing a domain on this website as I do not have the monetary funds available at this time.
