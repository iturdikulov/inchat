## InChat

Project status: WIP, alpha.

Self-hosted Twitch chat tracker, collects chat messages and do something with
them.

Initial PLANNED Features (priority matters):

- Token management with ncurses interface;
- Automatic chat messages collector, sort of subscriptions;
- Aviable to add multiple accounts for workers;
- Automatic channel information collector;
- Configurable automatic bot actions;

### Tech Stack

Backend:

- [Python](https://www.python.org/);
- [Pydantic](https://docs.pydantic.dev/latest/);
- [FastAPI](https://fastapi.tiangolo.com/);
- [RabbitMQ](https://www.rabbitmq.com/);
- [aio-pika](https://docs.aio-pika.com/).
- [PostgreSQL](https://www.postgresql.org/);
- [SQLModel](https://sqlmodel.tiangolo.com/);
- [pytest](https://docs.pytest.org/en/stable/)

Frontend:

- ncurses interface;

Devtools:

- [Nix flakes](https://nixos.wiki/wiki/Flakes)
- [uv2nix](https://github.com/pyproject-nix/uv2nix)
- [Ruff](https://docs.astral.sh/ruff/)
- [pre-commit](https://github.com/pre-commit/pre-commit)

## External links

- [IGDB.com](https://api-docs.igdb.com/)
- [Twitch Developers](https://dev.twitch.tv/docs/api/reference/)
- [pyTwitchAPI](https://github.com/Teekeks/pyTwitchAPI)
- [Introduction to the curses Library in Python: Text-Based Interfaces | Hyperskill Blog](https://web.archive.org/web/20240313205930/https://hyperskill.org/blog/post/introduction-to-the-curses-library-in-python-text-based-interfaces)
- [Curses Programming with Python — Python 3.13.1 documentation](https://docs.python.org/3/howto/curses.html)
