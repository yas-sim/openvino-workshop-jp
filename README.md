## Overview
これはIntel DevCloud for the Edgeのハンズオン・ワークショップのコンテンツです。

## Description
Intel DevCloudはインテルが提供するクラウドサービスです。クラウド上にIntel distribution of OpenVINO toolkitがプリインストールされた様々な構成のハードウエアが用意されています。ユーザーはそれらを使いOpenVINOを使ったアプリケーションのテストやベンチマーキングを行うことが可能です。  
[DevCloud for the Edge web page](https://devcloud.intel.com/edge/)

このワークショップを通して、下記のことを学ぶことができます。
1.  Jupyter notebookの基本的な使い方 [jupyter-basic.ipynb](./jupyter-basic.ipynb)
2.  DevCloudの基本的な使い方 [devcloud-basic.ipynb](./devcloud-basic.ipynb)
3.  OpenVINO BenchmarkをDevCloudで実行する方法 [benchmarking.ipynb](./benchmarking.ipynb)
4.  OpenVINOを使用するC++プロジェクトの作り方と、DevCloudでの実行方法 [cpp-project.ipynb](./cpp-project.ipynb)
5. <おまけ> DevCloudでのテストを自動化する - [automated-testing.ipynb](automated-testing.ipynb)

## How to use
1. [DevCloud for the Edgeのweb page](https://devcloud.intel.com/edge/)に行き、sign-upし、アカウントを取得します
2. DevCloud for the EdgeにSign-inします
3. 'Advanced' - 'Connect and Create' を選択します
4. Jupyter notebook、あるいはJupyterLabを選択します (お好みでどうぞ)
5. Jupyterから、コマンドターミナルを開きます ('New' - 'Terminal')
6. このプロジェクトをcloneします
~~~shell
$ git clone https://github.com/yas-sim/devcloud-workshop-en
~~~
7. Jupyterで`devcloud-workshop-en/START-HERE.ipynb`を開きます

## Requirement
このワークショップコンテンツは[Intel DevCloud for the Edge](https://devcloud.intel.com/edge/)上で実行されることを想定しています。他のシステム上では正しく動きません。  
[Intel distribution of OpenVINO toolkit](https://software.intel.com/en-us/openvino-toolkit
)が必要ですが、DevCloud for the Edge上のシステムにはすでにインストールされていますので、別途インストールを行う必要はありません。

## Contribution

## Licence

[Apache2](http://www.apache.org/licenses/LICENSE-2.0.txt)

## Author

[Yasunori Shimura](https://github.com/yassim-intel)
