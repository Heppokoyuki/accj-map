## list.jsonの生成方法
```sh
ls -1 | jq -R . | jq -s . > list.json
```
