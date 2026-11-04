# ライセンス一覧・AI申告文（2026-11-04）

| 対象 | 出所と扱い | 同梱・記録 |
|---|---|---|
| Godot Engine 4.7.2 | MIT。実行中エンジンのAPIから取得 | licenses/GODOT-LICENSE.txt |
| Godotの組み込みライブラリ | 使用エンジンが返す102構成部品・19ライセンス本文 | licenses/GODOT-THIRD-PARTY.txt |
| DotGothic16 | Fontworks Project Authors / SIL OFL 1.1 | licenses/DotGothic16-OFL.txt。元godot/fonts/OFL.txtと同一 |
| キャラクター・敵・背景・アイコン・文字絵 | 開発者指示の画像生成AIで制作、縮小・透過整理・組み込み | art_src/ の原画とプロンプト。既存ゲームROMの画像は配布素材に使わない |
| BGM | 開発者がSunoで生成 | 24曲すべて有料プラン中に制作（元22曲は2026-11-01、追加2曲のゆめ・かわべは2026-11-04ユーザー確認）。元曲・制作日・ダウンロード記録は保持 |
| 効果音 | godot/scripts/sfx.gd等のプログラム合成 | 外部音源サンプルを読み込まない実装を確認 |
| UIフォントの数字・矢印 | プロジェクト内生成のビットマップ | godot/fonts/damage-fun.fnt・ui-arrows.fntおよび制作ツール |
| 文章・翻訳・プログラム | 開発者＋AI補助 | 文章は以下の申告対象に含める |

第三者製エンジン・フォントの全文は `licenses/` にまとめ、Windows/Web書き出し時に配布先へコピーする。今後外部素材・プラグインを追加したら、この一覧と同梱物を更新する。

## Steamコンテンツ調査に提出する文章（案・未送信）

日本語：キャラクター、敵、背景、アイコンなどの画像には、開発者の指示で画像生成AIを用いて制作し、ゲーム用に加工したものを使用しています。一部の文章・翻訳にはAIの補助を使用しています。音楽は開発者が音楽生成AI（Suno）を用いて制作しています。ゲームの実行中にAIがコンテンツを生成する機能はありません。

English: Character, enemy, background and icon artwork includes images created with image-generation AI under the developer's direction and processed for use in the game. Some writing and translations were produced with AI assistance. The developer created the music using Suno. The game does not generate AI content during play.

事前生成のみ。Steamworksへの送信はしていない。音楽の権利確認記録は既存のユーザー申告に基づき、生成日・契約情報の証明書をこちらで発行したものではない。

## 公式資料（2026-11-04確認）

- Godot: https://docs.godotengine.org/en/latest/about/complying_with_licenses.html
- Godotライセンス: https://godotengine.org/license/
- DotGothic16: 同梱OFL.txtと https://github.com/fontworks-fonts/DotGothic16
- Suno: https://help.suno.com/en/articles/9601665
- Steam: https://partner.steamgames.com/doc/gettingstarted/contentsurvey

AI素材を使っているという申告と、個々の素材の権利確認は別に扱う。新規第三者素材の追加をこの一覧だけで一括許諾したものとはしない。
