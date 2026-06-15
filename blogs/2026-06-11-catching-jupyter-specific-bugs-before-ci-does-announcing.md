---
title: "Catching Jupyter-specific bugs before CI does: announcing jupyter eslint plugin"
url: "https://blog.jupyter.org/catching-jupyter-specific-bugs-before-ci-does-announcing-jupyter-eslint-plugin-fc65ae414630?source=rss----95916e268740---4"
date: "2026-06-11"
author: "Darshan Kr. Paudyal"
feed_url: "https://medium.com/feed/jupyter-blog"
---
We’re excited to announce the release of the first version of the Jupyter ESLint plugin @jupyter/eslint-plugin , now available on npm. It's a custom ESLint plugin designed specifically for the official Jupyter frontends (JupyterLab, Notebook, JupyterLite) and TypeScript extensions built around them. Motivation If you’ve ever written a JupyterLab extension, you’ve probably hit something like this: You wire up a new plugin, push a PR, walk away to make coffee, and 30 minutes later CI fails on a test you didn’t expect to be related.
