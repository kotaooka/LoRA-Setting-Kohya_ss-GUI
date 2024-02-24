# LoRA Settings for Kohya_ss GUI

## 概要
  このjsonファイルは低VRAM環境で768×768のLoRA学習をするための設定ファイルです。
  
  https://github.com/bmaltais/kohya_ss

  ![image](https://github.com/kotaooka/LoRASetting-Kohya_ss-GUI/assets/115392256/522b8052-310d-4f4a-a82b-8334895214e9)

## 使い方
  1. jsonファイルをダウンロードして Kohya ss GUIのLoRAタブから読み込んでください
  2. 下記項目をお好みで指定してください
  ```
    Pretrained model name or path
    Image folder
    Output folder
    Model output name
  ```
  3.使用しているGPUによってfp16かbf16を選択してください
  　※RTX30xx以降ではbf16のままで問題ありません
  ![image](https://github.com/kotaooka/LoRASetting-Kohya_ss-GUI/assets/115392256/a9146e3a-fd6a-48fc-9737-665608526eec)
