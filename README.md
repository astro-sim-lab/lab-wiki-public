# Laboratory
- これから研究を始める学生向けの情報を蓄積・共有するページです。
- 研究や進捗報告の流れをまとめていますが、これは一例です。研究者は一人一人異なる・自分に合ったスタイルを構築します。もちろん、最低限パスするべき条件はあります。
- 編集方針: [PRINCIPLES.md](./PRINCIPLES.md)

## Lab Wiki (docs)
- 生活・ルール系の情報は [docs/README.md](docs/README.md) に集約しています。
- 研究用PC環境設定・コード関連は別リポジトリを参照してください。

## MkDocs Site
- このリポジトリは `MkDocs + Material + awesome-pages` で閲覧用サイトを生成できます。

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

- ビルド: `mkdocs build`
- 設定: `mkdocs.yml`（`repo_url` は実際のGitHub URLに置き換えてください）
- GitHub Pages公開: `Settings > Pages > Build and deployment` で `Source: GitHub Actions` を選択

# 研究とは
- 「研究は、新たな発見をすることである。つまり、たくさん失敗して成功をつかみ取ることである」
- 「研究する = 挑戦して(イノベーション)失敗する」です。
- 「挑戦して失敗して、そこから成功に結びつける訓練をしてください」
- 「流行の言葉を使うなら、"コスパ良く"失敗するスキルを身につけてください」
- 「全ての人間は生まれつき知ることを欲する。」(形而上学、アリストテレス)
- 指導教官の言葉より実験結果と格闘せよ「なぜわれわれは、この宇宙のいろんな部分の知識を追求するにあたって、神の作品たる自然から始めずして、むしろ神の言葉である聖書から始めねばならぬのでしょうか。」（1633年、ガリレイが友人に向けた手紙より）
- 「天文学とは我々が天や星に着目するときに生じる事柄の原因を提示する学問である。それは事物や自然現象の原因を探究するがゆえに、物理学の一部である。」(コペルニクス天文学概要)

# 卒研指導テーマ例
数値シミュレーションや大規模データ解析を用いた宇宙物理・天体現象の研究
（１）初代星の形成・進化・最期
（２）超大質量ブラックホールの起源
（３）宇宙の大規模構造への宇宙論・暗黒物質モデルの影響
（４）観測される星形成領域のシミュレーション解析
（５）化学反応ネットワークの機械学習
(X) 石山サンプルからボイドミニハローを探す。
(X) one-zone modelの改築。東モデルに組み込む反応を足していく。

## これまでの学生研究テーマ
- 大学の公開リポジトリへのリンクをまとめる

## 参考資料
- 「天文学・宇宙物理学の長期計画―2030-2040年代のビジョン」(日本学術会議, 2023)(https://www.scj.go.jp/ja/member/iinkai/kiroku/3-20230801.pdf)
- 「一家に１枚」(文部科学省)(https://www.mext.go.jp/stw/series.html)

# 進捗MTG
- 最初にルール決めを提案する。ルールは都度追加・修正する。
- 「研究を進めるとき、結果はメンター教員にとっても未知」であるため、「教員の経験による否定」には間違いが当然ありうる。教員自身がチェックする場合は正しい場合が多いが、学生が行った実験結果を間接的に評価する場合には間違えることもある。学生は、自分が納得するまで説明してもらうよう議論を続けること。「わかりました（わかんない）」は、やめる。
- 締切があると、その期限内での効率的な取り組みを考える。無制限だと、人は動かなくなる。卒研・演習の提出期限を短くしよう。

# 研究ステージ別
- 学士
- 修士
- 博士
- ポスドク
- スタッフ

## 参考資料
- (全般)「学術界サバイバル術入門」(Natureダイジェスト)()
- (ラボ運営)「桜井政博のゲーム作るには」(桜井 政博, 2022-2024)(https://www.youtube.com/@sora_sakurai_jp)

# Tools
- 主に平野が使用しているツールをまとめています。
- 「共同編集 + コメント + バージョン管理」機能を重視します。

## 研究ノート
- Notion

## 進捗共有
- Slack / Discord
- Zoom

## プレゼン
- 「難しいことを難しいまま伝える方法@慶応大学」(ヨビノリタクミ, 2023)(https://www.youtube.com/watch?v=RVlGTQ9R-_Q&list=PLHojTShnfYxrLlY56g6ph_rBSlT8_iE58&index=12)

## 論文
- Overleaf (LaTeX)
- 「「公用文作成の考え方」について（建議）」(文化審議会, 2022) (https://www.bunka.go.jp/seisaku/bunkashingikai/kokugo/hokoku/93650001_01.html)
- 「サイエンスイラストで「伝わる」科学」(大内田 美沙紀, 2023-2024)(https://www.igaku-shoin.co.jp/paper/series/208)

## コード開発
- VScode + Copilot (GitHub Education)
- Sublime Text
- GitHub (desktop)
- C / Fortran / Python (+ astropy)

## ハードウェア
- Desktop: Win / Linux
- Laptop: MacBookPro / Surface Pro
- Tablet: iPad mini
- Display: EIZO
- Keyboard: REALFORCE
- Mouse: Logicool MX Master 3S
- NAS: Synology

# 生成AIとの付き合い方 (暫定版)
- 剽窃と生成AI利用についてのガイドラインを確認する。
- アイデア出しの壁役
  - 生成AIは、質問に対して肯定的な回答を「作る」傾向にある。特に回答が明確ではない論文・研究サーベイでは、存在しない文献を「捏造する」。
- 書類の校正
- 想定質問の生成
