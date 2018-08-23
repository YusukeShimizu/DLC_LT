
## Discreet Log Contracts

Bitcoinのスマートコントラクト

---
### 自己紹介
- - -

現在 : SI(有休消化)  
9/3  : メルペイ

---

### LIT

MIT DCIのBitcoinのライトニングネットワーク。  
SPV nodeで動く。

![](https://github.com/mit-dci/lit/raw/master/litlogo145.png)  
![](https://camo.githubusercontent.com/1fd1fa6c7c9b22f3b2414a6e4af2b53d26a6d286/687474703a2f2f6875627269732e6d656469612e6d69742e6564753a383038302f6a6f622f6c69742d50522f62616467652f69636f6e)


>>>

### Discreet Log Contracts

* LITで動くスマコン
* 2 of 3 の契約
* 当事者間にしかコントラクトの存在は見えない  
(Oracleにも見えない)

>>>

### Bitcoinのスマコン

![](./img/positions.png)

---

### デモシナリオ

* YusukeとMikiが付き合ったのでスマコン
* 一年後、Yusukeは振られる方に賭ける
* Mikiは逆
* 案の定、Yusukeは振られる
* Oracleは仲介だったDaichi

>>>

![](./img/smacon.png)

>>>

失恋の価値は0.8BTC程度でしたか・・・

---

### Oracleへの秘匿化

今回のシナリオではわかりづらいけど、Oracleは二人の契約の存在は認知していない。  
Schnorr署名応用で実現しているけど研究レベル。

---

ご静聴ありがとうございました。  
@bruwbird


![](https://avatars1.githubusercontent.com/u/3435121?s=460&v=4)

---

### Apendix

![](./img/terminal.png)

>>>

![](./img/terminal2.png)
