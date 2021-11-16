# fluentd-for-avis

fluentd-for-avis は、[avis](https://github.com/latonaio/avis) のデータ収集元として、エッジ端末等内においてログデータを収集するためのリソースです。  
fluentd を動かすためには、fluentd-for-avis の他に、下記のようなレポジトリを参照して、設定を行う必要があります。  

* fluentd-for-docker-containers  
* fluentd-core-kube  
* fluentd-for-containers-mongodb-kube  

## 動作環境
fluentd-for-avis は、以下の動作環境を前提としています。  

* OS: Linux OS  
* CPU: ARM/AMD/Intel  

## サンプル定義ファイル

本リポジトリには、fluentd-for-avisとしてのサンプル定義ファイル fluentd-configmap.yaml が格納されています。  

## AION での fluentd の動作  
AION で fluentd を動かすためには、主にエッジコンピューティング環境の特性とシステム要求に留意して、aion-core-manifests に適切な追加設定を行う必要があります。  