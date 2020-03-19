# CLEF2020-CheckThat! Task 2

This repository contains the _dataset_ for the [CLEF2020-CheckThat! task 1](https://sites.google.com/view/clef2020-checkthat/tasks/tasks-1-5-check-worthiness?authuser=0).

It also contains the _format checker, scorer and baselines_ for the task.

````
FCPD corpus for the CLEF-2020 LAB on "Automatic Identification and Verification of Claims"
Version 1.0: March ?, 2020 (Data and Baseline Release)
````

This file contains the basic information regarding the CLEF2020-CheckThat! Task 1
on evidence retrieval estimation dataset provided for the CLEF2020-CheckThat! Lab
on "Automatic Identification and Verification of Claims".
The current version (1.0, March ?, 2020) corresponds to the release of a
part of the training data set.
The test set will be provided in future versions.
All changes and updates on these data sets and tools are reported in Section 1 of this document.

__Table of contents:__

- [CLEF2020-CheckThat! Task 2](#clef2020-checkthat-task-2)
  - [Evaluation Results](#evaluation-results)
  - [List of Versions](#list-of-versions)
  - [Contents of the Distribution v1.0](#contents-of-the-distribution-v10)
  - [Data Format](#data-format)
  - [__Results File Format__](#results-file-format)
  - [Format checkers](#format-checkers)
  - [Scorers](#scorers)
    - [Evaluation metrics](#evaluation-metrics)
  - [Baseline](#baseline)
  - [Licensing](#licensing)
  - [Credits](#credits)

## Evaluation Results

TBA

## List of Versions

* __v1.0 [2020/03/?]__ - Training data. The training data for task 1 contains (?) Tweets.

## Contents of the Distribution v1.0

We provide the following files:

* Main folder: [data](data)
  * [training.tsv](data/training.tsv) <br/>
  Contains all the tweets with claim worthiness labels.
  * [README.md](README.md) <br/>
    this file


## Data Format

#TODO: We need to mention hwo we anntated the tweets. SO maybe we have.a summary n the instruction doc added here or in another section.

The datasets are text files with the information TAB separated. The text encoding is UTF-8. You will get:

> tweet_id <TAB> tweet_url <TAB> tweet_text <TAB> claim <TAB> claim_worthiness

Where: <br>
* tweet_id: Tweet ID for a given tweets given by Twitter <br/>
* tweet_url: URL to the given tweet <br/>
* tweet_text: Text of the tweet <br/>
* claim: 1 if the tweet is a claim; 0 otherwise. <br/>
* claim_worthiness: 1 if the tweet is worth fact checking; 0 otherwise. <br/>

Example:
#TODO

## __Results File Format__:

#TODO

## Format checkers

TBA

## Scorers

TBA

### Evaluation metrics

#TODO

## Baseline

TBA

## Licensing

  These datasets are free for general research use.

## Credits

Task 1 Organizers:

* Alex <br/>

* Firoj, Qatar Computing Research Institute, HBKU <br/>

* Shaden Shaar, Qatar Computing Research Institute, HBKU <br/>

* Giovanni Da San Martino, Qatar Computing Research Institute, HBKU <br/>

* Preslav Nakov, Qatar Computing Research Institute, HBKU <br/>

Task website: https://sites.google.com/view/clef2020-checkthat/tasks/tasks-1-5-check-worthiness?authuser=0

Contact:   clef-factcheck@googlegroups.com

