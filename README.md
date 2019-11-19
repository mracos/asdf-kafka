# asdf-kafka

[![Travis](https://img.shields.io/travis/skotchpine/asdf-kafka/master.svg?style=flat-square)](https://travis-ci.org/skotchpine/asdf-kafka)

## Install

```
asdf plugin-add kafka https://github.com/skotchpine/asdf-kafka.git
```

## Usage

Check [asdf readme](https://github.com/asdf-vm/asdf) for instructions on how to install & manage versions of `kafka`.

## Starting Kafka

<!-- stolen from: https://github.com/JoshAshby/asdf-kafka -->
```bash
$ zookeeper-server-start.sh "$(asdf where kafka)/config/zookeeper.properties"
$ kafka-server-start.sh "$(asdf where kafka)/config/server.properties"
```