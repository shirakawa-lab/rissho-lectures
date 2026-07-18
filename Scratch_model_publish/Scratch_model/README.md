# Scratch AI教材モデル集

Scratch・機械学習・データサイエンスの授業で使用する、ブラウザ実行型教材の格納場所です。

## フォルダ規則

```text
Scratch_model/
├── index.html                 # 教材一覧
├── catalog.json               # 全教材の登録台帳
└── <model-slug>/
    ├── index.html             # 実行ページ
    ├── README.md              # 教員・学生向け説明
    └── model.json             # 教材メタデータ
```

## 登録済みモデル

| ID | 名称 | フォルダ | 内容 |
|---|---|---|---|
| scratch-ml-001 | 座位姿勢AIチェック | `sitting-posture-posenet/` | PoseNetによる正面・横向き座位姿勢の簡易評価 |

## 追加ルール

1. フォルダ名は英小文字・数字・ハイフンで付ける。
2. `index.html`、`README.md`、`model.json`を必ず置く。
3. `catalog.json`にモデルを1件追加する。
4. IDは `scratch-ml-002` のように連番にする。
5. 医療・健康分野の教材は、診断ではないことを明記する。
