# openvino-workshop-jp

## Overview
これはIntel distribution of OpenVINO toolkitのハンズオン・ワークショップコンテンツです。
このワークショップコンテンツはUbuntuとWindows 10上で動作確認しています。

## Description
[Intel distribution of OpenVINO toolkit](https://software.intel.com/en-us/openvino-toolkit)はコンピュータービジョンアプリケーションのためのライブラリスイートです。OpenVINOは様々なライブラリやツールで構成されています。
- Inference Engine - 高効率、高性能で柔軟性の高いディープラーニング推論ランタイムライブラリ
- Model Optimizer - 一般的な学習済みディープラーニングモデルをOpenVINO IR形式に変換するツール
- Model Downloader - OMZ(Open Model Zoo, Intel)モデルや一般的なパブリックディープラーニングモデルをダウンロードするツール
- Deep Learning Workbench - モデルの再量子化(int8)、ベンチマーク、精度テストなどを行えるツール
- OpenCV - 高性能、高機能な画像処理ライブラリ

OpenVINOは高いスケーラビリティーを持っています。様々なディープラーニングプロセッサやアクセラレータをサポートします。一度書いたコードをほとんどをのまま別のプロセッサ上で走らせることも可能です。
- CPU - AtomからXeonまで。OpenVINOは最新のDL Boost命令セットもサポートします
- Integrated GPU - 内蔵GPUを活用しディープラーニング推論処理をCPUからオフロードすることも可能です
- VPU - Vision Processing Unit (Myriad). 低消費電力かつ高性能なディープラーニングアクセラレーター
- FPGA - OpenVINO互換FPGAアクセラレーターカードを使用可能
- HDDL - High Density Deep Learning accelerator. 一つ、または複数のMyriadデバイスが搭載されたアクセラレーターカード

また、OpenVINOは幅広いOSをサポートします。
- Windows 10, Ubuntu, CentOS, MacOS

このハンズオンワークショップを通して、下記の内容を習得可能です。
1.  OpenVINO APIの基礎: 簡単な画像分類プログラム - [classification.ipynb](./classification.ipynb)
2.  OpenVINOを使った物体検出プログラムの基礎 - [object-detection-ssd.ipynb](./object-detection-ssd.ipynb)
3.  非同期推論実行方法の基礎 - [classification-async-single.ipynb](./classification-async-single.ipynb)
4.  非同期推論、同時推論を使った高スループットアプリケーションの基礎 - [classification-async-multi.ipynb](./classification-async-multi.ipynb)

## How to use
1. Intel distribution of OpenVINO toolkit [web page](https://software.intel.com/en-us/openvino-toolkit)に行き、お使いのOS用のOpenVINOパッケージをダウンロードする
2. ['Get Started'](https://software.intel.com/en-us/openvino-toolkit/documentation/get-started)ページの手順に従ってOpenVINOをインストールする
3. このレポジトリをクローンする
~~~shell
$ git clone https://github.com/yas-sim/openvino-workshop-en
~~~
4. コマンドターミナルを開く
5. OpenVINO環境変数の設定を行う
~~~
Linux $ source /opt/intel/openvino/bin/setupvars.sh
~~~
~~~
Windows > call "Program Files (x86)\IntelSWTools\OpenVINO\bin\setupvars.bat"
~~~

6. Jupyter notebookを開始する
7. Jupyterで`openvino-workshop-jp/START-HERE.ipynb`を開く

## Requirement
This workshop requires [Intel distribution of OpenVINO toolkit](https://software.intel.com/en-us/openvino-toolkit
).

## Contribution

## Licence

[Apache2](http://www.apache.org/licenses/LICENSE-2.0.txt)

## Author

[Yasunori Shimura](https://github.com/yassim-intel)
