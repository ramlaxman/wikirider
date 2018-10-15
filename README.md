# WikiRider
##
Do a Wikirun directly from your terminal (assuming you are using Linux or Mac) !

[![Build Status](https://travis-ci.org/sadboyzvone/wikirider.svg?branch=master)](https://travis-ci.org/sadboyzvone/wikirider)
[![Known Vulnerabilities](https://snyk.io/test/github/sadboyzvone/wikirider/badge.svg)](https://snyk.io/test/github/sadboyzvone/wikirider)
[![Code Climate](https://img.shields.io/codeclimate/coverage/github/sadboyzvone/wikirider.svg)](https://github.com/sadboyzvone/8080py)
## Install
Since I use Debian, I can only provide instructions for Debian-based distros.
```bash
# Clone the repo
git clone git@github.com:sadboyzvone/wikirider.git
# Install virtualenv
sudo pip install virtualenv
# Create a virtualenv
cd wikirider && virtualenv .
# Activate virtualenv
source bin/activate
# Install requirements
pip install -r requirements.txt
# Run
python main.py
```
## FAQ:
* What is a Wikirun?
	* [This](http://www.urbandictionary.com/define.php?term=Wikirun)
* Does it work on XYZ OS?
	* If you have Python on it, it probably will
