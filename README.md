## Tutorials for CHIRIMEN / CHIRIMEN チュートリアル
This site contains tutorials for "CHIRIMEN for Raspberry Pi 3.

このサイトは "CHIRIMEN BLE" のチュートリアルサイトです。

CHIRIMEN コミュニティと W3C の Browsers and Robotics コミュニティグループでは、JavaScript で Web アプリから電子パーツを直接制御できる低レベルハードウェア制御 API (WebGPIO API や WebI2C API など) の標準化に向けての検討や、それらの API を実際の開発ボード上で試せるようにするプロトタイプ環境の開発を行っています。Web ページ中の JavaScript で直接ハードを制御できる環境を実現することで、既存の Web 関連の知識・環境・サービスをすべて活かしたまま、同じプログラムの中で簡単に画面やサービスと電子パーツを制御可能になります。電子パーツの制御だけのために専用のツールや開発環境を用意したり、複数の言語やプログラムを連携した複雑な仕組みを理解して作る必要がないため、素早くプロトタイピングを行ったり、プログラミング初学者が IoT の基礎を学ぶ上で最適な環境です。

現在、CHIRIMEN コミュニティでは最新の CHIRIMEN 環境をブラウザと Bluetooth LE (BLE) で接続されたインターフェースボードの組み合わせで動作させるようにメンテナンスしており、このサイトではその使い方を学ぶためのチュートリアルを掲載しています。

CHIRIMEN BLE はスイッチサイエンスの BLE 開発ボード、TY51822r3 とブラウザが動作する PC 環境があれば試す事ができます。TY51822r3 には mbed で公開されている [btGPIO_TY51](https://os.mbed.com/users/nakamura_bs/code/btGPIO_TY51/) を書き込み、PC のブラウザでは、GitHub で公開されている [chirimenble](https://github.com/Nakamura2013/chirimenble) をダウンロードしてローカルファイルにアクセスまたは公開されている URL にオンラインでアクセスします。

## CHIRIMEN BLE チュートリアル

CHIRIMEN Raspi3 チュートリアルの各ページはこちらでご覧頂けます:

* [0. Hello World](./ble/ja/section0.md)
* [1. GPIO 編](./ble/ja/section1.md)
* [2. I2C 編](./ble/ja/section2.md)
* Appendix / FAQ
  * [JavaScript 1 Day 講習 (外部 PDF)](https://webiotmakers.github.io/static/docs/2017/maebashi-js.pdf)
  * [非同期処理 (async await版)].(/raspi3/ja/appendix0.md)
  * [よくある質問](./raspi3/ja/faq.md)


## Online Version / オンライン版
Latest version of this site is hosted on https://tutorial.chirimen.org/

このサイトのオンライン版は https://tutorial.chirimen.org/ でご覧頂けます

## Feedback / フィードバック
If you have any feedback to this tutorials, see [Feedback Page](feedback.md)

本チュートリアルにご指摘やご提案のある方、編集に協力頂ける方は [フィードバックページ](feedback.md) をご覧ください。
