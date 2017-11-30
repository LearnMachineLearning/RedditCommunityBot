# RedditCommunityBot

A community-made Reddit bot by [/r/LearnMachineLearning](https://www.reddit.com/r/learnmachinelearning) to generate an FAQ based on a subreddit's history of posts. The original proposal and community vote is [viewable in this Reddit thread.](https://www.reddit.com/r/learnmachinelearning/comments/77xjtw/lets_build_a_reddit_bot_together/)

## Description

This is an in-progress open source development effort by the Reddit "/r/LearnMachineLearning" community. The general guideline and roadmap for how this application will be built is available at [RedditCommunityBot/docs/Design-Doc.md](https://github.com/LearnMachineLearning/RedditCommunityBot/tree/master/docs/Design-Doc.md). While this project is in development it will undergo many sweeping changes (including the contents of the Design-Doc), and is not intended for production use until further notice.

## Prerequisites

- Python 3.5.x

See the `requirements.txt` file for a full list of dependencies.

## Contributing & Setup

The recommended approach for contributing to this effort is to fork the repository with you Github account ([click here to fork this now](https://github.com/LearnMachineLearning/RedditCommunityBot/blob/docwriting/docs/Design-Doc.md#fork-destination-box)), and to develop on a feature branch (not on your `master` branch) in your forked version of the repository. When you are ready to introduce your contributions to the project, enter a [Pull Request](https://github.com/LearnMachineLearning/RedditCommunityBot/pulls) on the source repository for review and merging.

Keep in mind there are active members of the community to take your questions on the [/r/LML Discord server](https://discord.gg/G3rvFKF) in case you run into issues or have questions!

If you're unfamiliar with developing in a Github repository, the following is a recommended virtual environment setup.

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

Note that these are specific to a Python-based bot build, and will change if the community takes a different direction with the project design.