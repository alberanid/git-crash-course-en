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

## Ortherwise...

Slides are in markdown format and can be [directly consulted](git-crash-course-en.md)

## Licence

Copyright 2017-2026 Davide Alberani <da@mimante.net>, RaspiBO <info@raspibo.org>

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License: http://creativecommons.org/licenses/by-sa/4.0/

This work include the revealjs dependency, jQuery and possibly other free software; see their own licenses.
