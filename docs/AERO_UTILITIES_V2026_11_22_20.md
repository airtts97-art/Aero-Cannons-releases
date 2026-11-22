# 額縁・Interiors大型座席の許可（v2026.11.22-20）

試合用スケマティックの許可タグに minecraft:item_frame と interiors:big_seat を追加します。interiors:bigseat も任意の互換IDとして収録し、そのIDが存在する環境だけで有効になります。Interiorsがない環境でもタグを読み込めます。既存の接着剤などの許可は維持します。

JARはv2026.11.22-18のままで使えます。これは設計図内のエンティティの許可データパックで、手持ちアイテムの許可リストや防具立てなど他のエンティティは変更しません。

ZIPを展開せず使用中ワールドのdatapacksへ置き、OPで /datapack list available の後に /datapack enable "file/aerocannons-match-utilities-v2026.11.22-20.zip" を実行してください。v19の額縁パックが有効なままでも重複による問題はありません。

本番でinteriors:big_seatのタグ読み込みと設計図審査を確認済みです。既存の接着剤の許可と、防具立ての禁止も確認しました。存在しない互換IDの実体生成試験は行っていません。
