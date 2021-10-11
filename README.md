# hello-world

## poetry 사용법 익히기

```shell
# add package, remove package
$ poetry add fastapi

# pip install과 동일. package를 local에 설치하기
$ poetry install

# vscode에서 import error 발생시
$ poetry shell
$ code .
# python env를 설정할 수 있음. 그 후에는 shell exit하면 이후에도 죽 사용가능함.
```

## pyenv를 이용하여 python 버전 변경

```shell
# 특정 python 설치하기
pyenv install 3.7.12

# 현재 디렉토리에 python version 설정하기
pyenv local 3.7.12

# python version에 맞게 package 설치하기
poetry install
```

## poetry env 삭제하기

```shell
# env list 확인하기
poetry env list

# 특정 env 삭제하기
poetry env remove <env-name>
```
