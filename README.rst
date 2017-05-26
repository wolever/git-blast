git-blast: show git branches sorted by last commit date
=======================================================

``git-blast`` (Brach LAST) shows git branches ordered by the date of the last commit::

    $ git blast
    * master 33 minutes ago
      some-feature 4 days ago [M]
      dev-branch 4 days ago
      legacy-branch 5 days ago [M]
      another-feature 4 months ago


Installation
============

With `Homebrew`__::

    $ brew install wolever/git-blast/git-blast

__ https://brew.sh/

Manually::

    $ curl https://raw.githubusercontent.com/wolever/git-blast/master/git-blast -O /usr/local/bin/git-blast
    $ chmod +x /usr/local/bin/git-blast
