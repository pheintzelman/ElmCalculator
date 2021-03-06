[<img src="/docs/screenshot.png" align="right" alt="Elm Calculator Demo" width="200px">](https://pheintzelman.github.io/elm-calculator/)
# elm-calculator
A calculator written in elm. Feel free to use this as a jumping off point for your own elm experiments.

I created this project to give elm a try. I am currently working on a blog post of the experience. Will add link soon.

[See demo here](https://pheintzelman.github.io/elm-calculator/) 

### Install:
Clone this repo into a new project folder, e.g. `elm-calculator`, and install its dependencies:
```
git clone https://github.com/pheintzelman/elm-calculator.git elm-calculator
cd elm-calculator
npm install
```

Re-initialize the project folder as your own repo:
```
rm -rf .git
git init
git add .
git commit -m 'first commit'
```

If you haven't done so yet, install Elm globally:
```
npm install -g elm
```

Install Elm's dependencies:
```
elm package install
```

### Serve locally:
```
npm start
```
* Access app at `http://localhost:8080/`
* Get coding! The entry point file is `src/elm/Main.elm`
* Browser will refresh automatically on any file changes..


### Build & bundle for prod:
```
npm run build
```

* Files are saved into the `/dist` folder
* To view it, open `dist/index.html`

### Thanks

I want to thank the people who made this [great starter project](https://github.com/moarwick/elm-webpack-starter) and various bloggers from around the web.

### Changelog

**Ver 0.2.1** 
* Added operation chaining
* Fixed bug with pressing operation at start
* Fixed bug with pressing equal at start
* Add V1 underdocs which excludes these fixes

**Ver 0.1.1** 
* Added demo

**Ver 0.1.0** 
* Added calculator functions - Add, Minus, Devide, Mutiple, Equals, Decimal, Numeric Input, Display
* Added scss styling for calculator, buttons, display
* cloned https://github.com/moarwick/elm-webpack-starter my-elm-project
