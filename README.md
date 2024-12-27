# InChat

Project status is "Planning", updates are available in [TODO.md](TODO.md).

Self-hosted Twitch chat tracker, collects chat messages and do something with
them.

Initial PLANNED features (priority matters):

- Token management with ncurses interface.
- Automatic chat messages collector, sort of subscriptions.
- Aviable to add multiple accounts for workers.
- Automatic channel information collector.
- Configurable automatic bot actions.

## Requirements

Project tested on:

- [Python](https://www.python.org/) 3.12.
- [RabbitMQ](https://www.rabbitmq.com/) 4.0.
- [PostgreSQL](https://www.postgresql.org/) 16.
- [Node.js](https://nodejs.org/en) 23.
- [Docker](https://www.docker.com/) 27, (maybe later switch to Nix Flakes).

## External links

- [IGDB.com](https://api-docs.igdb.com/)
- [Twitch Developers](https://dev.twitch.tv/docs/api/reference/)
- [pyTwitchAPI](https://github.com/Teekeks/pyTwitchAPI)
- [Introduction to the curses Library in Python: Text-Based Interfaces | Hyperskill Blog](https://web.archive.org/web/20240313205930/https://hyperskill.org/blog/post/introduction-to-the-curses-library-in-python-text-based-interfaces)
- [Curses Programming with Python — Python 3.13.1 documentation](https://docs.python.org/3/howto/curses.html)
