# StarCitizen Tracker

[![license](https://img.shields.io/github/license/TrumpTracker/trumptracker.github.io.svg?style=flat-square)](https://github.com/TrumpTracker/trumptracker.github.io/blob/master/LICENSE.md)[![RSS](https://img.shields.io/badge/RSS-v2.0-brightgreen.svg?style=flat-square)](https://luithollander.nl/trumptracker/rss.php)

StarCitzen Tracker is forked from TrumpTracker on github.

# Placeholder FAQ
### How is Confidence Accuracy calculated?
Each item is judged from 0-100% accurate based on the promise date and supporting links. 'Broken' and 'Completed' items are judged the most harshly, and should include at least 2 supporting links, as well as the original promise to recieve 100% confidency.

# Contributing

We'd love to get contributions from you! For a quick guide to getting your system setup for developing StarCitizen Tracker take a look at the setup above. Once you are up and running, check out the [contributing guide](.github/PULL_REQUEST_TEMPLATE.md) to see how to get your changes and pull requests merged in.

# To Do List
- [ ] Re-implement Comment section -- Reddit Integration?
- [ ] Sign up for bi-weekly e-mails?
- [ ] Update about page
- [ ] Find more active editors for data entry
- [x] Accuracy confidence percentage
- [x] Cleaner way to add and handle elements (not hardcode it...)
- [x] Fuzzy Search functionality
- [x] Database
- [x] Add Open Source Links and Credits on Footer
- [x] Clean up duplicates
- [x] Implement functionality to sort by broken, in progress, completed, etc. categories
- [x] Add tweet button

# Setup

Install [Jekyll](https://jekyllrb.com/) and Bundler:

    gem install jekyll bundler
    bundle install
    rake serve

Site is now running at [localhost:4000](http://localhost:4000)

# Tests

    rake test

# Report Issues
1. Pull request is best
