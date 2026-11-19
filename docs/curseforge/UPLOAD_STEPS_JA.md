# CurseForgeアップロード手順

このZIPは提出準備用です。CurseForgeのMODファイル欄にはZIP全体ではなく、同梱のaerocannons-v2026.11.19-15.jarを指定します。前提MODは同梱していません。

1. https://authors.curseforge.com/ へログインし、Minecraft → Create a Project → Modsへ進む。
2. PROJECT_FIELDS.jsonのName・Summaryを入力。アイコンはmedia/icon-400.png（400x400）。名前とslugの重複は実際の作成画面で確認する。
3. PROJECT_DESCRIPTION.mdを掲載文として使用。英語を先に、日本語を後に記載済み。外部のJARダウンロードリンクは掲載しない。
4. ライセンスは現在のAll Rights Reservedを選ぶ。元のテンプレートのMIT表記は別途保持済み。
5. ソース・不具合報告リンクはGitHubを指定する。
6. FilesからJARを選び、Minecraft 1.21.1 / NeoForge / Betaを設定。CHANGELOG.mdを変更履歴へ入力する。
7. Related Projectsには必要なCreate / CBC / Aeronautics / TFMG等を設定。SableがAeronauticsの配布ファイルに含まれる構成かも確認する。任意連携をすべて必須扱いにはしない。
8. 新画像のゲーム内スクリーンショットと、最小構成のクライアント起動を追加確認する。プレビューシートをゲーム画面として扱わない。
9. 確認後に提出。審査承認までは公開完了ではありません。

初回Betaは試験用の選択です。公式案内ではCurseForgeアプリの通常同期には少なくとも1個のReleaseファイルが必要です。未検証のままReleaseと誤記しないでください。

現在の状態：未アップロード。画面操作ツールが「failed to write kernel assets: 指定されたパスが見つかりません。(os error 3)」で起動せず、ログイン状態・プロジェクト作成画面を確認できませんでした。本番サーバー・参加用インスタンスは更新していません。

公式手順：https://support.curseforge.com/support/solutions/articles/9000197241-creating-and-submitting-a-project
