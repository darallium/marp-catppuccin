# marp-catppuccin

## ビルド

```bash
git clone https://github.com/darallium/marp-catppuccin marp-ctp
cd marp-ctp
marp 
```

## 出力形式の設定

.marprc.yml で出力形式を切り替えれます。
以下のキーをもとにコメントアウトを外してください。

HTML出力
```yaml
html: true
```

PDF出力
```yaml
pdf: true
```

PNG画像出力
```yaml
image: "png"
```

PPTX出力
```yaml
pptx: true
```

ほかのオプションとして、一番下のpreviewをtrueにすると1回だけビルド。watchをtrueにすると変更を監視して常時ビルドになる。

## カスタムテーマ

markdownのfrontmatterのthemeに以下のいずれかを設定してください。
- catppuccin-frappe
- catppuccin-latte
- catppuccin-macchiato
- catppuccin-mocha
