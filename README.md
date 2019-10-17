### This tool is based on LinkFinder https://github.com/GerbenJavado/LinkFinder you can read more about this tool here

# About sentrySSRF

Written in python, try to find sentry config on page or in sentry files by using regular expressions from LinkFinder and then check for blind SSRF in sentry.

## Screenshots

![sentrySSRF](https://sun9-9.userapi.com/c858336/v858336741/abd7f/0hRTywTmYKc.jpg "sentrySSRF")

## Installation

sentrySSRF As LinkFinder supports **Python 3**.

```
$ git clone https://github.com/xawdxawdx/sentrySSRF.git
$ cd sentrySSRF
$ python setup.py install
```

## Dependencies

sentrySSRF depends on the `argparse` and `jsbeautifier` Python modules. These dependencies can all be installed using [pip](https://pypi.python.org/pypi/pip).

```
$ pip3 install -r requirements.txt
```

### Usage and Examples

* Exact js url:

`python3 sentrySSRF.py -i https://example.com/1.js`

* Input a domain to recursively parse all javascript located in a page to find config with sentry:

`python3 sentrySSRF.py -i https://example.com/ -d`



## Final remarks
- Thanks to GerbenJavado
# sentrySSRF
