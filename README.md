# kintaicsv
出勤・退勤のCSV記録をするためのAutomatorアプリケーション
rubyです

アプリケーションをデスクトップ等に置いて、開くと、
- YYYYMM.csvファイルをユーザー以下に探しに行く（無ければ作る）
- 出勤時間が記録されていない場合は`%Y/%m/%d(日時), %H:%M(出勤時間),`を記録
- されてる場合は`%H:%M(退勤時間)\n`を記録

それだけです。
