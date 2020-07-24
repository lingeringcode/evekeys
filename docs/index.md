## Overview

A set of functions that uses scikit-learn to conduct a TF-IDF analysis to isolate keywords from event-based documents. It answers the following questions:

1. What keywords represent a particular period of content?
2. What keywords represent a particular group of content from a particular period?

It assumes you have:

- imported your corpus as a pandas DataFrame,
- included metadata information, such as a list of dates and list of groups to reorganize your corpus, and
- pre-processed your documents.

It functions only with Python 3.x and is not backwards-compatible.

**Warning**: evekeys performs little to no custom error-handling, so make sure your inputs are formatted properly. If you have questions, please let me know via email.

## System requirements

* pandas
* sklearn
* tqdm

## Installation

```pip install evekeys```

## Known Issues or Limitations

- Please contact me if you discover any issues.

## Example notebooks

- Coming soon.