.PHONY: build

build:
	docker run --rm -i -v $$(pwd):/tmp google/dart:2.8.4 bash -c "export PUB_HOSTED_URL=https://pub.flutter-io.cn && cd tmp/code && dart2native index.dart && mv index.exe bootstrap"
	chmod +x code/bootstrap