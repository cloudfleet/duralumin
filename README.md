Duralumin
=========
*Every Zeppelin's look and feel is defined by its awesome duralumin*

Cloudfleet's UI.

Design guidelines
-----------------
Victorian, with grace.

[satadev](http://www.satadev.com/about/) - crispy, with an occasional hint of
hand-drawn trinketry.

[Valve's handbook](http://media.steampowered.com/apps/valve/Valve_Handbook_LowRes.pdf)
- some nice hand-pressed goodness.

[Franz Ferdinand - Eleanor Put Your Boots On, video](http://www.youtube.com/watch?v=mdQHdSfSRKw)
- parallax, cardboard-collage show of semi-transparent
clouds, kites and airships

Setup
-----
Assuming you have Node.js and RubyGems, first install the "global" tools.

    npm install -g yo generator-webapp
    gem install compass

Then install the local tools.

    npm install
    bower install

Run the development server.

    grunt serve

When you're happy, commit the changes in the dist/ folder.

    grunt publish

Adding new dependencies
-----------------------

New JS or SASS/CSS packages can be added easily
using [bower](http://bower.io/).

    bower install --save <package>

The only diff should now be seen in `bower.json` and the
files get installed under the .gitignored `app/bower_components/`.

To automatically link the package run

    grunt bower-install

but check this to make sure that it was done right and that any
templates have been updated accordingly. If necessary set the path(s)
manually.
