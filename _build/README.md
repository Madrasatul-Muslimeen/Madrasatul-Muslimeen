# How this copy was made (Web project)

Free static copy of madrasatulmuslimeen.org (WordPress), address https://madrasatul-muslimeen.github.io/Madrasatul-Muslimeen/. Hidden from search (noindex, canonical = the real site) until the name is moved here.

`smallsite.sh` mirrors the site; then `HIDDEN=1 python3 -I wpstatic.py mirror OUT madrasatulmuslimeen.org https://madrasatul-muslimeen.github.io/Madrasatul-Muslimeen/ posts.json pages.json` (on move day drop HIDDEN=1 and use https://madrasatulmuslimeen.org/ as the address). Check with linkcheck.py and shoot.js.
