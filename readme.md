# 中谷 研究引き継ぎ資料

## 研究のソースコード
* [合成花画像の作成](https://github.com/opu-imp/create_syntheic_flower_img)
* [Conditional DETR](https://github.com/opu-imp/PrivateConditionalDETR) 
* [花弁のアプリ](https://github.com/opu-imp/flw_app)
* [2022年アルバイト分の根の解析](https://github.com/opu-imp/plant-root-2022)
  * セグメンテーションの説明はsrsuディレクトリに記載
* [2024年分の根の解析](https://github.com/opu-imp/plant-root-2024)

## 実験オリジナルデータ
Google 共有Driveの`impshare2/nakatani/data`に配置
* plant-root
    * seedpack_2020
    * soybean_root2021
    * soybean_root2021_2
* plant-petal
    * 合成画像作成用_花弁切り出し手順.mov
    * img
        * initial_original_img: 初めに藤本先生からいただいた花画像データ
        * labeled3292: ユニメディアさんにラベル付けしてもらった正解データ
        * petals_for_synthetic: 
    * model
        * maml: MAMLのモデルパラメータファイル(pytorch)
        * exp21_best.pt: yolov5のモデルパラメータファイル(pytorch)

## 研究発表資料
Google 共有Driveの`imppub/nakatani`に配置
