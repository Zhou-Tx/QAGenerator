# QAGenerator

QAGenerator is an automatic execution program that converts doc into standard question-answer pairs.
QAGenerator支持自动将文档文件转为标准问答对

（一）初始化环境

```zsh
# Linux / MacOS
python3 -m venv venv
source ./venv/bin/activate
pip install -r requirements.txt
```

```shell
# Windows
python -m venv venv
./venv/Scripts/activate
pip install -r requirements.txt
```

（二）打包

```shell
pyinstaller -wF __main__.py -n QAGenerator
```
