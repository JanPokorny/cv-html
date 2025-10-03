<h1 align="center">cv.html</h1>

<h3 align="center">Beautiful, flexible and easy to edit CV template</h3>

I made this for my friends who I couldn't bear seeing struggle with LaTeX. `cv.html` is written in HTML, and all you need is a text editor and a web browser to make it your own.

## How to use

1. [Download the repository as ZIP](https://github.com/liantze/AltaCV/archive/refs/heads/main.zip) and extract `cv.html` and `cv.css` to a folder.
2. Save your photo as `cv.jpg` in the same folder.
    - Crop the photo to a square and lower the resolution to avoid the PDF being too large.
    - If you don't want a photo, remove the `<picture>...</picture>` block and set `--photo-size: 0;` in the `<style>` block in `cv.html`.
3. Open `cv.html` in a text editor or IDE. (If you don't have one, install [Sublime Text](https://www.sublimetext.com/) which is easy to use.)
4. Edit the text in `cv.html` to replace Karel's information with yours. It uses standard HTML syntax with some custom elements (prefixed `cv-`). The strucutre is quite flexible, you can infer the meaning of each tag from context.
    - Do not forget to change the `<title>`.
    - You can customize some basic styling in the `<style>` block near the top -- colors (use a [color picker](https://google.com/search?q=color+picker) to get the hex codes), sizes, margins, column rations.
    - The used icon pack is Boxicons, [you can find tags for more icons here](https://boxicons.com/icons/phone?s=regular&w=normal&p=basic&free=true).
    - For more advanced styling, edit `cv.css` directly.
5. Open `cv.html` in a web browser to preview your CV.
6. Once you're satisfied, print to PDF from the browser: press `Ctrl+P` (or `Cmd+P` on macOS), and choose "Save as PDF" as the printer.
    - Use a Chrome-based browser (Google Chrome, Microsoft Edge, Brave, etc.) for best results, since it supports directly printing to PDF. Firefox offers only system-wide PDF printing (e.g. Microsoft Print to PDF), which does not preserve hypertext links in the output PDF.
    - If the print preview does not look right, set print margins to "None" and enable "Background graphics" in the print settings.

<h2>Limitations <small>(PRs welcome!)</small></h2>

- Single-page only at the moment
- Not all features of AltaCV are implemented yet

## Acknowledgements

Based on the design of [AltaCV](https://es.overleaf.com/latex/templates/altacv-template/trgqjpwnmtgv), which in turn was inspired by [one of the Enhancv templates](https://enhancv.com/resume-examples/famous/marissa-mayer/). Thanks to Karel Sedláček for permitting me to use his CV as the example.
