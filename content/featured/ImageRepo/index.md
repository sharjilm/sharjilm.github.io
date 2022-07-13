---
date: '2'
title: 'Image Repository'
cover: './ImageRepo.png'
github: 'https://github.com/sharjilm/Image-Repository'
external: 'https://imagerepoweb.herokuapp.com/'
tech:
  - Python
  - HTML
  - CSS
  - AWS S3
  - Vision API
  - Tensorflow
  - Heroku
  - PostgreSQL
---

This image repository application can allow users to upload images, download, archive, and search for images that have been uploaded into the repo. Using object detection (cvlib by default and Google Vision API if the credentials are provided), the image will also have suggested tags attached to it that users can use to find the uploaded images. This application uses Heroku and AWS S3 for image hosting and scalability.
