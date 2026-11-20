# mll-games

ブラウザで遊べるゲームを置くリポジトリです。各ゲームは専用ディレクトリの中の単一HTMLファイル（index.html）で動作します。ルートの index.html がゲーム一覧ページです。

## ゲーム一覧

- [スネークゲーム DX](snake-dx/index.html) — りんごを食べてヘビを伸ばすスネークゲーム。画面をなぞった方向にヘビが自由に動き（斜め・カーブOK）、壁はすり抜け。コンボ＆フィーバー、アイテム、ミッション20種、全10ステージ制、スキン解放、S〜SSランク評価、効果音つき。
- [スターシューター](star-shooter/index.html) — ウェーブ制の縦型シューティング。ドラッグ・マウス・矢印キー/WASDで自機を操作し、自動発射で敵を撃墜。敵は直進・ジグザグ・射撃・大型の4種、ウェーブが進むほど難易度アップ。コンボ倍率、パワーアップ（武器強化・シールド・ボム）、ライフ3、ベストスコア保存つき。
- [バランスタワー](baransutawa/index.html) — 物理演算の積み上げゲーム。クレーンからブロックを落としてタワーを高く積み上げる。はみ出すほどタワーが傾いて崩れやすく、風・ライフ3・5段ごとのボーナスブロックで難易度が変化。パーフェクトのコンボ、ヒットストップや画面振動などの手応え演出、5・10・20・30段でのテーマ解放、ベストスコア保存、S〜Cランク評価つき。
- [タイミング斬り](timing-zan/index.html) — スワイプ斬撃アクション。画面下から放物線で放り投げられる果物をスワイプで真っ二つに斬る。両半分が飛び散り果汁が飛ぶ演出、ヒットストップ・スローモーション・画面振動。同時斬りボーナス（1スワイプ3個以上）、コンボ、FEVER（スコア2倍）、金の果物150点、落下でライフ減、斬ると爆発する爆弾、WAVE制の難易度、累計スコアで刀5種を解放・切替、ミッション9種、ベストスコア保存つき。
- [まもりの塔](mamori-tower/index.html) — タワーディフェンス。うねる道を進む敵から城を守る。弓塔・砲塔・氷塔・雷塔の4種タワー（各Lv3まで強化・売却可）、スライム・コウモリ・ゴーレム・ボスの4種の敵、全15ウェーブ（5・10・15がボスウェーブ）。ゴール直前撃破のボーナスコイン、ミッション6種、ウェーブ3・5でのタワー解放、ヒットストップ・画面振動・効果音、ベストスコア保存つき。
- [ニトロラッシュ](nitro-rush/index.html) — レース／3レーンドッジ。3レーンのハイウェイを駆け抜け、一般車・高速車・トラック・バリアを避けてコインを集める。ニトロ加速でスコア倍率×2、ギリギリすり抜けのニアミスでコンボボーナス。500mごとのレベルアップ（5の倍数はラッシュ）、ライフ3、ミッション6種、累計距離でマシン4種を解放、ベストスコア・ベスト距離保存つき。
- [ブロックラッシュ](block-rush/index.html) — ブロック崩し。パドルでボールを弾いてブロックを全て壊すとステージクリア（全10ステージ）。パドルに当てず連続破壊でコンボ倍率アップ、金ブロック高得点、耐久ブロック・動くブロック。カプセル7種（マルチボール・ワイド・レーザー・スロー・キャッチ・ライフ+1・悪いパドル縮小）、ミッション6種、累計スコアでパドルスキン4種を解放、ヒットストップ・画面振動・効果音、ベストスコア保存つき。
- [ビートタップ](beat-tap/index.html) — リズムゲーム。BGM（BPM 110）のビートに合わせて4レーンに落ちてくるノーツを叩く。PERFECT/GOOD/MISS判定、ヒットストップ・パーティクル・画面振動、コンボ20でFEVER（スコア×2）、ロングノーツ、曲ループごとのレベルアップ、ミッション6種、累計スコアでノーツスキン4種を解放、ベストスコア・最大コンボ保存つき。
- [カラーチェイン](color-chain/index.html) — パズル。同じ色のオーブをなぞってつなげて消す（7×7盤面、8方向）。スコア10×n×n、3秒以内の連続消去でコンボ倍率（最大×3）、8個以上のチェーンでFEVER（スコア×2）。60秒で目標スコアを目指すレベル制、Lv3で5色・Lv5で6色、Lv4から岩ブロック、詰み時は自動シャッフル。ミッション6種、累計スコアで盤面テーマ4種を解放、ベストスコア・最大チェーン・最大コンボ保存つき。

## BGMクレジット

各ゲームのBGMには、OpenGameArt.org で公開されているフリー音源（各ディレクトリの bgm.ogg）を使用しています。

- スネークDX：「Summer Park - 8bit tune (loop)」by Scribe (Daniel Stephens) — CC0 — https://opengameart.org/content/summer-park-8bit-tune-loop
- スターシューター：「RailJet」by Deceased Superior Technician (DST) — CC-BY 3.0 — https://opengameart.org/content/railjet-long-seamless-loop / http://www.nosoapradio.us
- バランスタワー：「Chill lofi inspired [loop edit]」by omfgdude, loop edit by qubodup — CC0 — https://opengameart.org/content/chill-lofi-inspired-loop-edit
- タイミング斬り：「Taiko drums (seamless loop)」by jobro — CC-BY 3.0 — https://opengameart.org/content/taiko-drums-seamless-loop
- まもりの塔：「Tower Defense Theme」by Deceased Superior Technician (DST) — CC0 — https://opengameart.org/content/tower-defense-theme
- ニトロラッシュ：「8-bit - Last Mission」by HydroGene — CC0 — https://opengameart.org/content/8-bit-last-mission
- ブロックラッシュ：「8-bit - Mechanical Complex」by HydroGene — CC0 — https://opengameart.org/content/8-bit-mechanical-complex
- ビートタップ：「8-bit - I am not clumsy!」by HydroGene — CC0 — https://opengameart.org/content/8-bit-i-am-not-clumsy
- カラーチェイン：「8-bit - Slay The Evil」by HydroGene — CC0 — https://opengameart.org/content/8-bit-slay-the-evil
