"# ionic3-camera" 

androidアプリとしてapkファイルを作成するためには、

AndroidStudioで、platforms/android を開き、File > Project Structure > Projectタブで

```
Gradle Version を 4.6 に変更
Android Plugin Version　を　3.2.0　に変更
```

その後、 Build > Build bundle > Build APK

“プロジェクトフォルダ\app\build\outputs\apk\”配下に.apkファイルが作成される。

これを、GoogleDrive経由でAndroidスマホにインストール。

2018/10/8現在、カメラが動いたことを確認しています。

参考：http://android-java.hatenablog.jp/entry/2018/09/30/191211

参考：http://i-doctor.sakura.ne.jp/dokuwiki/doku.php/ionic3%E3%81%A7camera%E3%83%97%E3%83%A9%E3%82%B0%E3%82%A4%E3%83%B3

