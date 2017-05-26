git-blast: show git branches sorted by last commit date
=======================================================

``git-blast`` (Brach LAST) shows git commits ordered by the date of the last commit::

    $ git blast
    * master 33 minutes ago
      david 4 days ago [M]
      unholy-david-payments 4 days ago
      payments 5 days ago [M]
      david-old 4 months ago
      dbscan 5 months ago
      matrix-fun 5 months ago


Installation
============

With `Homebrew`__::

    $ brew install wolever/git-blast/git-blast

__ https://brew.sh/

Manually::

    $ curl https://raw.githubusercontent.com/wolever/git-blast/master/git-blast -O /usr/local/bin/git-blast
    $ chmod +x /usr/local/bin/git-blast
