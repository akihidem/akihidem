# akihidem

高校で物理を教え、公認心理師でもあります。放課後に一人で、半年で 182 の repo を作りました。51 本が今月も動いています。夜のあいだは AI が 30 本余りを進め、朝に報告が 1 本届きます。その全部を、ひとつの決まりで回しています。AI の自己採点は証拠に数えない。
I teach high-school physics and hold a national license as a Certified Public Psychologist. After hours, alone, I built 182 repos in six months; 51 of them are still moving this month. At night an AI advances thirty of them and sends me one report by morning. All of it runs under one rule: an AI's self-report is not evidence.

## 数字

- repo 182（2026 年 4 月から。公開 27）、commit 5,261、この 30 日で手を入れた repo 51
- 1 日で 118 commit（紙に書いた物を撮ると AI が決めた反応で返す道具）、7 日で 332 commit（紙の口座で測ってから作る売買 bot）
- Claude Code の運用系を自作: skill 50、hook 18 種、cron 89、1 事実 1 ファイルの記憶 500 余り

## 外に出ている物

- [kizashi](https://kizashi-tawny.vercel.app): 11 のミニゲームで 12 の指標を測る適性検査。本番稼働、85 tests + E2E
- [式神リーグ](https://haifu.vercel.app): 見た目はカード対戦のゲーム、中身は実在する LLM の配置を測るベンチ
- [kokoro-mcp](https://github.com/akihidem/kokoro-mcp): 公認心理師の見立てを AI が読める形に翻訳する規格 KOKORO の配信サーバ。[npm](https://www.npmjs.com/package/kokoro-mcp) 公開。KOKORO で科研費に応募済み（2026 年 9 月）
- 60fps の VJ（1960 年代のリキッドライトショーを物理シミュレーションで再現。DJ イベントへ納品予定）、Playdate のゲーム 2 本、訪日客向け天気チャンネルの毎日の台本（9 月から無人で生成）

## ほかに居ない組み合わせ

- AI だけの組織に相転移があることを測り、接地の臨界量 g* = 0.225 を出し、それを次の道具の合否判定に使った。[souteni](https://github.com/akihidem/souteni) → [yoriai](https://github.com/akihidem/yoriai) → [gama](https://github.com/akihidem/gama)
- 30 本余りの repo を夜に進める番頭と、設計 → 並列実装 → 別系統の検品を回し続ける開発基盤を自作し、AWS 2 台と Mac と手元の WSL に複数のモデルを配って動かしている。公開版の部品: [claude-headless-via-tui](https://github.com/akihidem/claude-headless-via-tui)・[tehai-core](https://github.com/akihidem/tehai-core)・[loop-kit](https://github.com/akihidem/loop-kit)・[loop-verify](https://github.com/akihidem/loop-verify)
- この自己紹介は、4 つの AI に自分の 154 repo を互いを知らずに読ませ、原文との一字一句の照合を通った軸だけから起こした。6 月の版と手順: [tebanare](https://tebanare-web.vercel.app)

## 流儀

- 任せる範囲は、合否が機械で決まる検査で決める。合否は作った側でなく別の系統のモデルが言う
- 取り消せない操作（送信・発注・公開・本番の変更）は、方針で止めるのでなく、経路をコードに持たせない
- うまくいかなかった結果は消さない。自作の売買戦略を正直な費用で棄却した再現研究を、そのまま置いている。[subspace-pca-leadlag](https://github.com/akihidem/subspace-pca-leadlag)・[lead-lag-pca-review](https://github.com/akihidem/lead-lag-pca-review)
- 他者を名乗らず、診断や心の中を書かない。実在の人のデータは外へ出さない。[your-own-mod](https://github.com/akihidem/your-own-mod)・[jibun-kit](https://github.com/akihidem/jibun-kit)

GitHub: [github.com/akihidem](https://github.com/akihidem) ・ note: [note.com/docsfirst](https://note.com/docsfirst)
