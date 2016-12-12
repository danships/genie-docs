Roadmap
====================

This is the roadmap, building up the features in the genie eco-system, per version.

# 0.7

The first "real" release, across all genie repositories. Estimated readiness is the
first quarter of 2017.

## genie-ai

* Integrate [sonus](https://github.com/evancohen/sonus)
* Allow for stt via: Google STT
* Implement tts via espeak, Amazon Polly, Googl TTS

## genie-point

* Implement genie-ai module
* Expose socket interface

## genie-router

* Implement genie-point socket interface
* Fixed configurations

## [gladys](https://github.com/gladysproject/Gladys)

Make a module that implements the genie-router to receive commands and make speak in
a multi-room environment.

# 0.9

A follow-up release with new features. Estimated readiness at second quarter of 2017.

## genie-point

* http interface
* device detection via a technique such as [Bonjour](https://en.wikipedia.org/wiki/Bonjour_%28software%29)

## genie-cluster

* http interface
* automatically add and expose automatically detected genie-point devices

# 1.0

Tests and unit tests with full coverage. Estimated readiness second half of 2017.

# 1.1 and beyond

Will be specified in more detail as development of earlier versions progresses.

* extend genie-ai with a machine learning module to easily build a virtual assistent
* implement a virtual assistent that support a multi-room environment using genie.
* create an integration with [Mycroft](https://github.com/MycroftAI/mycroft-core)
