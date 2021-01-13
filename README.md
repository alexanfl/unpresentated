# Unpresentated
Out of the box [reveal.js](https://revealjs.com) presentations using markdown.

## Installation
```bash
cd reveal.js && npm install
```

## Presentation setup
- Create a new directory for a category of presentations, or
use one of the current ones.
- `cp res/template.html <dirname>/<presname>.html` 
- Edit the html file. You only need to change the title and the reference
to the .md file. If your presentation is in a subfolder, you have to change
the relative links to the reveal.js library.
- `touch <dirname>/<presname>.md`
- `npm start`
- Open `localhost:8000/<dirname>/<presname>.html`.
