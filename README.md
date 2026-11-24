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
- [フルーツマージ](fruit-merge/index.html) — 物理演算・マージ系パズル。上からフルーツを落とし、同じもの同士をくっつけて進化させる。合体スコアは段階nで n×(n+1)/2×10 点、1.5秒以内の連続合体でコンボ倍率（最大×5）、スイカ完成で+1000点＆10秒FEVER（スコア×2）。デンジャーライン上で3秒静止するとゲームオーバー。ミッション6種、累計スコアで背景テーマ4種を解放、ベストスコア・最大コンボ・スイカ完成数保存つき。
- [メモリーラッシュ](memory-rush/index.html) — 神経衰弱×タイムアタック。裏向きカードを2枚めくって同じ絵柄をそろえる。1ペア100点×コンボ倍率（最大×5）、ミスで制限時間−2秒（Lv1は−1秒）＆コンボリセット、4連続正解でFEVER（8秒間スコア×2）。レベル制（Lv1は4×3・65秒、Lv2以降は必須ペア数×7秒＋10秒）、Lv2からスター（+300点＆+5秒、クリア必須）、Lv3からボム（任意、+200点＆−5秒）。ミッション6種、累計スコアでカードテーマ4種を解放、ベストスコア・到達レベル・最大コンボ保存つき。
- [ブラックジャックバトル](card-battle/index.html) — ブラックジャック対決（2026-11-24に旧「ハイカードバトル」から全面リニューアル）。自分と敵に2枚ずつ配り（敵は1枚伏せ）、ヒット/スタンドで21を目指す。21超えはバーストで即負け、Aは1/11、絵札は10。勝利ダメージは自分の合計（21は30、ブラックジャックは40）、敗北時はバースト10／それ以外max(5, 敵合計−5)。敵HP=40+10×(ラウンド−1)、5ラウンドごとのボスは×1.6。3連勝でFEVER（5ハンド、ダメージ×1.5・スコア×2）。ラウンドクリアでHP+25回復・ボーナス500。ミッション6種、累計スコアでカード裏面テーマ4種を解放、ベストスコア・到達ラウンド・最大連勝保存つき。
- [スカイクライマー](sky-climber/index.html) — 縦スクロール・ジャンプアクション。自動で跳ね続けるキャラをドラッグ／矢印キーで左右に動かし、足場を乗り継いで高く登る。足場は通常・小さい・動く・崩れる・バネ・金の6種。100mごとのレベルアップ（500mの倍数は難所帯）、コイン5連続でFEVER（8秒間スコア×2）、200mからカラスが横切る（当たると跳ね飛ばされる）、風船で落下を1回救済。ミッション6種、累計高度でキャラクター4種を解放、ベスト高度・ベストスコア保存つき。

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
- フルーツマージ：「8-bit - Jester Theme」by HydroGene — CC0 — https://opengameart.org/content/8-bit-jester-theme
- メモリーラッシュ：「Happy Adventure (Loop)」by TinyWorlds — CC0 — https://opengameart.org/content/happy-adventure-loop
- ブラックジャックバトル：「8-bit - Boss Battle」by HydroGene — CC0 — https://opengameart.org/content/zelda-style-8-bit-boss-theme
- スカイクライマー：「8-Bit Explorer Theme」by Sygil — CC-BY 3.0 — https://opengameart.org/content/8-bit-explorer-theme
