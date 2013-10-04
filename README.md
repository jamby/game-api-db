# Game API DB creation

This is used as a rake task for my Play N' Vote app.

Basically, it goes through all of the platforms specified as `PLATFORMS` and will get all of the specified information (name game, release date, cover art, platforms, developers, and the Giant Bomb ID).

This is just the first iteration of this rake task.

To use it on your own, you must get an API key from the Giant Bomb website. Then replace the `API_KEY` with yours.
