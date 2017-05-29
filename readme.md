# Learning about ipfs

This is an app for learning the basics of IPFS. I, @chadoh, stole it from the TodoMVC React example: http://todomvc.com/. The React code is outdated and it's not what I'd build, but it's a simple app that demonstrates client-side storage, and that's what we're going for.

## Learn you an ipfs

When you get to [chapter 2 of the distweb book](https://flyingzumwalt.gitbooks.io/decentralized-web-primer/content/files-on-ipfs/lessons/wrap-directories-around-content.html), it'll suggest you add a whole directory to ipfs. That's when you use this app. Here's what you do:

* Download this repository
* Change [line 153 of app.jsx](/js/app.jsx#L153) and add your own name inside the `<h1>` (example: `<h1>Chad's Todo App</h1>`)
* Maybe make the text inside [the `<title>` tag in index.html](/index.html#L5) match your new title
* Check that the app looks the way you want it to by opening up your terminal app, changing into the directory with the code, and running `python -m SimpleHTTPServer` -- Now you can type `localhost:8000` into your browser and see your app. Does it have your name in the tab and on the page? Nice!

Now add this directory to ipfs.

You've now uploaded a whole app to ipfs! :raised_hands:


---

See the original React TodoMVC readme below:

# React TodoMVC Example

> React is a JavaScript library for creating user interfaces. Its core principles are declarative code, efficiency, and flexibility. Simply specify what your component looks like and React will keep it up-to-date when the underlying data changes.

> _[React - facebook.github.io/react](http://facebook.github.io/react)_


## Learning React

The [React getting started documentation](http://facebook.github.io/react/docs/getting-started.html) is a great way to get started.

Here are some links you may find helpful:

* [Documentation](http://facebook.github.io/react/docs/getting-started.html)
* [API Reference](http://facebook.github.io/react/docs/reference.html)
* [Blog](http://facebook.github.io/react/blog/)
* [React on GitHub](https://github.com/facebook/react)
* [Support](http://facebook.github.io/react/support.html)

Articles and guides from the community:

* [How is Facebook's React JavaScript library](http://www.quora.com/React-JS-Library/How-is-Facebooks-React-JavaScript-library)
* [React: Under the hood](http://www.quora.com/Pete-Hunt/Posts/React-Under-the-Hood)

Get help from other React users:

* [React on StackOverflow](http://stackoverflow.com/questions/tagged/reactjs)
* [Discussion Forum](https://discuss.reactjs.org/)

_If you have other helpful links to share, or find any of the links above no longer work, please [let us know](https://github.com/tastejs/todomvc/issues)._


## Running

The app is built with [JSX](http://facebook.github.io/react/docs/jsx-in-depth.html) and compiled at runtime for a lighter and more fun code reading experience. As stated in the link, JSX is not mandatory.

To run the app, spin up an HTTP server (e.g. `python -m SimpleHTTPServer`) and visit http://localhost/.../myexample/.
