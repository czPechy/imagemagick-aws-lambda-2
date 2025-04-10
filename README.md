# ImageMagick for AWS Lambda

## Versions

* imagemagick: 7.1.1-47
* nodejs: 20
* libpng: 1.6.40
* libtiff: 4.7.0
* libjpeg: 9f
* openjpeg2: 2.5.3
* libwebp: 1.5.0

## Compiling the code

* `docker pull public.ecr.aws/lambda/nodejs:20`
* `docker tag public.ecr.aws/lambda/nodejs lambda/nodejs:20`
* `make build/layer.zip`

## Author

Gojko Adzic <https://gojko.net>

## License

* These scripts: [MIT](https://opensource.org/licenses/MIT)
* ImageMagick: https://imagemagick.org/script/license.php
* Contained libraries all have separate licenses, check the respective web sites for more information
