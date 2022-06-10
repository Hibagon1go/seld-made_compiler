# Cの自作スモールコンパイラ

## 概要
- 低レイヤの勉強のため、 [このサイト](https://www.sigbus.info/compilerbook)を参考にして実装 💻
- M1 Mac + Dockerで環境を構築


## 環境構築における注意点
- [参考サイトのMac+Dockerでの環境構築](https://www.sigbus.info/compilerbook#docker)は、M1 Macの想定ではない
- 実際には、DockerImageをPullする際に、`platform=linux/x86_64`と指定する必要がある。
