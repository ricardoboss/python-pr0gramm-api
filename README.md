# python-pr0gramm-api

[![Build Status](https://travis-ci.org/davidmann4/python-pr0gramm-api.svg)](https://travis-ci.org/davidmann4/python-pr0gramm-api)

This Python library allows you to search for images on the image board pr0gramm.com - it contains only high quality images so you basically have a pool of high end images. Usefull for automated scripts which generate content.

##example

```python
import pr0gramm
api = pr0gramm.Api()
api.enableSFW()
items = api.search("awww webm")
print api.info(item["id"])["tags"]
```
