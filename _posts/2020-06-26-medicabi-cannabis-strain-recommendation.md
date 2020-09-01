---
layout: post
title: Recommending cannabis strains using natural language processing
subtitle: Working with a team of 3 data scientists, we built an api serve up strain recommendations to a webdev team
bigimg: /img/cluster_map.jpeg
gh-repo: BuildWeek-Med-Cabinet-4/DS
gh-badge: [star, fork, follow]
tags: [NLP, API, Cannabis, Data Science]
comments: true
---

Working on a team of three, [Jen](https://github.com/JenBanks8585), [Jon](https://github.com/jae-finger) and myself created a simple api for our cannabis strain recommendation machine. The strain recommendation model uses NLP techniques including: term frequency document frequency(tfidf) vectorizing, consine similarity, and k-nearest neighbors. We built our api using flask to accept POST requests with JSON object containing user input, and return a JSON object with strain recommended by our recommender. [api can be found here](https://medicabi.herokuapp.com/), and [the web teams final product here](https://bwmedcabinet4.netlify.app/).
