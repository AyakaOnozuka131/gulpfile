# gulpfile
## Require
* node.js
version >= 12.16.1

## Getting Started
### Install npm package
```bash
npm install
```

## Usage
### Commands
#### Run develop server
```bash
npm run start
```

## Constitution
```
.
├── README.md
└── assets : npm run startでファイル出力先
│   └── ...
└── src
│   ├── css
│		│		├── foundation : scss base settings
│   │   ├── layout : scss layout settings
│   │   └── object : FLOCSSをベースに分類
│   │       ├── component
│   │       ├── project
│   │       └── utility
│   └── js
├── gulpfile.js
├── node_modules
└── package.json


```

## Commit rules
### Emoji Prefix
|Emoji| コミットタイプ|
|---|---|
|✨ `:sparkles:` |新規機能追加|
|📝 `:memo:` |ドキュメント追加|
|🔉 `:sound:`|ログ追加|
|✅ `:white_check_mark:`|テストの追加|
|👍 `:+1:`|機能修正|
|🚀  `:rocket:` |パフォーマンス改善|
|👮  `:cop:`|セキュリティ関連の改善|
|✏️ `:pencil2:`|タイポなどの修正|
|🎨 `:art:`|リファクタリング|
|🚧 `:construction:`|コメントアウトなど|
|🔥 `:fire: `|ファイル削除|
|🔇  `:mute:`|ログ削除|
|🐛 `:bug:` |バグ修正|
|🔖  `:bookmark:` |バージョンアップ|
|🎉 `:tada:`|イニシャルコミット|

### Type of commit

|コミットメッセージ | 意味|
|---|---|
|Add| 新規(ファイル)機能追加|
|Update| 機能修正、既存機能追加（バグではない)|
|Clean|リファクタリング|
|Remove|削除など|
|Fix|バグ修正|
|Upgrade|バージョンアップ|
