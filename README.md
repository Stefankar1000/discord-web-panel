# Discord Web Panel
### Administrative web panel for managing Discord servers

Sanic-oauth is broken (because of dependency version problems), this project doesn't currently run. Further work is required to rewrite/fix the entire backend. Feel free to contribute to the project. Please don't open issues about sanic-oauth not working.

![Widescreen panel screenshot](https://i.imgur.com/VfDkc4Q.png "Widescreen panel")
![Smallscreen panel screenshot](https://i.imgur.com/owRsdDm.png "Smallscreen panel")

# Running
- Make sure you've installed all the required python packages: `python -m pip install -r requirements.txt --upgrade --user`
- Rename `_config.json` to `config.json`
- Create an appliation at the [discord developer portal](https://discordapp.com/developers/applications/) and copy your client id and secret into the config.
- Add a bot to your application and copy its token into the config.
- Run the webserver: `python app.py`
