# 500×500mm ステッカーデザイン設定

**サイズ**: 500×500mm
**レイアウト**: 15個×2行（合計30個のショートカット）

---

## ◉ ドキュメント設定

| 項目 | 設定値 |
|------|--------|
| **幅** | 500mm |
| **高さ** | 500mm |
| **DPI（解像度）** | 300dpi |
| **カラーモード** | CMYK |
| **裁ち落とし** | 3mm |

<br>

---

## ◉ レイアウト計算

### エリア分割

```
┌─────────────────────────────────────┐
│  ヘッダー（タイトル）: 50mm         │
├─────────────────────────────────────┤
│  1行目（15個）: 215mm                │
├─────────────────────────────────────┤
│  2行目（15個）: 215mm                │
└─────────────────────────────────────┘
```

### 1行あたりのサイズ

- **横幅**: 500mm - 左右マージン20mm = 480mm
- **1項目あたりの幅**: 480mm ÷ 15個 = 32mm
- **縦幅**: 215mm ÷ 15個 = 14.3mm（1項目あたり）

<br>

---

## ◉ フォントサイズ推奨

### サイズ感

| 箇所 | サイズ | 用途 |
|------|--------|------|
| **タイトル** | 80〜100pt | ヘッダー「超基本ショートカット30選」 |
| **ショートカットキー** | 40〜50pt | メイン（Ctrl + C など） |
| **説明文** | 28〜35pt | サブテキスト（コピー、貼り付けなど） |

**ポイント**:
- 500×500mmは大きいので、フォントサイズも大きめに
- 遠くから見ても読めるサイズ
- 太字で視認性を確保

<br>

---

## ◉ おすすめフォント

### 日本語フォント（視認性重視）

**1. Noto Sans JP（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/noto/specimen/Noto+Sans+JP
- **おすすめウェイト**: Bold（太字）/ Black（極太）
- **特徴**: Google製・視認性抜群・モダン・無料

**2. M PLUS 1p（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/M+PLUS+1p
- **おすすめウェイト**: Bold / ExtraBold
- **特徴**: 丸みがある・読みやすい・無料

**3. ZEN Kaku Gothic（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/Zen+Kaku+Gothic+New
- **おすすめウェイト**: Bold / Black
- **特徴**: ゴシック体・クリア・無料

**4. BIZ UDゴシック（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/BIZ+UDGothic
- **おすすめウェイト**: Bold
- **特徴**: UD（ユニバーサルデザイン）フォント・読みやすさ重視

**5. 源ノ角ゴシック / Source Han Sans（無料・商用利用OK）**
- **ダウンロード**: https://github.com/adobe-fonts/source-han-sans
- **おすすめウェイト**: Bold / Heavy
- **特徴**: Adobe製・プロ仕様・無料


### 欧文フォント（キー表記用）

**1. Inter（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/Inter
- **おすすめウェイト**: Bold / ExtraBold
- **特徴**: モダン・視認性抜群・「Ctrl」「Command」などに最適

**2. Roboto（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/Roboto
- **おすすめウェイト**: Bold / Black
- **特徴**: Google製・読みやすい・定番

**3. Poppins（無料・商用利用OK）**
- **ダウンロード**: https://fonts.google.com/specimen/Poppins
- **おすすめウェイト**: Bold / ExtraBold
- **特徴**: 丸みがある・おしゃれ・モダン

<br>

---

## ◉ フォント組み合わせ例

### パターン1: シンプル・ミニマル

- **タイトル**: Noto Sans JP Black（100pt）
- **ショートカット**: Inter Bold（45pt）
- **説明**: Noto Sans JP Regular（32pt）
- **雰囲気**: プロっぽい・洗練された


### パターン2: 柔らかい・親しみやすい

- **タイトル**: M PLUS 1p ExtraBold（100pt）
- **ショートカット**: Poppins Bold（45pt）
- **説明**: M PLUS 1p Regular（32pt）
- **雰囲気**: やわらかい・初心者向け


### パターン3: クリア・ビジネス

- **タイトル**: BIZ UDゴシック Bold（100pt）
- **ショートカット**: Roboto Bold（45pt）
- **説明**: BIZ UDゴシック Regular（32pt）
- **雰囲気**: 読みやすい・オフィス向け

<br>

---

## ◉ レイアウト例

### 1行目レイアウト（15個横並び）

```
┌────────┬────────┬────────┬────────┬────────┐
│Ctrl+C  │Ctrl+V  │Ctrl+X  │Ctrl+Z  │Ctrl+S  │ ...
│コピー   │貼付け  │切取り  │戻す    │保存    │
└────────┴────────┴────────┴────────┴────────┘
```

**ポイント**:
- 32mm幅に収まるように
- 上段: ショートカットキー（45pt・太字）
- 下段: 説明（32pt・通常）
- 余白: 各セル間2mm


### 全体イメージ

```
┌───────────────────────────────────────────┐
│     超基本ショートカット30選（100pt）      │
├───────────────────────────────────────────┤
│ 1行目（15個のショートカット）              │
│ Ctrl+C Ctrl+V Ctrl+X ... (45pt)          │
│ コピー 貼付け 切取り ... (32pt)           │
├───────────────────────────────────────────┤
│ 2行目（15個のショートカット）              │
│ Alt+Tab Win+D Win+E ... (45pt)           │
│ 切替え デスクトップ エクスプローラー (32pt)│
└───────────────────────────────────────────┘
```

<br>

---

## ◉ クイック設定まとめ

**Affinity Designerで設定する値**:

1. **ドキュメント**: 500×500mm / 300dpi / CMYK
2. **タイトルフォント**: Noto Sans JP Black / 100pt
3. **ショートカットフォント**: Inter Bold / 45pt
4. **説明フォント**: Noto Sans JP Regular / 32pt
5. **レイアウト**: 15個×2行 / 各セル32mm幅×14mm高さ
6. **余白**: 上下左右20mm

<br>

---

## ◉ フォントダウンロードリンクまとめ

**すぐにダウンロードできる無料フォント**:

- **Noto Sans JP**: https://fonts.google.com/noto/specimen/Noto+Sans+JP
- **Inter**: https://fonts.google.com/specimen/Inter
- **M PLUS 1p**: https://fonts.google.com/specimen/M+PLUS+1p
- **Poppins**: https://fonts.google.com/specimen/Poppins
- **Roboto**: https://fonts.google.com/specimen/Roboto
- **BIZ UDゴシック**: https://fonts.google.com/specimen/BIZ+UDGothic

**全て商用利用OK・無料です！**
