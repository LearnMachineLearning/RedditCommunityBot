# RedditCommunityBot

A community-made Reddit bot by [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning) to generate an FAQ based on a subreddit's history of posts. The original proposal and community vote is [viewable in this Reddit thread.](https://www.reddit.com/r/learnmachinelearning/comments/77xjtw/lets_build_a_reddit_bot_together/)

## Description

This is an in-progress open source development effort by the Reddit "/r/LearnMachineLearning" community. The general guideline and roadmap for how this application will be built is available at [RedditCommunityBot/docs/Design-Doc.md](https://github.com/LearnMachineLearning/RedditCommunityBot/tree/master/docs/Design-Doc.md). While this project is in development it will undergo many sweeping changes (including the contents of the Design-Doc), and is not intended for production use until further notice.

## Prerequisites

- Python 3.5.x

See the `requirements.txt` file for a full list of dependencies.

## Setup

Linux / UNIX:

```bash
$ virtualenv -p python3 env
$ source env/bin/activate
(env) $ pip install -r requirements.txt
$ python --version
Python 3.5.2
```

Windows:

```bash
> virtualenv -p python3.exe env
> env\Scripts\Activate
(env) > pip install -r requirements.txt
> python --version
Python 3.5.2
```

