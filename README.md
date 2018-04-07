# 재료역학 ][ 2017<br>Mechanics of Materials ][ 2017

교재 : Pytel 외 저, 이주성 외 역, 재료역학 2판, 한티미디어, 2013.<br>
Text: Pytel et. al, Mechanics of Materials, 2nd Ed, 2013.

### 설치 항목 Software to install

#### 파이썬 프로그래밍 언어 Python Programming Language
* [Anaconda 5.0.x Python 3.6.x version](https://www.continuum.io/downloads) <br>
경로 이름에 한글을 사용할 수 없음 Use ASCII characters for path name<br>
윈도우즈의 경우, 설치 후 [가상 환경 생성, 전환 2회 이상](https://graspthegist.com/post/learn-conda-1/) 확인 추천<br>
For Windows, after install, please check [creating a virtual environment](https://conda.io/docs/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands) and [switching between environment](https://conda.io/docs/user-guide/tasks/manage-environments.html#activating-an-environment) more than twice.

#### 깃 버전 관리 소프트웨어 Git Version Control Software
* 명령행 Commandline [Git for Windows](https://git-scm.com/download/win)<br>실습실 환경에서는 credential manager 설치 삼가<br>Credential manager may not be a best choice for a computer lab
* GUI [SourceTree](https://www.sourcetreeapp.com/download/) 또는 or [Github Desktop](https://desktop.github.com/)

#### 통합 개발 환경 Integrated Development Environment
##### Spyder
* Anaconda 5.x 와 함께 설치됨.<br>Anaconda 5.x includes spyder.
##### [PyCharm Community](https://www.jetbrains.com/pycharm/download/)
* PyCharm 을 실행시키기 위해 [Java Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/index.html) 를 설치해야 할 수 있음 (2016 09)<br>
PyCharm may need [Java Development Kit](http://www.oracle.com/technetwork/java/javase/downloads/index.html) to run.
##### [Microsoft Visual Studio Code](https://code.visualstudio.com/download)
* Anaconda 설치 후 설치 선택 가능<br>
Installation [button](https://blogs.msdn.microsoft.com/pythonengineering/2018/02/15/visual-studio-code-is-now-shipping-with-anaconda/) available at the end of Anaconda installation<br>
* [다운로드](https://code.visualstudio.com/download) 받아서 설치도 가능<br>
Possible to [download](https://code.visualstudio.com/download) and install from the website<br>
[Setup Overview](https://code.visualstudio.com/docs/setup/setup-overview) / 
[Python Configuration Instruction](https://code.visualstudio.com/docs/python/python-tutorial)

#### 설치 동영상<br>Installation video
[![설치 동영상 Installation video](https://i.ytimg.com/vi/NAQn1jQws3Q/hqdefault.jpg)](https://www.youtube.com/embed/videoseries?list=PLA6B0Lmr9oJOuvxMPNjDcnAfmqw907Bqy)

### `jupyter` 노트북 실행시키는 법<br>How to start a `jupyter` notebook
이 저장소 는 주로 [`jupyter` 노트북](http://blog.ncsoft.com/?p=21870)으로 만들어져 있음.<br>
This repository is mostly written in [`jupyter` notebook](http://arogozhnikov.github.io/2016/09/10/jupyter-features.html).<br>
`jupyter` 노트북은 웹브라우저를 통해 프로그램 코드를 수정 실행하고 LaTex 수식을 포함한 문서 작성이 가능함.<br>
Through a web browser, `jupyter` notebook enables editing & running program codes and writing documents including LaTex equations.<br>

* 적당한 folder 를 만듦 (예를 들어 User/Documents/SolMech/) <br> Make an appropriate folder (e.g., User/Documents/SolMech/)
* Git 또는 SourceTree 를 이용하여 위 folder 아래 이 원격 저장소를 `git clone` <br> Using the Git or SourceTree, `git clone` this repository under the folder
* `cmd` 또는 `git bash` 실행한 후 `clone` 된 지역 저장소 folder로 이동 (예를 들어 `cd User/Documents/Solmech/`) <br> Start `cmd` or `git bash` and change working folder to the cloned folder (e.g. `cd User/Documents/Solmech/`)
* `cmd` 또는 `git bash` 에서 각각 `cd` 또는 `pwd` 로 `clone` 된 folder 인지 확인 <br>Check location using `cd` or `pwd` in `cmd` or `git bash`
* `jupyter notebook` 실행 <br>Run `jupyter notebook`

#### 실행 동영상<br>Instruction video
[![실행 동영상 Instruction video](https://i.ytimg.com/vi/W6ynqGKJFSs/hqdefault.jpg)](https://www.youtube.com/embed/videoseries?list=PLA6B0Lmr9oJO9HeSC74wqxECtwpUPJfdm)
