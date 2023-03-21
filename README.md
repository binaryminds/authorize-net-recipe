# Authorize net recipe

### Installation
Setup endpoints collection under `extra.symfony.endpoint` int composer.json:

```json
    "extra": {
        "symfony": {
            "allow-contrib": false,
            "endpoint": [
                "https://api.github.com/repos/binaryminds/authorize-net-recipe/contents/index.json",
                "flex://defaults"
            ]
        }
    }
```
