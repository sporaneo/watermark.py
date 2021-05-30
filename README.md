# watermark.py

![PyPI](https://img.shields.io/pypi/v/watermark.py)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/watermark.py)

A convenient python wrapper around FFmpeg to apply watermarks to images, gifs,
and videos.

## Installation

```shell
pip install watermark.py
```

You need to install  [`ffmpeg`](https://ffmpeg.org/) seperately.

## Usage

<!-- ### GUI

Visit watermark.py.aahnik.dev to experience the web app.

### CLI

You can use the command-line interface to easily apply watermark.

```shell
watermark --help
``` -->

<!-- ### Python -->

```python
from watermark import File, Watermark, apply_watermark

video = File("vid.mp4")
watermark = Watermark("im.png")

apply_watermark(video, watermark)
```

<!-- ## Used by

- tgcf
- telewater -->