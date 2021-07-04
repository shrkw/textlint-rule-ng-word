This project is forked cause the original project author terminated the maintenance.

# textlint-rule-ng-word
[textlint](https://github.com/textlint/textlint) rule that check NG word.

## Installation

```
npm install @shrkw/textlint-rule-ng-word
```

## Usage

```
npm install -g textlint @shrkw/textlint-rule-ng-word
textlint --rule ng-word README.md
```

## Config

```
{
  "rules": {
    "ng-word": {
      "words": ["word1", "word2"]
    }
  }
}
```

## Tests

```
npm test
```

## License
MIT
