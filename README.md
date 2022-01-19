# Usage

Install dictionary:

```sh
yarn add --dev cspell-dict-pinyin
```

Config [CSpell file](https://cspell.org/configuration/#configuration) (`.cspell.json` or `cspell.json`):

```jsonc
{
    "dictionaries": ["pinyin"],
    "dictionaryDefinitions": [
        {
            "name": "pinyin",
            "path": "./node_modules/cspell-dict-pinyin/words.txt.gz"
        }
    ]
}
```
