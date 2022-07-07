  <b>Simple bot for twitter.</b><br>
  <sub>
    Coded with 💙 by Parth
  </sub>
  <br>

  
Description 🔦 
--------

Simple twitter bot that can like and retweet your tweets, or search tweets with a specified topic. It stores and serves data with a Flask webapp. 🐦

Installation 📡
-------

- `git clone https://github.com/hack-parthsharma/Twitter-Bot`
- `cd twitterbot2`
- `pip install -r requirements.txt`
- Edit the `config.yaml` and `globals.py` files 
- `python init_db.py`
- `python twitterbot2.py -h`

Usage 🚀
-------

```
usage: twitterbot2.py [-h] [-v] [-t] [-k KEYWORD] [-nu] [-nl] [-nr] [-s STATS] [-oc OUTPUT_CSV] [-oj OUTPUT_JSON] [-oh OUTPUT_HTML]

Twitterbot v2

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         Show the version of this program.
  -t, --timeline        Search for tweets in the bot and user's timeline.
  -k KEYWORD, --keyword KEYWORD
                        Search for tweets with defined keyword(s). If more than one, comma separated enclosed in double quotes.
  -nu, --no-user        Don't like and retweet user tweets.
  -nl, --no-like        Don't like tweets, just retweet.
  -nr, --no-retweet     Don't retweet tweets, just like.
  -s STATS, --stats STATS
                        Show the statistics of the inputted bot (username).
  -oc OUTPUT_CSV, --output-csv OUTPUT_CSV
                        Produce a csv file containing the stats for the inputted used (ALL for anyone).
  -oj OUTPUT_JSON, --output-json OUTPUT_JSON
                        Produce a json file containing the stats for the inputted used (ALL for anyone).
  -oh OUTPUT_HTML, --output-html OUTPUT_HTML
                        Produce a html file containing the stats for the inputted used (ALL for anyone).
```


Useful notes/links 🔗
--------

- [Getting access to the Twitter api](https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api)
- [Twitter api rate limits](https://developer.twitter.com/en/docs/twitter-api/v1/rate-limits)
- This app uses a Flask webserver (port 5000). Expose it on public Internet at your own risk (I use it behind NAT/firewall).
