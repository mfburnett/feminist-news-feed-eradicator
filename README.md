Feminist News Feed Eradicator
====================

A browser extension that deletes your Facebook news feed
and replaces it with an empowering quote. Forked from the original News Feed Eradicator (jordwest).

![Screenshot](http://i.imgur.com/W7FJo8R.png?1)

Development
-----------

To get started, clone the repository and then run:

    make install
    BROWSER=chrome webpack

Project folder structure:

    src                             # Common code across all browsers
    browsers                        # Browser specific code
    assets                          # Images
    news-feed-eradicator.west.io    # Companion website

    # Build output:
    build                           # The raw extension contents for each browser
    dist                            # Distributable extension package for browsers
