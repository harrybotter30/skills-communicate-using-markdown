# 毎日の学習

## 朝の計画

- [ ] トピックのアイデアについては[GitHubブログ](https://github.blog/)をチェックする。
- [ ] [GitHub Pages](https://skills.github.com/#first-day-on-github)について学ぶ。
- [ ] 初めてのブログ投稿を実際のウェブページに変換する。

## レビュー

[ffmpeg](https://www.ffmpeg.org)を使用して画像や動画をダークモードからライトモードに変換する

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
