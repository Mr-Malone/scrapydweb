ScrapydWeb: Full-featured web UI for Scrapyd cluster management, Scrapy log analysis & visualization
==========================

[![PyPI - scrapydweb Version](https://img.shields.io/pypi/v/scrapydweb.svg)](https://pypi.org/project/scrapydweb/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/scrapydweb.svg)](https://pypi.org/project/scrapydweb/)
[![Coverage Status](https://coveralls.io/repos/github/my8100/scrapydweb/badge.svg?branch=master)](https://coveralls.io/github/my8100/scrapydweb?branch=master)
[![GitHub license](https://img.shields.io/github/license/my8100/scrapydweb.svg)](https://github.com/my8100/scrapydweb/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/my8100/scrapydweb.svg?style=social)](https://twitter.com/intent/tweet?text=ScrapydWeb:%20Full-featured%20web%20UI%20for%20Scrapyd%20cluster%20management,%20Scrapy%20log%20analysis%20%26%20visualization%20%23python%20%20%23scrapy%20%23scrapyd%20%23webscraping%20%23scrapydweb%20@my8100_%20&url=https%3A%2F%2Fgithub.com%2Fmy8100%2Fscrapydweb)

Features
---------------

- Scrapyd Cluster Management
  - Group, filter and select any numbers of nodes
  - Execute command on multinodes with one click

- Scrapy Log Analysis
  - Stats collection
  - Progress visualization
  - Logs categorization

- All Scrapyd API Supported
  - Deploy project, Run Spider, Stop job
  - List projects/versions/spiders/running_jobs
  - Delete version/project

- Others
  - Basic auth for web UI
  - Accessing Scrapyd servers protected by basic auth


Maintainer
---------------
- [my8100](https://github.com/my8100)
- [simplety](https://github.com/simplety) (Front-End)


Installation
------------

To install ScrapydWeb, simply use pip:

```
pip install scrapydweb
```


Start Up
------------

1. Run `scrapydweb -h` to get help,
and a config file named **scrapydweb_settings.py** would be copied to the working directory,
then you can custom config with it.
2. Run `scrapydweb`
3. Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) **(It's recommended to use Google Chrome to get better experience.)**


Screenshot
------------

- Overview
![overview](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/overview.png)

- Dashboard
![dashboard](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/dashboard.png)

- Log Analysis
  - Stats collection
![log_stats](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/log_stats.png)

  - Progress visualization
![log_chart](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/log_chart.png)

  - Logs categorization
![log_extracted](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/log_extracted.png)

- Deploy a Project
![deploy](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/deploy.png)

- Run a Spider
![run](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/run.png)

- Manage Projects
![manage](https://raw.githubusercontent.com/my8100/scrapydweb/master/screenshot/manage.png)
