## OTAKUcoin 改め UMRcoin

### UMRcoin

UMRcoinはMonacoinのシミュレーターのようなものです。<br>
基本的にMonacoinと同じですがDNS seedサーバーがないため接続ノードを手動で追加する必要があります。<br>
まともに機能させるためにはUPnP設定をONにして8ノードぐらいは追加すべきでしょう。<br>
採掘の検証回数は101回なので採掘したコインが使えるようになるまでに自分を含めて更に100回の検証(採掘)が必要です。<br>
Ubuntu example)<br>
　$ umrcoind -daemon -upnp<br>
　$ umrcoin-cli addnode 133.130.66.167 add<br>
　（133.130.66.167はコンパイル用サーバーを兼ねています）
```markdown
Algorithm: Lyra2RE(v2)
Block time: 1.5 minutes
Block reward: 50 UMR(August 2017)
105,120,000 total coins
Subsidy halves every 1051k blocks (~3 years)
Difficulty re-target: every block (Dark Gravity Wave v3)
not premined
P2P Port: 9441
RPC Port: 9442
```

ダウンロードはこちらです→ [Download](https://github.com/umarucoin/umrcoin/releases).<br>
マイニングツールはこちらです→ [Mining Tool](https://www.umaru-coin.com/).<br>
ソースコード→ [Source code](https://github.com/umarucoin/umrcoin).<br>
Blockchain Explorer→ [Powered by RPC Ace](http://v133-130-66-167.myvps.jp:25252/blockexplorer.php)<br>
Monacoinも当たるおまけサイト→ [しがないどころか丸出しノーセキュリティーfaucet](http://v133-130-66-167.myvps.jp:25252/node.php).<br>

### 概要

<b>"待"ってたぜェ！！ この"瞬間"をよォ！！</b><br>
<s>UMRcoin</s>一条武丸サンは一条グループの御曹司として魍魎の勢力拡大に尽力し、<br>
私立聖蘭高校に自由の学風を築くために多大な功績を残した人です。<br>
どうかこの武丸サンを怒らせないで下さい。

### Support or Contact

under construction.<br>
2chスレッド→ [橋本環奈「ごめーん！環奈今日唐揚げのレモン買うの忘れたけん代わりにオシッコかけたとよー！」@仮想通貨板](https://fate.2ch.net/test/read.cgi/cryptocoin/1499216178/l50)
