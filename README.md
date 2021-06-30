# Colon x2 Marker for Markdown

This extends can introduce marker with colon to Markdown.

It is inspired by `markdown-it/markdown-it-mark` and `bear.app`.

## Notation

```markdown
::Notation::
```

## If you customize token color

`markup.bold.marker` is specified as scope.

Ex.) settings

```json
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "markup.bold.marker",
                "settings": {
                    "fontStyle": "bold underline"
                }

            }
        ]
    }
```
