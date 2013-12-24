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
