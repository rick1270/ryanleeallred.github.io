---
layout: post
title:  Reproducibility
category: R
---

Reproducibility is the construction of an environment or a piece of code so that things can be reconstructed the same way across many devices, byte for byte when possible.

This is especially important in production code and model deployment, where simply hacking together a model is not sufficient.

Use things like [docker](https://www.docker.com/) to build 'containers', or essentially deployable labs, in order to ensure proper conditions.
