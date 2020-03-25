由于平台不同，xgboost需要最新版本的gcc来支持，多线程处理。

在macOS下面，可以通过brew install gcc
然后在path下面指向最新版本的gcc

直接通过pip3 install xgboost还可能失败，可以通过把代码拉下来，通过指导
cmake，已经 make 来编译本地的xgboost包

最后再通过pip3 install xgboost便可以了。