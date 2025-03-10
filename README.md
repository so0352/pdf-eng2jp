# pdf-eng2jp

英語pdfを日本語pdfにローカルで変換する試み

## 使い方
1. ```
    docker compose up -d --build
    ```
    を実行する．
2. ```
    localhost:7860
    ```
    にアクセスする．
3.  翻訳したいpdfファイルをアップロードする．

    option欄を以下のように設定
    ![option欄](./img.png)

4. Translate from と Translate to を任意に設定する．

5. Translated から翻訳語のpdfがダウンロードできる．

## 参考
https://github.com/Byaidu/PDFMathTranslate

https://github.com/ollama/ollama

https://hub.docker.com/r/byaidu/pdf2zh

https://hub.docker.com/r/ollama/ollama

