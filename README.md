#### 概要
- shellモジュールでコマンドを実行して結果を表示

#### コマンド例
```
# ansible-playbook -i inventories/develop/hosts site.yml -u username --ask-pass | grep "msg"
 ```
