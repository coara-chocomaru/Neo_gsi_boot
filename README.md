# TAB-A05-BD
## チャレンジパッドNeo用 gsi_boot
### 手動リカバリ起動以外は通常bootします。


- Q.1 gsi_bootってなに？
- A.1 recoveryとbootを一つにしたNeo用のbootです
- Q.2 どうやって使うの？
- A.2 fastbootでrecoveryに焼いてgsi起動などで使います。
- Q.3 なんでこんなのをgsi起動で使うの？
- A.3 Neoはboot検証を回避できない為recoveryからgsiを起動する必要があるからです。

## 注意事項
- otaは使えません(文鎮回避)
- gsiなどの起動でのみご利用ください。
