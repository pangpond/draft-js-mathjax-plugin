# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

# 1.3.5 - 2019-02-10
- forked from original https://github.com/efloti/draft-js-mathjax-plugin
- PAR-1228 added getProps to store in initialize handler of plugin
- PAR-1228 changes to InlineTex and TexBlock so that if the parent Editor is `readOnly` then do nothing when attempting to edit a MathJax block
- PAR-1228 update default external MathJax script to 2.7.5


# 1.3.4 - 2017-05-09
- update to support draft-js-0.10.1
- partially fix a DOMException (Failed to execute 'extend' on 'Selection') raise
  when a rendered math element is clicked
## 1.3.x - 2017-04-19
- improve plugin config: mathjax source (script), mathjax options (options), completion.
## 1.2.x - 2017-04-15
- add auto completion
## 1.1.x - 2017-04-13
- add the ability to config mathjax macro,
- avoid flickering of the preview,
- escape the `$` character to insert it.
## 1.0.0 - 2017-04-10
### Released the first working version of DraftJS MathJax Plugin