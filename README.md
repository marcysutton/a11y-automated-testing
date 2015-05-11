#30 Minutes or Less: The Magic of Automated Accessibility Testing
[http://marcysutton.github.io/a11y-automated-testing/](http://marcysutton.github.io/a11y-automated-testing/)

By [Marcy Sutton](http://marcysutton.com)<br>
Developer at [Substantial](http://substantial.com), Angular core team member<br>
twitter: [@marcysutton](http://twitter.com/marcysutton)

##Presenting at:
* Seattle Software Craftsmanship Meetup
* JSConf US 2015

## Installation

Should you want to run this presentation from source for some reason, the **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Building from source locally
Some reveal.js features require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

1. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

1. Clone the reveal.js repository
```
$ git clone git@github.com:hakimel/reveal.js.git
```

1. Navigate to the reveal.js folder
```
$ cd reveal.js
```

1. Optional global dependencies (for my live demos)
```
$ sudo npm install -g a11y
```

1. Install local dependencies
```
$ npm install
```

1. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

1. <http://localhost:8000> opens dynamically

You can change the port by using `grunt serve --port 8001`.
