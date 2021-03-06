# jigr (Jigsaw Web Manager)
Play the game: https://ioanabirsan.github.io/jigr/

**`project, infoiasi, cliw, web`**

### Project Documentation
* Technical Report: https://htmlpreview.github.io/?https://github.com/ioanabirsan/jigr/blob/master/docs/technical-report.html
* User Guide: https://htmlpreview.github.io/?https://github.com/ioanabirsan/jigr/blob/master/docs/user-guide.html
* Demo Video: https://youtu.be/PcytPEx8Z3U
### Development workflow
0. The first time you should clone the project locally. This step should be skipped in future iterations.
1. Checkout to master and pull the latest version from github locally before adding any other code. **This should be done each time you want to make changes starting from the latest master changes:** 
    1. `git branch` -> current branch
    2. `git checkout branch-name` -> move to branch `branch-name`
2. Checkout to a new branch with a name that describes the feature, following the standard **name/feature**: `git checkout -b andrei/add-animations`.
3. Make your desired changes to the code and make commits with those changes: `git commit -m "message that describes commit"`.
4. Push the changes to GitHub to a branch with the same name: `git push -u origin local-branch-name:desired-branch-name-on-github` (e.g., `git push -u origin andrei/add-animations:andrei/add-animations`).
5. Validate that the changes work as expected.
6. If your changes work as expected merge the new branch to the **master** branch. **Merge only if the changes work as expected**. This can be done from the GitHub UI.

Idei:
- snap dupa procent suprafata - epsilon / centru (greutate - epsilon) si (unghi - epsilon)
- afisare aleatoriu piese pe ecran dupa 2 criterii: locatie si unghi
- slider dificultate: influenteaza epsilon
- web sochets pt transmitere de informatie colaborativa (multiplayer)
- ? stocare stare joc local / pe server
- ? de utilizat canvas pentru rotatie (biblioteci)
- ? fragmentare puzzle per sesiune sau static (de preferat static)
- endpoint-uri:
  - /puzzles/id (GET) 
  - /puzzles (GET -> all puzzles)
  - /puzzles?search=term (GET -> all puzzles for witch the term matches)
  - /puzzles (POST : url sau imagine propriu zisa si intoarce id-ul puzzle-ului generat)
 
 Resources:
- https://developer.mozilla.org/kab/docs/Web/API/Canvas_API
- https://developer.mozilla.org/en-US/docs/Web
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- https://stackoverflow.com/
- https://iampava.com/cliw/
- https://profs.info.uaic.ro/~busaco/teach/courses/cliw/
- http://www.raymondhill.net/puzzle-rhill/jigsawpuzzle-rhill.php
- https://shout.setfive.com/2015/04/23/javascript-building-a-html5-canvas-puzzle/
- http://www.custarddoughnuts.co.uk/jigsaw
- https://coursesweb.net/javascript/image-puzzle-game-script
- http://www.netzgesta.de/snapfit/
- http://gavmac.github.io/jigsaw/
- https://codepen.io/dearsaif/pen/mOjbLK
- https://github.com/mlcheng/js-toast
