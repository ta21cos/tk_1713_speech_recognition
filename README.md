GoogleSpeechAPIとnode.jsで動くリアルタイム音声認識

実行するためには
```
export GOOGLE_APPLICATION_CREDENTIALS=xxxxx.json
```
というようにjson形式の認証ファイルを指定する必要がある

必要なnode_moduleは
```
npm install @google-cloud/speech
npm install node-record-lpcm16
```

大きな声ではっきり言わないと区切りと認識されない
