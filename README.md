# Raspberry Pi - Build Checker

[![Build Status](https://travis-ci.org/mrprompt/raspberry-build-checker.svg?branch=master)](https://travis-ci.org/mrprompt/raspberry-build-checker)
[![Code Climate](https://codeclimate.com/github/mrprompt/raspberry-build-checker/badges/gpa.svg)](https://codeclimate.com/github/mrprompt/raspberry-build-checker)
[![Test Coverage](https://codeclimate.com/github/mrprompt/raspberry-build-checker/badges/coverage.svg)](https://codeclimate.com/github/mrprompt/raspberry-build-checker/coverage)
[![Issue Count](https://codeclimate.com/github/mrprompt/raspberry-build-checker/badges/issue_count.svg)](https://codeclimate.com/github/mrprompt/raspberry-build-checker)

A build checker based on LEDs to Raspberry Pi.

## Instalação

```
git clone https://github.com/mrprompt/raspberry-build-checker
cd raspberry-build-checker
pip install -e .[test]
```

## LEDs GPIO 

* 11 = Green - Success
* 13 = White - Running
* 16 = Red - Error

## Uso

Com varíaveis de ambiente
```
GITHUB_REPOSITORY="<github-repository-slug>" GITHUB_TOKEN="<github-access-token>" checker 
```

Com argumentos

```
checker "<github-repository-slug>" "<github-access-token>" 
```

## Raspberry Pi

Com varíaveis de ambiente
```
GITHUB_REPOSITORY="<github-repository-slug>" GITHUB_TOKEN="<github-access-token>" rpi-checker 
```

Com argumentos

```
rpi-checker "<github-repository-slug>" "<github-access-token>" 
```

## Testes

```
py.test
```

## License

MIT
