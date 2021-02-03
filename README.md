## レジお願いしますアプリのソース・素材

## 成果物
https://play.google.com/store/apps/details?id=com.itsumen.regi&hl=ja

## コマンド

```bash
$ npm i -g cordova
$ cordova create sample com.example.sample sample
$ cd sample
$ cordova platform add android
$ cordova plugin add cordova-plugin-volume-control
$ rm -rf www/*
$ cd www
$ git clone https://github.com/yuzuru2/regi_apuri_sozai.git .
$ cd ..
$ cordova run android
```
