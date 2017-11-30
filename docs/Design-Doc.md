# The Design and Planning of The RedditCommunityBot

## Project Aims

This application is a Reddit bot that generates a list of frequently-asked questions for a particular subreddit. In high-level, it aggregates all posts within the subreddit that are questions, categorize them such that similar questions are grouped together, rank the question topics in order of frequency, and automatically generate an FAQ page that can be used on the subreddit to users' benefit.  

### Stretch Goals

- The bot can determine what the best answer to each FAQ is based on the highest-voted comments for each sample of the respective question, and populate this into the generated FAQ list for inclusion in the subreddit Wiki.

## Phases

### Phase 1 Objectives

- Bot is able to ingest posts from a particular subreddit, and determine what posts are questions and which are not.
- Bot trains itself on questions, and is able to categorize questions according to relevant topics.
- Aforementioned categorizations are verified by humans to be of sufficient accuracy.
- Bot summarizes the questions for each topic.
- Aforementioned summarizations for each topic are verified by humans to be of sufficient accuracy.
- Bot generates a list of summarized questions and outputs them in a common format for future use.
- Bot generates a usable FAQ list for the /r/learnmachinelearning subreddit.

### Phase 2 Objectives

- Bot is implemented with an infrastructure that supports regular retraining and regeneration of the FAQ list.
- Bot is used in service to a variety of subreddits to verify its capability to generalize. It is able to determine which posts are questions, and train itself on them to learn which are related, as described in Phase 1.
- Bot summarizes and generates a list of FAQs based on its findings for a variety of subreddits.
- Bot generates a usable FAQ list for a list of subreddits.

### Phase 3 Objectives

- At least one round of general user feedback has been collected and fixes implemented for satisfying the original project aims listed above. 
- Bot is released for general public consumption. 

## Design Considerations

There are a large number of resources at our disposal for tackling this project, and we are truly only limited by our own ambitions as far as what we can use and how far we can go. For example, we can dive into the Natural Language Processing of question posts by writing our algorithms from scratch (to bolster our familiarity with the tools that go into it and the challenges offered by NLP), or we can use a cloud-based service for this component of the bot (to simplify the development process for us as learners, letting us focus on other components of the bot that will serve our machine learning knowledge). Because this project has a stated goal of producing a working Reddit bot, conflicts in what options to follow will be solved by the classic engineer mantra: the solution that works wins. 

That being said, below are a few options of how we can approach this.
 
### Design Option 1: Python-based Tensorflow Text Processing

Proofs of concept:

- Link to paper/Github repository/etc.

..

### Design Option 2: Python-based Gluon Text Processing

Proofs of concept:

- Link to paper/Github repository/etc.

..

## References

- Original Reddit thread proposing the FAQ generator bot: https://www.reddit.com/r/learnmachinelearning/comments/77xjtw/lets_build_a_reddit_bot_together/

## Authors

- [@jgreenemi](https://github.com/jgreenemi), Joseph Greene
- 