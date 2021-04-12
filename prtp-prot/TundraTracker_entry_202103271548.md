[f:id:paratap:20210207124956j:plain]

# **Kickstarterでのキャンペーン開始はJST 2021年03月30日午前6:00からです**
[Tundra Trackerのキックスターターページ(予定地)](http://kickstarter.com/projects/tundralabs/tundra-tracker)

##現時点での情報まとめ##

- <a href="#tsuiki">追記</a>
- <a href="#kickstarter_tundra">KickStarterキャンペーン</a>
- <a href="#comparison_vive">VIVEトラッカー(2018)との比較</a>
- <a href="#size">寸法</a>
- <a href="#compatibility_hmd">ヘッドセットとの互換性</a>
- <a href="#tracking">トラッキング方式</a>
- <a href="#baseplate">ベースプレート</a>
- <a href="#multiportdongle">スーパーワイヤレスドングル</a>
- <a href="#support">サポート</a>
- <a href="#manufacturing">製造</a>

## <a id="tsuiki">**追記**</a>

- (2021/03/27追記)
- 「Tundra Trackerの質問に答え続ける会」において出た質問とそれに対する回答

- Q,スーパーワイヤレスドングルはUSB2.0ポートへの接続で動作するか(供給電力は足りるか)
    - A,足りる　USB2.0推奨(USB3.0の場合動作が不安点になる可能性がある) HMDのUSBポートで動作する

- Q,スーパードングルを同じPCで複数同時に使用することは可能か、例えばSW3を2個接続してSteamVRデバイスを合計6個接続できるか
    - A,可能　SW3+SW5で8個接続するなどもできる　ただしSW7を二個以上接続するのはUSB2.0の帯域上できない

- Q,SW5とSW7の数量限定はKickstarterキャンペーン内においてのものか、恒久的なものか
    - A,現状Kickstarter後の販売予定は決まっていない(部品調達が難しいため)

- Q,スーパーワイヤレスドングルに受信しやすい向きはあるか
    - A,特に無い、どの向きでも受信可能

- Q,ヘッドストラップ
    - A,開発にフィードバックする
ボディマウントについてはHaritoraのものが使い回せると思う

- Q,キックスターター分の調達
    - A,大丈夫、すでに始めている
現状製品版のスケジュールは不明
来年のいつ頃になるかもわからない

- Q,何故軽く小さくできたか
    - A,基板を柔らかくして(フレキシブル基板)筐体の内部に折り紙の様に3次元的に折りたたんでいる
さらにセンサー配置を工夫した結果消費電力が低下

- Q,耐久性
    - A,現在サンプルをハードユーザーがテスト中
Tundra Labsではテストが終了
ハードな用途に置いての強度についてはフィードバックします

- Q,シリコンプロテクターの販売予定
    - A,フィードバックします

- Q,ツンドラトラッカーのFoV(視野角)
    - A,おおよそ220度程度
VIVEトラッカーより若干切れやすいかも

- Q,ツンドラトラッカーの向き
    - A,ランプが上、上下左右前後の区別はあるが利用するソフトウェア側の実装次第
現状バーチャルキャストで認識せず

- Q,ツンドラトラッカーのペアリングの手順
    - A,ペアリング手順はVIVEトラッカーと同じ
トラッカーの部位割り当てメニューも同じ

- Q,スーパーワイヤレスドングルの大きさ
    - A,SW3、SW5、SW7で同一の大きさ

- Q,ワンタッチで着脱できるマウントの販売予定
    - A,現状無し

- Q,キックスターター版と製品版の価格について
    - A,製品版と比較して上下するかは分からない

- Q,アイコンはどのように表示されるか
    - A,現在開発中でありSteamVRのウィンドゥ上だとTマークで表示

- Q,アンリアルエンジンでの使用
    - A,プラグインを入れれば可能

- その他
    - トラッカーの生産数が限られており、各セットの注文数に上限は設けていないため早期に出資締め切りの可能性もある
    - ストレッチゴールについては未定
    - ドングルのファームウェアはvalve提供のもの
    - 保障(不良品の交換等)に関しては日本分は日本で交換(Tundragonさんの元に在庫が存在)
    - VIVEトラッカーやIndexコントローラーとのミックス環境でも使用も可能
    - NEOSでの11点トラッキングについては未検証、フィードバックする
    - 設計・開発はTundra Labs、実際の製造は子会社である[N7R](n7r.info)が行う

- (2021/03/21追記)
- [Tundra Trackerデビューまであと少し！Kickstarterは日本時間2021年3月30日（火）午前6時開始です](https://www.tundratracker.com/so/4aNXIkk7R#/main)

- (2021/03/19追記)
- [Hello! I am Tundra Tracker and my birth date is comin'! Kickstarter Launch on Monday, Mar 29th, 2021, CDT 4pm.](https://www.tundratracker.com/so/a4NWyhmsi#/main)
    - JST 2021/03/30-06:00にKickstarterキャンペーン開始
    - 本体重量52g~59g
    - 850mAhのバッテリー
    - 最小約7時間、最大約9時間の稼働が可能
    - ベースプレートはスワップ可能
    - 自分でベースプレートを3Dプリントするため3D/CADデータと設計方法もリリース予定
    - Arduino<del>内蔵</del>付属の開発者版は今日から受け付け開始、4月中旬から出荷予定
    - アーリーバードプランには充電用USBケーブル、キャリングケース、ボディ・脚・リスト/ハンドストラップが付属予定
    - スーパーワイヤレスドングル単品での販売も予定

- [【日本語版】Let's Tundra!](https://www.tundratracker.com/so/95NWhLsIk#/main)
    - アクセサリーは「アーリーバッカー」及び「お買得セット」に無料で付属する予定
    - すべてのTundra Trackerには「ストラップを通す用のベースプレート」と、「1/4インチ ネジをマウントする用のベースプレート」の２つが付属
    - [f:id:paratap:20210315211201p:plain]

- (2021/03/13追記)
- [TenteEEEE てんて-氏](https://note.com/tenteeeeee)によるTundra TrackerとVIVE Tracker 3.0のセンサ配置・トラッキング性能等の考察
    - [3Dモデルで考察するTundra TrackerとVIVE Tracker 3.0｜てんてー｜note](https://note.com/tenteeeeee/n/ndd61a946ed32)

- (2021/03/13追記)
    - [Let's Tundra!](https://www.tundratracker.com/so/e2NWUgkBU#/main)
        - SW5ドングル(最大接続数5)、SW7ドングル(最大接続数7)は数量限定
        - バリエーションと日本円換算での価格(おおよそ)
        - [f:id:paratap:20210313205434p:plain]

- (2021/03/11追記)
    - Super Wireless Dongle(マルチポートドングル)は任意のSteamVRデバイスとペアリングでき、同様にツンドラトラッカー側は任意のSteamVRドングルとペアリングできる[Tundra_Labsツイッターアカウント](https://twitter.com/Tundra_Labs/status/1369832773301714945)より

- (2021/03/10追記)
    - Kickstarterでの受注および発送分に関しては技適取得予定([Tundra_Labs_JPツイッターアカウント](https://twitter.com/Tundra_Labs_JP/status/1369516379838193665)より)

- (2021/03/07追記)
    - 日本語に翻訳されたニュースレターの配信が開始
        - [Tundra Trackerの最新情報＆アンケート実施中！](https://www.tundratracker.com/so/b4NWAzOHl?languageTag=en&cid=83e0604f-f173-4261-8487-8088c6536e77#/main)

- (2021/03/05追記)
    - Tundra Labsの日本語アカウント[Tundra_Labs_JP](https://twitter.com/Tundra_Labs_JP)が開設

- (2021/03/04追記)
    - [Tundra Tracker Community Survey and Updates!](https://www.tundratracker.com/so/deNVvMZH_?languageTag=en#/main)
        - 9月末までにすべてのKickstarterバッカーに発送するという目標に向けて順調に進んでいる(アーリーバッカー向けも同様に進行中)
        - TundraトラッカーDVT-2の開発が進行中
        - ワイヤレスドングルの開発が進行中
        - ツンドラトラッカーコミュニティサーベイが開始

- (2021/03/03追記)
    - Kickstarterでのキャンペーン開始が2021/03/29に決定([公式サイト](https://www.tundratracker.com/)より)

## <a id="kickstarter_tundra">**KickStarterキャンペーン**</a>

- KickStarterキャンペーン期間(2021/02/07時点)
    - 2021/3/29 - 2021/5/28 (暫定)
- Early Backers(早期出資者)向け出荷
    - 2021/06/19 (暫定)
- All Backers(全出資者)向け出荷
    - 2021/09/18 (暫定)

(([Tundra Tracker: Week 04 Update : DVT-1: ~30 Units (Week 01- 07)~](https://www.tundratracker.com/so/0aNRicXQ2?languageTag=en#/main)))

## <a id="comparison_vive">**VIVEトラッカー(2018)との比較**</a>

- 40%小さいサイズ、50%の消費電力と重量、2倍の駆動時間
    - 最小約7時間、最大約9時間の稼働が可能
    - 本体重量52g~59g
    - 850mAhのバッテリー(参考としてVIVEトラッカー2018のバッテリー容量は740mAh)
- Kickstarterキャンペーン時の価格は以下(日本円への換算はおおよその価格)
[f:id:paratap:20210313205434p:plain]

(([Tundra Tracker Aims for Cheaper Alternative to Vive Tracker](https://www.roadtovr.com/tundra-tracker-vive-tracker-alternative-steamvr-tracking/)))

## <a id="size">**寸法**</a>

- DVT-1(Tundraトラッカープロトタイプ)(本体のみ、ベースプレート含まず)
    - 50mm(w) x 50mm(d) x 30mm(h)((https://twitter.com/Tundra_Labs/status/1368635106286575620))

## <a id="compatibility_hmd">**ヘッドセットとの互換性**</a>

- HTC
    - VIVE
    - VIVE Pro
    - VIVE Pro Eye
    - Cosmos Elite
- Valve
    - Index
- Varjo
    - すべてのVarjo製ヘッドセット
- その他
    - XTAL,JVC,StarVRなどのプロ向けHMD

(([What headsets will Tundra Tracker be compatible with?](https://www.tundratracker.com/post/what-headsets-will-tundra-tracker-be-compatible-with)))

## <a id="tracking">**トラッキング方式**</a>

- SteamVR Tracking(Lighthouse) 1.0/2.0
    - ベースステーション1.0/2.0に対応(**動作にはベースステーション1.0もしくは2.0が必須**)(([What Basestations will Tundra Tracker be compatible with?](https://www.tundratracker.com/post/what-basestations-will-tundra-tracker-be-compatible-with)))

## <a id="baseplate">**ベースプレート**</a>

- Tundraトラッカーからの取り外しおよび交換が可能
- Week 04 Update時点でストラップループ型と1/4-20マウント型の二つが予定されている(([Tundra Tracker: Week 04 Update](https://www.tundratracker.com/so/0aNRicXQ2?languageTag=en#/main)))
- 自分でベースプレートを3Dプリントするため3D/CADデータと設計方法もリリース予定

## <a id="multiportdongle">**スーパーワイヤレスドングル**</a>

[f:id:paratap:20210320133213p:plain]

- 単一のUSB接続で複数のトラッカー/SteamVRデバイスとペアリングできるドングル
- それぞれ3つ、5つ、7つのトラッカー/SteamVRデバイスとペアリングできるドングルを計画
- Valve Indexヘッドセットの前面の開口部(別名Frunk)に収まるサイズになる((https://twitter.com/Tundra_Labs/status/1354877080765411335))
- vive pucks(?),Wands(VIVEコントローラー),Knuckles(Indexコントローラー)等任意のSteamVRデバイスに対応((https://twitter.com/Tundra_Labs/status/1368725548814499840))

## <a id="support">**サポート**</a>

- 現時点でのサポート目標は、アメリカ合衆国・カナダ・イギリス・EU・日本・中国(([What Countries will Tundra Tracker Support?](https://www.tundratracker.com/post/what-countries-will-tundra-tracker-support)))

## <a id="manufacturing">**製造**</a>

- PVT(生産検証テスト)用ユニットは2000~3000ユニット製造され、最終的にEarly Backers向けに配送される

- プロトタイプに穴が開いているが
    - 現時点のプロトタイプはMJF3Dプリントで印刷されたプロトタイプ
    - 3Dプリントされたプラスチックの光学特性は射出成型されたものより制御が困難である
    - そのためセンサーの上の材料を取り除いているが、**射出成型されるMP(大量生産)バージョンではセンサーはカバーされる**(([Tundra Tracker Prototype Construction](https://www.tundratracker.com/post/tundra-tracker-prototype-construction)))
