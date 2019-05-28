# Commands

Make json human readable
```console
echo '{"foo": "lorem", "bar": "ipsum"}' | python -m json.tool
```

Get value from json

```console
echo '{"foo": "lorem", "bar": "ipsum"}' | python -c 'import json,sys;obj=json.load(sys.stdin);print obj["foo"]'
```
