# yh-antagning.se


## Development setup

1. [Install kit](https://github.com/learnpoint/kit).

2. Clone this repo (or create a fork).

3. In the repo (or your fork), start the dev server with the default port (4444):

        kit dev

     ... or start the dev server on a custom port:

        kit dev -p [port]

4. Open the site at `http://localhost:4444` (or the custom port).

5. Write all your changes to the `src` folder. You should never make any changes to the `docs` folder.

6. If there are any file mismatches, or build problems, it's perfectly safe to:
    1. Stop the dev server: `Ctrl + C`.
    2. Completely delete the ```docs``` folder.
    3. Restart the dev server: `kit dev`. This command will rebuild the `docs` folder.

7. When done, stop the server:

        Ctrl + C


## How to: Edit the hero image

1. Edit the file `hero.html`. Tool for creating arrows: https://www.fffuel.co/pppointed/.
2. Open `/hero.html` in a browser.
3. Take a screenshot.
4. Save the screenshot as `/src/images/hero.png`.
5. Verify that the image margins look good on `/index.html`.


## How to: Edit the of terms of service page

1. Edit `terms-of-service/index.html`.

2. When done, create a new folder inside `terms-of-service/history`. The name of the folder should represent the date for when the new terms are in effect, for example `2026-12-12`.

3. In the created folder, create a new file named `index.html`. Edit the file:

    a. Copy the content of `terms-of-service/index.html` to the new file.

    b. Add a preamble that indicates the version date.

    c. Add a back link to history at the top.

    d. Remove the link to previous version at the bottom. 

4. Update the history index page `terms-of-service/history/index.html` to reflect the changes.
