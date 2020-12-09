# Open Platform for AI (OpenPAI) ![alt text][logo]

[logo]: ./pailogo.jpg "OpenPAI"

[![Build Status](https://travis-ci.org/microsoft/pai.svg?branch=master)](https://travis-ci.org/microsoft/pai)
[![Join the chat at https://gitter.im/Microsoft/pai](https://badges.gitter.im/Microsoft/pai.svg)](https://gitter.im/Microsoft/pai?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Version](https://img.shields.io/github/release/Microsoft/pai.svg)](https://github.com/Microsoft/pai/releases/latest)

**OpenPAI [v1.3.0](./RELEASE_NOTE.md#Nov-2020-version-130) has been released!**

权威README参考[microsoft/pai/README](https://github.com/microsoft/pai/blob/master/README.md)

这里fork了`microsoft/pai:pay-1.3.y`以及`kubernetes-sigs/kubespray:release-2.11`

主要目的是openPAI的gcr.azk8s.cn镜像源只能针对国内Azure用户使用，不对外公开。我将相对应的源全部更新到了whoami179的dockerhub中，并且上面fork的分支版本中的对应的代码是全部更新的。

只需要按照官方的说明进行config,master.csv,worker.csv这些文件的编辑，然后
```
git clone -b pai-1.3.y https://github.com/ReyRen/pai.git
```
继续按照官方安装步骤即可，其中我的requirement.sh注释掉了，可自行根据安装手册提前进行requirement检测
