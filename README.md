### Rozhovor o LAN
```diff
- Prvně si řekneme něco o LAN.. hmm..
- Tak začenem tím, že jeho rozsah může být místnost, podlaží, budova... no prostě to je síť která zabírá menší plochu.
+ Lokální sít... No to je vlastně všechno co je mi lokální, poblíž ne?
- Přesně tak! V tom malým rozsahu máš třeba kompl, tiskárnu a mnoho dalších zařízení. 
- A právě lan všechny tyto tvoje zařízení v malém rozsahu propojuje.
+ Aha! Takže LAN propojuje všechny počítači v naší učebně a v kancelářích například tiskárny!
- Dneska ti to nějak pálí!! Je to přesně jak jsi řekl!
- Dále zmíním že zařížení v síti LAN se kdykoliv mohou spojit s ostatními zařízenímy v této LAN síti.
+ Mohou se kdykoliv spojit... OK, to dává smysl!
- Jistě, v LAN síti tomu tak je, ale ve WAN síti tomu tak není.
- To jest hlavní rozdíl, dále poskytuje vetší rychlost a kvalitu spojení.
+ Poskytuje větší rychlost.. No a co je myšleno tou rychlostí?
- No... Asi nejlepší vysvětlení by bylo:"kolik dat může poslat najednou, jakou max. velikost může najednou poslat"
+ Ahaaaa.
+ Dobře. chápu! No a co ta vysoká kvalita přenosu?
- Tím slovem "kvalita" je myšlena "Přesnost, správnost dat".
- Tím pádem čím větší kvalita přenosu, tím mín dostanem ERRORŮ!
- Data vlastně kolují jako elektrický signály uvnitř kabelů, ale i tak když voláme přes pevnou linku tak 
- někdy kvalita hovoru stojí za hovno a blbě ho slyšíme.
+ Jo to je pravda.. U pevný linky koluje v jeho kabelu elektřina..
+ Taky je pravda že někdy u volání dochází k nějakému rušení a hlas druhé osoby zeslábne a skoro ho nejde slyšet..
-Ano! A protože LAN je na krátkou vzdálenost, tak vznik takové chyby se stává jen zřídka.
```
### Rozhovor o WAN
```diff
- No dobře, teď tak nějak víš co to ta LAN je.
- Další na řadě je řeč o WAN!
+ To bude logicky nějaká širší síťová oblast, která bude spojovat různé LAN sítě.
- Přesně tak! 
- Jako příklad takove WANky by jsme si mohli uvést třeba toto:
- Máme nějakou společnost, která se rozhléhá po celé republice.
- Máme hlavní kancelář v Praze, a jednu další v Ostravě.
- Ostravák chce, aby se dostal do databáze kancéláře v Praze.
+ Takže dvě síťe si chcou vyměnovat data...
- Přesně tak, ty náš chytráku!
- Zkráceně, LAN síť v naši kanceláři v Praze a Ostravská LAN síť se nějak potřebují spojit.
+ tsss :P
- V takové situaci se jedna LAN s druhou LAN spojí pomocí WANu.
+ Spojí? Jak se sakra mohou spojit?
+ To je budeme spojovat kabelem jako u dvou počítačů v LAN síti?
- Kabelem se sice spojí, ale ne vlastním.
- K tomuto použijeme už položený kabel nějakým providerem, poskytovatelem připojení.
+ Aha, takže to je například ten STARNET nebo T-MOBILE o kterých tak často slýchám..
- Ano, takže bychom mohli říct, že si od těchto providerů "půjčíme","nájmeme" kabely pro náš přenos.
+ Hmmm, pujčím si kabel od providera a pošlu přes něj data.. 
+ To už začíná znít jako ten internet kterej znám.
- No vlastně bych mohl říct, že i samotnej INTERNET je WAN.
- V předchozím příkladě to bylo z Ostravy do Prahy, Internet spojuje LANky po celém světě.
+ ???
+ Muj počítač se na internet připojit umí i když nemá LANku ??
- ... Spíš by jsi měl o tom přemýšlet jako že tvůj počítač je LAN síť o jednom zařízení.
- Trochu o tom popřemýšli, a pak pochopíš že to není zas tak šílená myšlenka.
+ "šílená myšlenka"...
- Možná by ti pomohl tento bláznivý výrok:
- "Provider tě nespojí s okolím, ve skutečnosti se staneš součástí jedné velké lanky samotného providera!". 
- No ve skutečnosti to tedy jedna velká LAN není ale..
+ " šílená myšlenka"...
- Furt jen šilená myšlenka? Je to skutečnost, ale to je jedno.
- To je obecně řečeno charakteristika WANu. 
- Prvně si prostě musíš pronajmout kabel.
- U LANu si všechny kabely zařizuješ a propojuješ sám na sebe, u WANu musíš platit poplatky providerovi...
+ ..Já mám doma nepřetržité připojení takže jsem připojenej 24/7.
- AAaa, v dnešní době jsou takové připojení častá, např. ISDN nebo ADSL...
- Většina společností má nepřetržité připojení...
- No a pro lidi jako jsi ty, má WAN určitě také nepřetržité připojení.
+ Ano, to jsi zmínil u vysvětlení LAN, 「LAN dokáže být vždy připojen」.. Souhlasím!
- Hm.. Mimoto, ISDN má normálně nejvyšší rychlost 128Kb/s. ADSL má 8Mb/s.
- Když použijeme optickej kabel tak výjímečně dosáhneme vysokých rychlostí, ale v zásadě je WAN pomalejší než LAN.
+ To je pravda.. Ve školní LANce se data na sousedícím PC objeví instantně, ale školní internet je strašne pomalej..
- Ve srovnání s minulostí se situace zlepšila, ale i tak je WAN linka více náchylná na výskyt chyb než je LAN.
+ Hm. Hm.
+ Takže když to shrneme tak porovnání LAN a WAN může vypadat takto:
```
![porovnani](porovnani.png)
