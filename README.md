<div align="center">

# Web Programming 2025

Lab exercises, mini-projects and assessments from **Web Programming** at VIT Vellore (2025),
taught by Prof. Anthoniraj Amalanathan.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![License](https://img.shields.io/badge/License-GPL--3.0-blue)

</div>

## Table of contents

- [What is inside](#what-is-inside)
- [How to run the examples](#how-to-run-the-examples)
- [Learning path](#learning-path)
- [Project structure](#project-structure)
- [License](#license)

## What is inside

| Folder          | Topics |
| --------------- | ------ |
| `web_design/`   | HTML basics, block vs inline, all five CSS positioning modes, z-index, character entities, Flexbox, media queries, two resume pages |
| `javascript/`   | Linking JS to HTML, forms, a datalist, ES6 features and `localStorage` |
| `es6_practice/` | Event listeners, a digital clock and ES6 module-style exercises |
| `js_modules/`   | ES module imports and exports |
| `react/`        | React without a build step: components, state, events, a counter, calculators and a to-do list |
| `webservice/`   | A small Python API and a page that calls it (`setup_api.md` explains the setup) |
| `assessment/`   | Graded tasks: calculator, to-do list and word counter |
| `review/`       | Short revision snippets on selectors, centring and timers |

## How to run the examples

Almost every example is a standalone HTML file, so you only need a browser. For the ones
using JavaScript modules, serve the folder over HTTP:

```bash
git clone https://github.com/gitswagata1/WebProgramming2025.git
cd WebProgramming2025
python -m http.server 8000      # then open http://localhost:8000
```

The React examples load React and Babel from a CDN, so they need an internet connection.

### Web service example

```bash
cd webservice
pip install flask flask-cors      # see setup_api.md for the exact steps
python app.py
```

## Learning path

1. **Foundations:** `web_design/01` to `03`, then `review/`
2. **Layout:** positioning (`04` to `09`), Flexbox (`12` and `13`) and media queries (`14`)
3. **JavaScript:** `javascript/` then `es6_practice/` and `js_modules/`
4. **React:** `react/basics.html` through `react/todo.html`
5. **Full flow:** `webservice/` and `assessment/`

## Project structure

```
WebProgramming2025/
├── web_design/       HTML and CSS lessons, numbered in order
├── javascript/       Core JavaScript
├── es6_practice/     ES6 exercises
├── js_modules/       Module examples
├── react/            React lessons
├── webservice/       Python API demo
├── assessment/       Graded tasks
├── review/           Revision snippets
├── images/ fonts/    Shared assets
└── LICENSE
```

## License

Released under the [GPL-3.0 License](LICENSE).

---

Built by **Swagata Banerjee** · B.Tech CSE, VIT Vellore · [GitHub](https://github.com/gitswagata1)
