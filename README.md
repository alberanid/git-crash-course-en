# git-crash-course

Introduction to Git written for the RaspiBO makerspace.

## Italian version

Italian version available here: https://git.lattuga.net/alberanid/git-crash-course

## Build & run

Requirements: Python 3. Node.js, npm and a build step are not needed:
the bundled reveal.js files include ready-to-use JavaScript and CSS.

Run:

    $ ./run.sh

Open <http://127.0.0.1:8000> in your browser; press Ctrl+C to stop the server.
The script also works when launched from another directory.

To change the port: `PORT=8080 ./run.sh`. To make the server accessible
on the local network: `HOST=0.0.0.0 ./run.sh`.

The launcher serves the project files directly. To publish the slides on a
static web server, include the bundled reveal.js assets as well.

## Presentation

The bundled assets in `vendor/reveal.js/` come from
[reveal.js 6.0.2](https://github.com/hakimel/reveal.js/releases/tag/6.0.2)
(commit `75dff6f515d2d08df0c32cf2b7328b89425c6f25`). The Markdown,
syntax highlighting, zoom and notes plugins load from the compiled files in
`vendor/reveal.js/dist/`. No npm dependencies are needed.

Use the arrow keys to navigate; the URL preserves the current slide.
Click a diagram to enlarge it, or select it with Tab and press Enter.
Esc or the “Close” button closes the image. Ctrl/Cmd-click opens the image
in another tab. Image zoom uses a native HTML dialog and requires a modern
browser, without jQuery or Bootstrap.

On desktop, the file states slide places the text and diagram side by side;
on small screens, it uses a single column and allows long content to scroll.

## Otherwise...

Slides are in markdown format and can be [directly consulted](git-crash-course-en.md)

## License

Copyright 2017-2026 Davide Alberani <da@mimante.net>, RaspiBO <info@raspibo.org>

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License: http://creativecommons.org/licenses/by-sa/4.0/

This work includes reveal.js and other free software; see their own licenses.
