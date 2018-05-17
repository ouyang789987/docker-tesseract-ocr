# [Tesseract OCR](https://github.com/tesseract-ocr/tesseract).

Tesseract OCR 4 running on Ubuntu.

## Tags

Versions indicates ubuntu version, not tesseract version. All versions uses tesseract 4.

* `latest`, `18.04`
* `16.04`

## Example run

```bash
docker pull jitesoft/tesseract-ocr
docker run -v /path/to/image/:/tmp jitesoft/tesseract-ocr /tmp/img.jpg stdout
```

Use high DPI image for best result. Higher DPI does increase the time to run though.
