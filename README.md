# my-tools

簡単なスクリプトなど

bin/

- v2s - MP4の動画ファイルから音声を抽出してMP3に変換する


### OpenAI Wisper のインストール

音声ファイルから文字起こしをする
[OpenAI Whisper](https://github.com/openai/whisper)
を使う場合は、以下のコマンドでインストールする。

```
pip install -U openai-whisper
```

音声ファイルから文字起こしは次のコマンド

```
whisper <音声ファイル> --language Japanese
```