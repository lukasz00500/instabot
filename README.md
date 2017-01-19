# instabot
Cool instagram scripts and API wrapper. Written in Python.

As you may know, Instagram closed it's API in summer 2016. This Python module can do the same thing without any effort. 

If you have any ideas, please, leave them in [issues section](https://github.com/ohld/instabot/issues).

*Your Contribution and Support through Stars will be highly appreciated.*

## How to install
```
pip install -U instabot
```

## How to run
Choose any example from [examples](https://github.com/ohld/instabot/tree/master/examples) and run
```
python example.py
```

## Implemented methods

### API

* login / logout
* like / unlike
* follow / unfollow
* comment

### API info getters

* get_profile_info
* get_following
* get_user_id_by_username

## Examples

### Bot

* subscribe_to_following.py

subscribes to person's following

* unsubscribe_not_mutually_followers.py

unsubscribes from persons that are not follow you

### Statistics

* save_my_stats.py

Saves every hour to track your growth

* save_my_following.py

Saves your followings list into *.tsv format

*More information you can find in examples folder.*
___
_inspired by @mgp25 and @LevPasha_
