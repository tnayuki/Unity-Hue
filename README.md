# Unity-Hue

Unity用のPhilips Hueライブラリーです。

## 使い方

1. Unity-Hue.unitypackageをプロジェクトにインポートします。
2. シーンに「Hue/Prefabs/Hue Bridge」を配置します。
3. Hierarchy上で「Hue Bridge」を選択します。
4. 使用しているHueブリッジのホスト名・ポート番号・ユーザー名を、Inspector上で「Hue Bridge」コンポーネントに設定します。
5. 「Discovery Lights」をクリックすると、ブリッジに接続しているライトが検出されます。
6. 検出されたライトのGameObjectのプロパティ(ON/OFF、色)を変更すると、実際のライトに反映されます(実行中のみ)。

## 備考

Hue-emulatorで動作を確認しました。
(実機では未確認)

http://steveyo.github.io/Hue-Emulator/
