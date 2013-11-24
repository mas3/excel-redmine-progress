進捗資料
==========

RedmineのチケットCSVから進捗資料を作るシートです。

使い方
-------

1. Redmineのチケット画面からCSVでチケットをエクスポートしてください。エクスポート設定では「すべての項目」を選んでください
2. エクスポートしたデータを[データ]シートに貼り付けてください。最初に入っているサンプルデータは上書きして削除してしまって構いません
3. [進捗]シートの「集計日付」にデータをエクスポートした日付を入れてください

前提条件
----------

- チケット作成時に「予定工数」を入れてください
- 作業したら作業時間を記録してください
- 「進捗 %」も更新してください。チケットのステータスと連動して自動で算出するようにするのがお勧めです
- チケットの親子関係には対応していません

余談
-----

Excelでやっていた進捗管理をRedmineでやる場合の一番の問題はExcelじゃないことだったりするので、内部用にはRedmineを使い、報告用にExcelを使うというやり方もあると思います。
