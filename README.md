# The Yandex Decoder Ring

In January of 2023, Russian search engine Yandex had fragments of its codebase leaked into the public domain. This was an unprecedented move. The public has never had access to large swaths code from a major search engine. 

For the Search Engine Optimization (SEO) community, this is especially compelling because we are an industry that manipulates websites as inputs to impact how pages might rank in search engines. For the first time we're getting a clear view of different ranking factors and how they are analyzed and weighted by search algorithms. 

**This repository is the output of such a deep dive analysis of the code.**

A few technically adept members of the SEO community, namely Ben Wills, Mike King, and Ryan Jones have spent their time to review the code in attempts to make sense of it. The initial result of that was Mike's SearchEngineLand article [Yandex scrapes Google and other SEO learnings from the source code leak](https://searchengineland.com/yandex-leak-learnings-392393). However, we quickly realized we were only scratching the surface with that analysis and wanted to continue to understand the code.

In the Decoder Ring, we've broken down the code by its function as it relates to Information Retrieval components (crawling, processing, indexing, ranking, etc) and the structure of the codebase (search, extsearch, kernel, etc.). The documentation herein represents our understanding of the code and what it is doing.

This repository highlights snippets of code from the codebase as examples of what we've identified, but we do not include the entirety of the codebase here. You can fire up your favorite torrent client and find that pretty easily. 

## How to Use this Project

This project is solely documentaiton of our findings. We understand that there are missing pieces to the codebase, and we will continue to refine the docs as we learn more. What we've shared here is solely for educational purposes and to encourage a stronger understand of how information retrieval, natural language processing, and neural networks operate for web search engines.

## Contributions
Getting involved is quite simple. If you'd like to contribute, you can simply submit a pull request. If you'd like to join the discussions about the project, come join our Slack community, The Index. We've got an on-going conversation where we discuss what we've found and how to get things in the code to work.

