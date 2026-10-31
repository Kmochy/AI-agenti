# Lekce 02 - přepis

- **Zdroj:** `2-AI Agenti 2.pdf`
- **Rozsah:** všech 90 stran PDF, časové značky od 00:12 do 03:05:27.
- **Způsob převodu:** doslovný přepis textové vrstvy PDF bez jazykových oprav, zkracování a doplňování. Zachovány jsou časové značky, jména mluvčích, původní znění i zalomení řádků. Členění podle stran a ohraničení textových bloků jsou doplněny pouze pro formátování Markdownu. Přepis nebyl ověřován proti audiozáznamu.

## Strana PDF 01

```text
00:12 - 00:13
Lukáš Kellerstein: Tak, dobrý večer.
00:14 - 00:15
pvojacek: Dobrý večer.
00:16 - 00:17
Lukáš B: Dobrý večer.
00:18 - 00:19
Lukáš Kellerstein: Dobrý večer.
00:19 - 00:20
Ing. Ivan Kostolný: Pozdravujem.
00:22 - 00:23
Ondřej Tomášek: Dobrý den.
00:24 - 00:24
Karel Vaclavik: Tričko.
00:26 - 00:27
maria: Pěkný Večer všetky.
00:31 - 00:33
Lukáš Kellerstein: Tak tak já vás všechny zdravím.
00:33 - 00:36
Lukáš Kellerstein: Ještě mám tady za úkol dvě věci. Musím si nastavit.
00:36 - 00:37
Martin Slanař: Řešíme.
00:38 - 00:40
Lukáš Kellerstein: Dobrý den, abyste to dobře viděli.
00:42 - 00:43
Lukáš Kellerstein: Tak hotovo.
00:49 - 00:54
Lukáš Kellerstein: A eště mi tady. Zbejvá vám nakopírovat zdrojáky jako mytnout je
00:56 - 01:00
Lukáš Kellerstein: Takže To bude ještě jedna věc, kterou udělám. A pak už se na to
vrhneme.
01:04 - 01:07
Lukáš Kellerstein: Eh, a langenglishinitialhginitial.
01:08 - 01:09
Lukáš Kellerstein: My jsme pětka,
01:13 - 01:16
Lukáš Kellerstein: tak máme tady nula jedna.
01:18 - 01:26
Lukáš Kellerstein: A dneska nám tady přibyde nula. Dva initialmcpinitial. Takže kopírovat
01:29 - 01:30
Lukáš Kellerstein: vložit.
01:34 - 01:36
Lukáš Kellerstein: Teda chviličku. Počkám, až se, to tam nakopíruje
```

## Strana PDF 02

```text
01:47 - 01:49
Lukáš Kellerstein: kometnuto a vlítneme na to
01:54 - 01:56
Lukáš Kellerstein: tak vypadá to, že se to nakopírovalo.
01:59 - 02:08
Lukáš Kellerstein: Git status get ad gitcomit message initialcpinitial. Tak už
02:10 - 02:13
Lukáš Kellerstein: měli byste to mít v repozitáři, takže si to můžete stáhnout.
02:14 - 02:23
Lukáš Kellerstein: Zdrojový kódy, abyste se na ně případně mohli koukat se mnou.
Pokuď byste měli zájem delít.
02:25 - 02:32
Lukáš Kellerstein: Zavřu všechny, Jo, Wafer All, Ne,
02:36 - 02:49
Lukáš Kellerstein: takže to bych měl připravený. Prezentaci mám taky připravenou Tady,
jdeme na to pro Browser. U.
02:50 - 02:51
Lukáš Kellerstein: Výborně,
02:56 - 03:03
Lukáš Kellerstein: Tak se ještě tady tak Jdeme na to sdílet obrazovku. Celou obrazovku
sdílet.
03:03 - 03:05
Lukáš Kellerstein: Tak Měli byste ji vědět.
03:07 - 03:19
Lukáš Kellerstein: Výborně, Tak, eh, doufám, že jste nebo že jsem vysvětlil minulou
hodinu dostatečně. Eh, vlastně Tool Calling. A
03:19 - 03:29
Lukáš Kellerstein: to jak funguje vlastně agent uvnitř? To bylo vlastně cílem minulý
hodiny ukázat ten základní stavební kámen
03:32 - 03:34
Lukáš Kellerstein: Neboli ehlminitial Langenglishinitialapiinitiallangenglish.
03:35 - 03:44
Lukáš Kellerstein: A vlastně vysvětlit na tom princip Tool Calling U. A proč je to tak
důležitý? A že vlastně, bez toho Tool Calling. U by žádný agenti nevznikli.
03:45 - 04:03
Lukáš Kellerstein: A že ať se to možná nezdálo na začátku tak důležitý, tak jako tak, si
umí vybrat ňákej tůl. Ten to není zas tak převratný. Tak díky tomu lhpu. Vlastně jsme si
ukázali, že to, eh, nabejvá, nebo nabylo na důležitosti
04:04 - 04:09
Lukáš Kellerstein: a že Vlastně, jako podobně. Já. Když jsem to viděl poprvý, tak jsem si
vlastně řek
04:11 - 04:17
Lukáš Kellerstein: tak. Jsem zamydlenej protože, vlastně já jsem vývojář já, Jsem
developer. A co já dělám
```

## Strana PDF 03

```text
04:17 - 04:30
Lukáš Kellerstein: já, Defakto. Když to hodně zjednoduším a úplně odprostím se vod
ňákýho toho že, znám architektury a paterny A Takovýdle věci tak víceméně. Když
vyvíjíte, tak děláte.
04:30 - 04:45
Lukáš Kellerstein: Eh, takový tři věci Dokola Napíšete kód, pustíte kód, vopravíte kód,
napíšete kód, pustíte kód Vopravíte kód. A to je todle tydle tři věci. Když já vlastně, kde
jsem schopnej teďkon díky tomu tool Calling u
04:46 - 04:50
Lukáš Kellerstein: dát vlastně do ňákýho Lupu a. Teď To si napíše kód teda.
04:51 - 04:55
Lukáš Kellerstein: Tak díky tool. U. Si teda je schopný opustit ten kód
04:56 - 05:07
Lukáš Kellerstein: a pak si vopraví ten kód a. A. Jo, A zase si pustí ten opravenej kód. Tak
todle, když se vlastně dá do lupu, tak sem si říkal, No tak teď je teď už teď. Už se vlastně
05:08 - 05:14
Lukáš Kellerstein: teď už je jedno, jak dlouho von ten kód bude psát, protože to se
Neustále bude zlepšovat a optimalizovat.
05:15 - 05:26
Lukáš Kellerstein: To znamená, že už jenom to, že jsem viděl, že napíše ten kód a bude
schopnej tam dojít i Kdyby jednoduchej kód a piškvorky psal měsíc, Bylo to. Mi to
vlastně v hlavě úplně jedno.
05:27 - 05:35
Lukáš Kellerstein: Tak jsem si říkal, No tak, za za Půl roku to zkrátí na na půl měsíce, pak
na tejden, pak na hodinu, pak na za tři minuty.
05:35 - 05:40
Lukáš Kellerstein: Jo a samozřejmě, ten progress Byl mnohem rychlejší. Takže už jenom
tadydle ten lup. Prostě
05:41 - 05:57
Lukáš Kellerstein: týdle tý práce tý opravy a tak byl hrozně pro mě důležitej a díky Tomu
mě to vodevřelo oči. A já jsem díky tomu začal vlastně fungovat a zajímat se mnohem
víc. Vo ty a agenty do tý doby sem se zabýval. Spíš vlastně
05:58 - 06:03
Lukáš Kellerstein: vo modely, jako takový. A jak se trénujou a jak fungujou vevnitř a tak
dále,
06:04 - 06:10
Lukáš Kellerstein: Takže to by Byl úkol první hodiny vysvětlit si ten loup a ten Tool
Usage.
06:10 - 06:19
Lukáš Kellerstein: Dneska na to navážeme a představíme si standard, kterej se pro tůl
Kol, nebo pro tůly jako takový
06:19 - 06:39
Lukáš Kellerstein: eh, používá. Protože my jsme si ukázali, že pro nás byly vlastně túly.
Ten předpis byl stejnej. Ten Byl danej a potom jsme tam měli tu naši implementaci. Ty
dvě funkce tu vrať mi akcie. Get stock price a get dividend date Takže tydle ty dvě byly
naimplementovaný v tom pythonu.
```

## Strana PDF 04

```text
06:39 - 06:50
Lukáš Kellerstein: No a teď si vysvětlíme že todle to se používalo po nějakou dobu a
působilo to Ňáký problémy takže. Se jako v antropiku Jednou rozhodli tak. Todle Bysme
měli vyřešit
06:51 - 06:52
Lukáš Kellerstein: a přišli tadydle S tim
06:53 - 07:10
Lukáš Kellerstein: standardem Kterej neptejte se mě, Proč se jmenuje Model Kontext?
Protokol Absolutně. Tomu nerozumim. Nepřijde mi, že by to mělo ňákej význam jako,
přijde Mi tak, Kdyby vzali tři Random slova a dali je dohromady a udělali z toho
standard. Jo, mohlo se to jmenovat úplně jinak, Takže
07:10 - 07:16
Lukáš Kellerstein: nevím. Jaká je analogie Zatím slovíčkařením Tady Initialmcpinitial,
model kontext, protokol.
07:17 - 07:22
Lukáš Kellerstein: Ale tak se to prostě jmenuje, Takže to tak berte a teď si vysvětlíme, vo
čem to je v dnešní hodině.
07:23 - 07:28
Lukáš Kellerstein: Máme tady původní prezentaci, kterou já jsem používal v minulejch
kurzech. Ale,
07:29 - 07:44
Lukáš Kellerstein: eh, snažím se ty kurzy dycky vylepšovat jak Mám čas Takže zrovna
tady. Pro tu hodinu jsem nám tady připravil, eh, novou prezentaci, která je mnohem víc
animovaná a. A vysvětluje to Témas bych řek mnohem líp
07:45 - 07:49
Lukáš Kellerstein: souvisí. To i s tím že, initialmcpinitial vyšlo teďkon ve verzi dva
07:50 - 07:55
Lukáš Kellerstein: takže. Si vysvětlíme jak, je rozdíl mezi tou verzí jedna a verzí dva. A že
to je vlastně
07:56 - 08:06
Lukáš Kellerstein: Breaking Change. Je to přelomová změna. To znamená, že zase si
ukážeme vysvětlíme Proč, Takže tady máte tu prezentaci? Novou Je teda v
Initialpdfinitial ku
08:07 - 08:12
Lukáš Kellerstein: Já už tím, jak jsou kódovací agenti a tím, jak prostě
08:13 - 08:20
Lukáš Kellerstein: celý Ten svět se mění přizpůsobuje tomu, co ty eh, korvovací agenti
umožňujou. Tak já už dneska
08:21 - 08:27
Lukáš Kellerstein: považuju vlastně Word dokument Powerpoint prezentaci
08:28 - 08:34
Lukáš Kellerstein: a skoro bych se nebál říct ekcelovskou tabulku za takový už přežitý
formáty.
```

## Strana PDF 05

```text
08:35 - 08:46
Lukáš Kellerstein: Takže samozřejmě jsem si vědomej toho, že ve spoustě firmách se to
pořád stále používá a nějakou dobu ještě používat bude. Nicméně, třeba prezentace. Už
mi přijde, že dneska je výhodnější dělat.
08:47 - 08:57
Lukáš Kellerstein: Takže ta prezentace vznikla jako Initialhtmlinitial prezentace.
Doporučuju i vám dělat prezentace v Initialhtmlinitial pomocí korvacích agentů.
08:57 - 09:02
Lukáš Kellerstein: Když bude čas, tak si můžeme ňákej takovejdle příklad ukázat já to
Mám celej den kurz. Tak jenom
09:03 - 09:20
Lukáš Kellerstein: když už vo tom mluvim tak, abych vám možná taky někdy ukázal
takže. Pokud budete chtít klidně, napište Do toho, chat U. Chci ukázat tady
maloprezentace pomocí kórovacích Agentů. A když tam bude dostatek lajků tak já tomu
ňákej čas dedikuju v Nějaký hodině, kde třeba si najdeme ňákej čas
09:21 - 09:22
Lukáš Kellerstein: nebo. V tý poslední
09:23 - 09:35
Lukáš Kellerstein: tak. To znamená proč. Tady celý říkám že, tady je sice nahraný
Initialpdfinitial Ko. Protože tenhle ten webová aplikace mi umožňuje nahrávat
prezentaci jenom v Initialpdfinitial ku nicméně Já vám budu ukazovat tu prezentaci tady
09:36 - 09:43
Lukáš Kellerstein: a Ta prezentace tady v týdle tý hezčí podobě s těma animacema je a
máte jí k dispozici. V těch v tom kódu
09:44 - 09:47
Lukáš Kellerstein: to znamená, že tadydle, když se podíváme na dnešní hodinu,
09:47 - 09:58
Lukáš Kellerstein: Zase pro ty z vás, co jsme byli minule třeba. Já? Jsem v jinym
repozitáři, kde Mám víc verzí tohodle kurzu a mám tady všechny ty hodiny. Takže se
nedivte, že vy to v tom repozitáři nevidíte,
09:58 - 10:10
Lukáš Kellerstein: Každopádně tudle složku, Tak jak jí tady mám? Já tu sem teďko
nakopíroval k vám do toho reportáře a komitnul. To bylo na tom začátku, takže tam
Musíte vidět to samý, co já tady vidim teďkom nebo co? Ukazuju dneska.
10:10 - 10:19
Lukáš Kellerstein: A tady je verze jedna. Verze dva. To je verze, o tom si budeme taky
povídat, Ale v tý verzi dva. Máte tady složku prezentace.
10:20 - 10:26
Lukáš Kellerstein: A tady je ta prezentace v tom initialhtmlinitial takže todle, To když si
vodevřete v prohlížeči,
10:27 - 10:29
Lukáš Kellerstein: tak uvidíte to samý, Co já
```

## Strana PDF 06

```text
10:30 - 10:41
Lukáš Kellerstein: Eště. Než začnu s toudle tou hodinou, byl tady dotaz, eh, v Diskortu.
Eh, za kterej děkuju. Protože mi tam bylo vlastně upozorněno.
10:41 - 10:59
Lukáš Kellerstein: Že Já tady používám Langenglishinitialideinitiallangenglish který
vlastně není úplně standardní a já už se omlouvám, já už jsem na to prostě zvyklej.
Takže já. Už to neberu moc jako novotu, takže. Ale chápu, že pro spoustu z vás třeba i
ty, co mají zkušenosti s programováním, Tak
10:59 - 11:02
Lukáš Kellerstein: se můžete divit, Co to tady. Co to tady ten Lukáš má?
11:03 - 11:12
Lukáš Kellerstein: Takže jenom Proto bych chtěl říct eště tady takhle na hodině, že
Všechny ty materiály, to Repo, Ten repozitář, kterej máte
11:12 - 11:19
Lukáš Kellerstein: tady a i a G Tady pět. Jo, já si to tady votevřu. V Ňáký Nový
11:21 - 11:27
Lukáš Kellerstein: teď. Se musim podívat sedmnáct. K udělám. Novou plochu
11:29 - 11:33
Lukáš Kellerstein: tady. Si to dávám Na Tady si dám třeba dvojku
11:35 - 11:52
Lukáš Kellerstein: Tak bych chtěl jenom ukázat. Jenomže. A G. Já pracuju hodně v telmi v
terminálu, Jo, takže já Jdu toudle tou cestou a otevřu si ty zdrojáky. Klidně ve
initialvsinitial kódu. Vyžuju studio kód. To bych doporučoval i vám na začátek
11:52 - 12:06
Lukáš Kellerstein: nebo Na začátek pro ty z vás tedy začínají, tak určitě bych
doporučoval ten initialvsinitial kód. I pravděpodobně spousta. Z vás ten initialvsinitial
kód používá Pokud nepoužíváte Jet Brains nebo ňáký další alternativy
12:07 - 12:17
Lukáš Kellerstein: který, sou třeba spíš pro ten váš primární programovací jazyk jako
java pravděpodobně má. Nějaký svoje Já si pamatuju Eklips a takovýdle různý
Langenglishinitialideinitiallangenglish.
12:18 - 12:28
Lukáš Kellerstein: Nicméně, studio Code bych doporučoval jako většině já. Jsem ho
používal dlouhý léta když, jsem potřeboval Něco víc Light wait, než byl tehdy
12:29 - 12:44
Lukáš Kellerstein: Eh, visual studio. Jako to Full visual Studio? Ne, tady to visual. Studio
kód. To bylo takový Lightweight Todle je vhodný na všechny programovací jazyky, takže
to doporučuju. V tom si bohatě. Vystačíte se všema hodinama, co my tady budeme
dělat,
12:45 - 12:51
Lukáš Kellerstein: Eh, eště abych to neodvíral jenom z toho terminálu. Tak samozřejmě,
přes ten finder si to najdete taky.
```

## Strana PDF 07

```text
12:52 - 12:56
Lukáš Kellerstein: Klikněte si pravý tlačítko tady a otevřít
12:57 - 13:04
Lukáš Kellerstein: někde tady. Takhle jsem to tady viděl. A nebo to tam takhle
přetáhnete do toho a máte to tam
13:06 - 13:07
Lukáš Kellerstein: tak, eh.
13:08 - 13:16
Lukáš Kellerstein: Proč já Používám něco jinýho. Takže jenom ve zkratce, Eh, začínalo
jako velmi Light Wait, Eh,
13:17 - 13:27
Lukáš Kellerstein: Langenglishinitialideinitiallangenglish prostředí ve kterém, eh, se
vyvíjí int Interactive Development Experience. Jestli si dobře pamatuju tu zkratku.
13:28 - 13:29
Lukáš Kellerstein: No,
13:30 - 13:50
Lukáš Kellerstein: eh, ale začlo to bobtnat. To znamená, že čím má čím dál tím víc věcí se
do toho navaluje. A už to žere hrozně. Vlastně jako paměti zdrojů. To znamená, já.
Povětšinou mám. Jak tady vidíte, všechny ty plochy tady Takhle nahoře, tady v pra vlevo.
Tak to sou všechny. Vlastně moje plochy, který tady mám. Ty barevný Mám takhle
barevně odlišený
13:50 - 13:53
Lukáš Kellerstein: Mám jich Tady Většinou otevřenejch třeba. Dvacet
13:53 - 14:08
Lukáš Kellerstein: na každý tý ploše zhruba tak. Běží nějaký ňákej projekt vodevřenej v
ňákym langenglishinitialideinitiallangenglish Jako Je Initialvsinitial kód tak K tomu ještě
běží nějakej kódovací agent vedle toho. A teď je pokuď initialvsinitial. Kód mi zabírá.
Třeba Giga Giga jeden.
14:09 - 14:15
Lukáš Kellerstein: Tak si vemte, že já jich mám otevřených dvacet. Tak mi to bere.
Dvacet giga pamětí úplně zbytečně.
14:15 - 14:19
Lukáš Kellerstein: Takže já jsem potřeboval něco lehčího. Něco Zase víc Lightweight.
14:20 - 14:23
Lukáš Kellerstein: To znamená, že já jsem přešel na Laisivym
14:24 - 14:40
Lukáš Kellerstein: tady Takže zase pro ty z vás. Jenom tady tomu budu věnovat ani, Ne
třicet vteřin. Takže tady je lasiv Wim, což je terminál v terminálu Se Otevře takovýdle.
Langenglishinitialidinitiallangenglish, který je velmi podobný tomu initialvsinitial kódu,
Já to Mám i nastylovaný, aby to mělo stejný barvičky.
14:41 - 14:51
Lukáš Kellerstein: Takže pak tady mám takhle vlevo, jakoby zase tu adresářovou
strukturu, jakou máte vy a pokuď si otevřu tady nějakej kód, Tak ho tady prostě zase
vidím v těch barvičkách. Jo,
```

## Strana PDF 08

```text
14:52 - 14:56
Lukáš Kellerstein: takže to je jenom to, co používám já, abyste se tomu nedivili.
14:56 - 15:11
Lukáš Kellerstein: Hodně studentů se často i ptá. Co to tady mám za ty Za tady ty cesty.
A co to používám za Terminál a takovýdle věci. Takže zase Kdyby to někoho z vás
zajímalo, napište to. Klidně do toho chat U, Zajímá mě to, na konci hodiny vám to můžu
ukázat.
15:11 - 15:15
Lukáš Kellerstein: Jenom si myslím, že do týhle tý regulérní hodiny to úplně teďko
nepatří.
15:16 - 15:25
Lukáš Kellerstein: Tak eh, to, znamená, Budu ukazovat prezentaci. Teda v tý anima
animovaný podobě. Protože se mi to bude líp na tom vysvětlovat.
15:25 - 15:30
Lukáš Kellerstein: Dostupnou ji Máte, eh, v lekci je teda Ta initialpdinitial varianta.
15:33 - 15:37
Lukáš Kellerstein: Jo, to jsem navázal Na to, co používáme pro za prostředí. A ještě tam
byla.
15:40 - 15:47
Lukáš Kellerstein: Jo, jedna otázka ohledně initialmcpinitiallangenglish, Na kterou bych
chtěl dneska odpovědět. To je tadydle ta od Luboše.
15:48 - 15:57
Lukáš Kellerstein: Takže tomu se budu chtít věnovat eh, V, průběhu tý pre tý hodiny
Dnešní bych měl na spoustu těch věcí odpovědět.
15:58 - 16:08
Lukáš Kellerstein: A Luboši, Pokuď by se stalo, že na kterou tu věc neodpovím, nebo jo,
tak já se budu snažit. Já si takhle dycky tady dávám nějakou botičku nebo autíčko,
16:09 - 16:15
Lukáš Kellerstein: Tak bych se k tomu měl chtít vrátit. Minulou hodinu jsem si uvědomil,
že jsem se nevrátil k těm otázkám.
16:15 - 16:19
Lukáš Kellerstein: Takže jsem se snažil na ně odpovědět po hodině.
16:19 - 16:30
Lukáš Kellerstein: Nicméně, eh, budu se snažit dneska Dávat větší pozor a udržet si v
paměti že, se chci dycky vrátit tady na ty otázky a reagovat na ně nebo na ně Minimálně
na konci hodně zodpovědět.
16:30 - 16:40
Lukáš Kellerstein: Minule toho bylo hrozně moc, Takže jsme přetahovali, Takže sem už
vám chtěl dát pokoj, abyste měli volnej večer, Takže budu se snažit k nim vracet,
16:41 - 16:51
Lukáš Kellerstein: kdyby náhodou. Ne. Klidně se nebojte to napsat jednou nebo dvakrát.
Ne, jako já se nebudu urážet, že mi tam někdo s tím votravuje. Rozhodně mě
nevotravujete.
```

## Strana PDF 09

```text
16:53 - 17:10
Lukáš Kellerstein: Tak pojďme teda začít prezentací. To znamená, proč to vlastně vzniklo
a co to je. A k čemu nám to vlastně jako pomáhá? Takže, Říkal jsem, jmenuje se to
Model Context protokol. Přišlo to vod antropiků a dneska Už je to vlastně standart,
Nebo Voni to předali?
17:15 - 17:17
Lukáš Kellerstein: Eh, Jáj. Foundation
17:20 - 17:37
Lukáš Kellerstein: Agentic. Ai Foundation. To je ten to uskupení vlastně který sdružuje
open Standardy pro agentický initialaiinitial. Je to teda vlastně neziskovka. Nebo Já
nevím, jestli to mám takhle úplně nazvat, stejně jako je Linux Foundation Jo,
17:38 - 17:42
Lukáš Kellerstein: Tak je vlastně Foundation Teďkon. A ta zdržuje všechny tyhle ty,
17:43 - 17:49
Lukáš Kellerstein: eh, věci ohledně agentur. Takže i initialmcpinitial, i když to vzniklo
vlastně
17:50 - 17:58
Lukáš Kellerstein: u Antropiku. Tak si to ale převzala tadydle ta nadace nebo
Foundation. Já nevím, jak to mám nazvat teďkon
17:58 - 18:14
Lukáš Kellerstein: a ta teda Si Vzala pod křídla. I některý další. Vlastně projekty. Takže
tadydle konfigurace pro kódovací agenty. Jaký to má pod sebou? Teďkom Má pod sebou
ten, eh, model kontext, protokol.
18:15 - 18:29
Lukáš Kellerstein: A teďkon si eště tady vzali, o který já jsem, eh, nemluvil minule, ale
hezky to navazuje. Minulou hodinu jsme si ukazovali Gateway. A říkali jsme si Light
Llminitial. To je ta naše initialiinitial Gateway.
18:30 - 18:35
Lukáš Kellerstein: Není to samozřejmě jediná Aia, i když já bych vám doporučoval začít s
toudle,
18:36 - 18:48
Lukáš Kellerstein: protože nejpřívětivější, má tam nejvíc uživatelskej jako
Langenglishinitialuaj prvků Hezký je to všechno vidět v tom initialuiinitial, ale pokuď
budete třeba pracovat na Enterprise Ňákym Eh,
18:49 - 19:02
Lukáš Kellerstein: Projektu, kde, pro vás bude kritický Aby, to bylo škálovatelný a tak
dále tak, budete používat envoy Třeba, jako Eia Gateway. Anebo teďkon sem byl na
Open source summitu tady v Praze, na vyšehradě
19:03 - 19:10
Lukáš Kellerstein: a tam se probírala i tadydle ta agent Gateway, Takže, vypadá to, že to
je jako v tom světě
19:10 - 19:16
Lukáš Kellerstein: tadydle. To by měla bejt jako taky velmi dobrá agentní Gateway. Těch
Gates budete nacházet víc, takže.
```

## Strana PDF 10

```text
19:17 - 19:25
Lukáš Kellerstein: Ne, nemám. Eh, Nemám pocit, že by jich bylo málo. Jenom jsem chtěl
to profiltrovat,
19:25 - 19:31
Lukáš Kellerstein: Tak pak je tady ještě agent, to agent. Vo tom budeme mluvit. A pak je
tady ještě agent Router. Takže
19:31 - 19:42
Lukáš Kellerstein: spoustu těch projektů se začalo sdružovat podle tou pod touhle Tou
Foundation. A ta se teďkon stará i vo Ten model kontext protokol. Takže jenom říkám,
vzniklo to fantropiku, ale
19:42 - 19:53
Lukáš Kellerstein: už je to někde Jinde. Budeme tady mít takovejch sedm sekcí, který by
nám měli pomoct to vysvětlit. Takže proč Initialmcpinitiallangenglish? Potom, co se
změnilo v initialmcpinitiallangenglish jedna A dva.
19:53 - 20:06
Lukáš Kellerstein: Je to hlavně důležitý z toho, že budete nacházet a narážet na
spoustuinitial server ů a na spoustu implementací initialmcpinitial serverů tak, Abyste
věděli ten rozdíl a uměli se v tom rychle orientovat.
20:07 - 20:14
Lukáš Kellerstein: Tak potom, jak je to zapojený. Potom si ukážeme, co vlastně v tom
Langenglishinitialmcpinitiallangenglish serveru je. A Potom si ukážeme
20:15 - 20:19
Lukáš Kellerstein: tři způsoby, jak se dneska ten initialmcpinitial server ve verzi dva píše.
20:20 - 20:26
Lukáš Kellerstein: A potom si ukážeme ještě Autorizaci, autentikaci, Jenom tak zrychleně
a potom migraci.
20:27 - 20:28
Lukáš Kellerstein: Tak co je dobré? Langenglishinitialmcpinitiallangenglish.
20:30 - 20:45
Lukáš Kellerstein: Teď si představme že máme agenta, nebo že si píšeme takovýdle
Agenty jako sme si ukázali v tu první Hodinu Představte si, že mám takovýdleho agenta
na support, že mám takovýdleho agenta na nějaký vnitropodnikový, Eh,
20:46 - 21:00
Lukáš Kellerstein: Věci typu jako marketingový oddělení. Má svýho agenta. Pak dejme
tomu právní oddělení. Má nějakýho svýho agenta. Účetní oddělení má svýho agenta
ven, Teda co jakoby já popl po. Mm,
21:01 - 21:05
Lukáš Kellerstein: co já publikuju? Ne, exposuju. Co já vlastně
21:06 - 21:24
Lukáš Kellerstein: poskytuju ven. Eh, jako agenta z mý firmy ven zákazníkům, tak je
většinou ňákej ten support. Agent jo. Nebo. Prodejní, agent nebo něco takovýho ať si
Představte že v, tý firmě jich máte Prostě dejme tomu. Nevim pět, nebo jich máte prostě
víc.
```

## Strana PDF 11

```text
21:25 - 21:29
Lukáš Kellerstein: A teď každej ten agent vlastně má jako ten svůj tůl,
21:30 - 21:48
Lukáš Kellerstein: Jo, a teď si představte, že ty agenti, jak jsem říkal, minule většinou
jako chcete aby, ty agenti teda minimálně, si uměli šáhnout do nějaký databáze aby, si
uměli teda něco najít na internetu, případně. A aby si případně v některejch případech
uměli třeba napsat kód. Jo,
21:49 - 21:57
Lukáš Kellerstein: tak teď tady máme Vlastně tůly jako na Github na postgres. Na slek,
jo. Samozřejmě. Chcete, aby s váma ňák komunikovali takže, Třeba
21:57 - 22:16
Lukáš Kellerstein: napojete na ňákej slek je Taky rozhodně dobrá. Eh, dobrej, Eh, dobrá
schopnost. Potom, aby uměli ovládat file systém Takže si číst soubory vodněkuď psát
někam do souborů já. Nevím, Google Drive. Ňákej. Share Point A tak dále
22:16 - 22:22
Lukáš Kellerstein: no. Teď, si vemte že, pro každýho toho agenta vlastně tydle ty tůly
jako máte Takhle Jako napsaný,
22:23 - 22:30
Lukáš Kellerstein: tak je úplně ta nejhorší varianta. Samozřejmě, je, že budete mít tu
implementaci toho agenta a u toho agenta budete mít Všechny ty funkce.
22:32 - 22:42
Lukáš Kellerstein: Může se to můžete se to snažit, Eh, vlastně, přepoužít to, že to
znamená, že si vytvoříte ňákou knihovnu a tu Těm agentům pak teda jako
22:43 - 22:46
Lukáš Kellerstein: poskytujete. To by bylo rozhodně lepší řešení
22:47 - 22:56
Lukáš Kellerstein: nicméně. Pořád, tady máte to že, ten agent referencuje tu knihovnu
která, mi sdružuje tydle ty tůly. Takže přece jenom
22:57 - 23:14
Lukáš Kellerstein: ten agent. Stejně pořád má ňákou jako verzi tý knihovny proč. To
říkám když, si takhle Vynásobíme pět vlastně agentů, ať už to jsou i aplikace, který
vlastně budete používat, nebo ty vaši zaměstnanci budou používat vnitřně v tý síti Nebo
v tý firmě.
23:14 - 23:19
Lukáš Kellerstein: Tak, A máte tady nějaký tůly? Tak je to prostě třeba pět krát pět takže.
Se to násobí
23:19 - 23:26
Lukáš Kellerstein: důležitý Je Tady ta násobnost teďkon Takže je. To dvacet pět zhruba
jako propojení Tímhle tím způsobem,
23:27 - 23:35
Lukáš Kellerstein: co initialmcpinitial, dělá, je, že to, že řekli, ne, Takhle se to teda už
nedá zvládat řekneme. Si hned proč. Se to nedá zvládat
```

## Strana PDF 12

```text
23:35 - 23:46
Lukáš Kellerstein: a. Místo toho uděláme takovej ten klasickej klient server To znamená,
že tu architekturu client server. To znamená, Místo toho, aby ty body byly připojený
napřímo
23:47 - 23:49
Lukáš Kellerstein: ňáký pýr tu. Peer Konexe
23:49 - 24:05
Lukáš Kellerstein: tak. Uděláme server a budeme. Ty agenti si budou dotazovat toho
serveru. A ten server pro nás bude sdružovat všechny tydlety tůly. Jo, to znamená, že V
tom případě máme už těch konexí. Pět plus pět
24:05 - 24:07
Lukáš Kellerstein: a ne pět krát pět
24:07 - 24:17
Lukáš Kellerstein: a. Je tady prostě míň konexí a eště verzování Bude Velkej topik. To si
ukážeme hned na delším slide u Jenom abysme pochopili, co to
Langenglishinitialmcpinitiallangenglish. Vlastně je
24:18 - 24:26
Lukáš Kellerstein: tak si řekneme a úplně Pro zjednodušení. Úplně jednoduše, že jestliže
víme, co je Langenglishinitialapiinitiallangenglish Server.
24:27 - 24:30
Lukáš Kellerstein: A co nám poskytuje Langenglishinitialapiinitiallangenglish. Server.
24:31 - 24:43
Lukáš Kellerstein: Tak si Vlastně můžeme říct, že initialmcpinitial Server je vlastně
initialapiinitial server. Ale pro agenty Jo, to znamená, eh.
24:44 - 24:48
Lukáš Kellerstein: Tak Todlen to tu myšlenku nechám na pozdější slide,
24:49 - 24:55
Lukáš Kellerstein: to, znamená, že Pokuď máme takovej počet agentů, jako je tady. Jo,
24:56 - 25:00
Lukáš Kellerstein: a teď máme takovejdle počet Tůlů Vidíte, jak se mi to mění,
25:01 - 25:16
Lukáš Kellerstein: Tak se jenom Koukejte, jaký číslo je tady to. Je bez toho
initialmcpinitial a. Jaký pak číslo je tady jo takže? Jenom, Aby, jenom z hlediska počtu
Vlastně těch udržovanejch konexí. Je. To je to nebo prostě
25:16 - 25:25
Lukáš Kellerstein: kombinací? Takhle Tak je to, eh, řádově úplně někde jinde takže, to by
bylo Úplně jako důvod
25:27 - 25:32
Lukáš Kellerstein: Důležitej důvod. Ne za mě. Ten úplně nejdůležitější. Takže, pojďme se
podívat dál.
25:32 - 25:39
Lukáš Kellerstein: Druhej důvod, kterej já považuju za ten nejdůležitější A proč Třeba mě
se to hrozně líbilo je, že
```

## Strana PDF 13

```text
25:40 - 25:56
Lukáš Kellerstein: verzování pro mě byl hroznej problém. To znamená, že si představte,
že máte jednoho agenta. Dva agenty, tři agenty a máte tři tůly. Dobrý, to je to. To
zvládnete. Managovat Jo, to se zvládnete managovat Jakmile ale máte těch agentů.
Dvacet
25:56 - 25:57
Lukáš Kellerstein: o třicet.
25:58 - 26:00
Lukáš Kellerstein: Teď případně máte ňáký klienty
26:01 - 26:18
Lukáš Kellerstein: nebo projekty v tý firmě a. Teď tenhle ten projekt má tyhle agenty
támhle Ten tydle agenty, Tydle. A teď najednou máte tituly Najednou. Je problém si
vůbec vzpamatovat, kterej ten agent používá Jakej initialmcpinitial tool a v Jaký verzi?
26:19 - 26:33
Lukáš Kellerstein: A teď je hroznej problém. Vlastně, jakoby když změnim jednu verzi
jako knihovny nebo toho toolu, představme si tady, že Github jsem Upgrade Oval z
verze jedna, dva. Jak to tady vidíte, že všichni mají stejnou verzi,
26:33 - 26:53
Lukáš Kellerstein: Tak jsem najednou vydal. Teď pomiňme to, že Github Má oficiální
initialmcpinitial server. Ale Řekněme že, sem si napsal svůj vlastní tak, jsem si ho vydal
ve verzi jedna tři, a teď musím jít do každýho toho agenta. A v každým Tom agentovi
vlastně jako upgrade ovat tu verzi
26:54 - 26:55
Lukáš Kellerstein: a přenasadit toho agenta
26:56 - 27:04
Lukáš Kellerstein: protože jenom proto, že Jsem upgrade Oval jednu jednu verzi. Vlastně
nebo něco jsem upgrade oval v Tool, u kterej ten agent používá
27:05 - 27:20
Lukáš Kellerstein: A teď, samozřejmě se mi Stane, že některý a teď já třeba nebudu
majitelem nebo zodpovědnej za všechny ty agenty. Budu ten šéf v tý firmě nebo ten
Early Adopter budu já. Ten, kterej bude jako
27:20 - 27:28
Lukáš Kellerstein: oversajtovat ty projekty a budu říkat hele. Tak, teď jsme tady s týmem
udělali novou upgrade toho Tool u Všichni si to upgrade.
27:28 - 27:35
Lukáš Kellerstein: Upgrade ujte. A teď, víte, jak to chodí. Každej má svoje priority. Někdo
to udělá, někdo to neudělá, No a pak se nám stane,
27:35 - 27:44
Lukáš Kellerstein: že takovýdle upgrade y budeme dělat. A nakonec budeme mít
nekonzistenci v těch agentech úplně napříč celejma těma projektama. Všema Těma,
27:45 - 28:03
Lukáš Kellerstein: eh, různejma typama. Protože každej si bude. Někde si to update Ne,
někdy si to neupdejt, Ne a tak dále, Takže Samozřejmě, Řešení, by bylo pro tendle ten
mez pro tendle ten. Vlastně problém by bylo aspoň vydávat nebo mít ty tůly jako jednu
knihovnu
```

## Strana PDF 14

```text
28:03 - 28:16
Lukáš Kellerstein: A pak teda jako vydávat upgrade tý knihovny, ve který sou upgrade
ovaný všechny ty tůly. Takže aspoň byste jako donutili, ale teď by nám zase přišel
problém, že každej ten agent
28:17 - 28:20
Lukáš Kellerstein: by moh mít různou verzi
28:21 - 28:29
Lukáš Kellerstein: tý knihovny, kterou bysme jako vydávali. Takže Řešení pro nás je že
právě tady mezi to takhle strčíme ten server.
28:30 - 28:38
Lukáš Kellerstein: A teď všichni ty agenti vlastně budou používat ten initialmcpinitial.
Server.
28:39 - 28:43
Lukáš Kellerstein: Ten initialmcpinitial Server je Nasazenej vlastně jako
langenglishinitialapiinitiallangenglish.
28:43 - 28:50
Lukáš Kellerstein: Takže pokud já něco změním vlastně v tý verzi, tak se to všichni to maj
vlastně hned.
28:51 - 28:53
Lukáš Kellerstein: Jo, protože to Nadeplojuju,
28:54 - 29:01
Lukáš Kellerstein: Eh, ten server. A vlastně, všichni to hned začnou používat. Nemusej ty
klienti vlastně dělat nic
29:02 - 29:14
Lukáš Kellerstein: Teďkon, eh, Stejně jako u Langenglishinitialapiinitiallangenglish platí
Stejná věc, že? Pokud tam nasadím, samozřejmě něco, co jsem rozbil, tak to
samozřejmě tím pádem ovlivní všechny. Jo, takže zase
29:15 - 29:21
Lukáš Kellerstein: musíte si samozřejmě dávat pozor. Pokuď tam. Nasadíte něco
rozbitýho, Tak jste zase to rozbili Všem.
29:21 - 29:24
Lukáš Kellerstein: Můžete to nasazovat? Zase genery deployment
29:24 - 29:43
Lukáš Kellerstein: typu. Nasadím to tam budu držet vobě ty verze, tu novou i tu starou.
A teďkon padesát procent lidí. Přehodím na tu novou, a budu sledovat, jestli jsem něco
Rozbil nebo nerozbil padesát procent. Pořád budu chodit na tu starou verzi a pak to pře
překlopim. Všechno to stejně Platí jako u Langenglishinitialapiinitiallangenglish,
29:44 - 29:46
Lukáš Kellerstein: Všechny tydlety, vlastně triky a typy.
29:48 - 29:48
Lukáš Kellerstein: Tak,
29:49 - 30:07
Lukáš Kellerstein: eh, proč teda nepoužíváme čistý Langenglishinitialhttinitial. Když tady
říkám, že to je vlastně Langenglishinitialapiinitiallangenglish ale pro agenty, Tak co to
vlastně znamená? To pro agenty? Tak, eh, až si budem ukazovat implementaci, tak se
ukážeme, že langenglishinitialmcpinitiallangenglish Server má
```

## Strana PDF 15

```text
30:08 - 30:14
Lukáš Kellerstein: vlastně jenom Dvě metody, dva end point y de facto. Dalo by se říct v
tý terminologii. Langenglishinitialapiinitiallangenglish
30:15 - 30:16
Lukáš Kellerstein: a jeden je.
30:17 - 30:24
Lukáš Kellerstein: Vrať mi list všech tůlů A druhé je. Zavolej tůl.
30:24 - 30:30
Lukáš Kellerstein: To znamená. Nefunguje to. A není to tak, Jak byste si asi představovali
u toho? Langenglishinitialapiinitiallangenglish že k Slash
30:31 - 30:41
Lukáš Kellerstein: Github. Jo, nebo Slash Postgres. Slash slek. Ne, tak to nefunguje. Je to
vlastně jenom dva end Point Y, který sou, eh, k tomu Přizpůsobený
30:42 - 30:54
Lukáš Kellerstein: a zároveň i ten protokolition, kterej se k tomu používá. Ale Ve
výsledku se to stejně obaluje do Fast Langenglishinitialapiinitiallangenglish, třeba v
Pythonu
30:55 - 31:06
Lukáš Kellerstein: Takže vono to vlastně jako je Langenglishinitialapiinitiallangenglish.
Ale má to svoje standardy, svoje svoje pravidla, Takže není správný a není dobrý,
vlastně i ten Initialmcpinitiallangenglish.
31:07 - 31:22
Lukáš Kellerstein: To, co se vidím hodně dneska, že není dobrý. Jakoby mít
Langenglishinitialapiinitiallangenglish v tý firmě a teď si říct no tak dobře, tak Já
Potřebuju vlastně to samý dát tomu agentovi. Tak vlastně, jakoby tak vobalíte to.
Langenglishinitialapiinitiallangenglish. Tim Langenglishinitialmcpinitiallangenglish a
Vystavíte to tomu agentovi
31:23 - 31:30
Lukáš Kellerstein: to není Úplně správný řešení a. Eh zase, budem se vo tom bavit i v
průběhu kurzu trochu víc dál
31:31 - 31:35
Lukáš Kellerstein: takže. Proč ne eště Langenglishinitialtpainitiallangenglish Tak, Je to
ten standard.
31:37 - 31:52
Lukáš Kellerstein: Tak todle to přeskočím. Protože k tomu k tomu ještě potřebujete
vědět. Eh, Transform způsoby pro Langenglishinitialmcpinitiallangenglish a todle to
jsem říkal todle, když rozbiju jednu věc, tak rozbiju vlastně všechno.
31:52 - 32:10
Lukáš Kellerstein: Takže co si můžete představit, že
Langenglishinitialmcpinitiallangenglish je takový usbcinitial port pro A aplikace. Takže
místo toho, aby každej měl vlastní konektor a každej ten agent se připojoval tím túlem
jakoby jiným konektorem Thunderball nebo ten druhej O teplu
```

## Strana PDF 16

```text
32:11 - 32:17
Lukáš Kellerstein: a initialusbinitial. A initialusbinitial. Nebo jak to je initialusbinitial C,
Ne, usbcinitial.
32:19 - 32:24
Lukáš Kellerstein: Teď mi to úplně sem se zmátnul sám sebe, ale Víte co, co tím chci říct?
32:25 - 32:30
Lukáš Kellerstein: Initialusbinitial pro agenty nebo aplikace.
32:31 - 32:37
Lukáš Kellerstein: Tak je to otevřenej protokol a poskytuje to a teď já si myslím, že
tadydle budu mít,
32:39 - 32:40
Lukáš Kellerstein: Tak na to ještě bude slight,
32:41 - 32:47
Lukáš Kellerstein: Eh, je to otevřenej protokol a poskytuje to tři věci. Ten server který
může Vlastně jsou
32:48 - 32:57
Lukáš Kellerstein: poskytovaný a konzumovaný z toho serveru. První je Thuli. A když se
budete bavit s kýmkoliv, o tak vám říkám, že na Devadesát
32:58 - 33:08
Lukáš Kellerstein: devět procent Eh, bude mluvit vo tůlech. Takže
Langenglishinitialmcpinitiallangenglish servery poskytujou prostě touly
33:08 - 33:11
Lukáš Kellerstein: a to bude to ví devadesát devět procent lidí
33:11 - 33:22
Lukáš Kellerstein: pak Je menší procento lidí který vědí, že to poskytuje i další dva jiný
objekty. Jedno je data a druhý jsou prompt y, Zase si Ukážeme,
33:23 - 33:29
Lukáš Kellerstein: eh, Tran nebo zprávy jsou jako Langenglishinitialginitiallangenglish
Jason Langenglishinitialrpcinitiallangenglish
33:29 - 33:46
Lukáš Kellerstein: je to teda Jason Request a respons, Můžete si ho tím pádem přečíst
začalo To v Antropicu. V roce na konci dvacet. Dvacet, čtyři a vod. Dvacet dvacet pět. To
vlastně patří tou Agentic Ai Foundation, jak jsem vám ukazoval tu stránku.
33:46 - 33:54
Lukáš Kellerstein: Je to teda votevřená specifikace a otevřený initialsdkinitial. Co to teda
znamená? Má to normálně na
33:55 - 34:06
Lukáš Kellerstein: všechny ty zdrojáky k Tomu Takže to najdete. Na. My se ještě k tomu
řekneme něco víc co, Ten všechno obsahuje ale, To to vlastně ve výsledku znamená
34:07 - 34:12
Lukáš Kellerstein: Adaptovali to teda všichni napříč celou tou komunitou.
34:14 - 34:18
Lukáš Kellerstein: I když se tomu, eh, ze začátku jako
```

## Strana PDF 17

```text
34:19 - 34:22
Lukáš Kellerstein: nechtělo respektive bych řek že,
langenglishinitialmcpinitiallangenglish
34:23 - 34:29
Lukáš Kellerstein: eh, hned Jak to vyšlo, tak to vlastně lidi pochopili, k čemu to je a proč
je to tak důležitý?
34:29 - 34:31
Lukáš Kellerstein: Takže to všichni začali adaptovat,
34:32 - 34:38
Lukáš Kellerstein: třeba Kromě jáj jo, Opene, Jay, Tim, že to vyšlo Vod toho antropiku a
voni sou prostě
34:39 - 34:55
Lukáš Kellerstein: Jing a Jang a a černý a bílý A prostě ty protipóly de facto by se dalo říct
tak voni to strašně dlouho, ne? Jako nechtěli vůbec uznávat a i přemejšleli a Viděl jsem
nějaký, že chtěli mít vlastní tendle. Ten jakoby
34:55 - 35:05
Lukáš Kellerstein: protokol A standard jenomže tak rychle. To ta komunika komunita
adaptovala jako vopravdu, tak Strašně rychle. Tam tady bylo jedno takový období.
35:06 - 35:21
Lukáš Kellerstein: Asi dvou tří měsíců, kdy nikdo nedělal nic jinýho pomalu, než sepsali
initialmcpinitial servery na všechno, Takže, eh, to stejný. Vlastně tak tak rychle se to
rozšířilo tou komunitou, že nebylo vůbec šance, aby. Jako by tady přišla nějaká
alternativa k tomu,
35:21 - 35:34
Lukáš Kellerstein: takže i v dnešní době je to akceptuje a, eh, používá. Všichni ostatní s
tím neměli Zas takovej problém, a normálně se nám to naomboard ovali a. A používaj
to.
35:34 - 35:41
Lukáš Kellerstein: Eh, akorát je problém. Ještě to nebudu říkat tak. Eh, Tak
35:42 - 35:47
Lukáš Kellerstein: teď sou tady tři role Je tady host, klient a server. Protože je to právě
ten klient. Server,
35:48 - 36:10
Lukáš Kellerstein: tak si umíme představit tadydle ty dvě slovíčka, klient a server, Stejně
jako máme v normálněm Langenglishinitialitinitiallangenglish. Nebo to, co vy znáte?
Když máte webovej prohlížeč, napíšete tam Urla adresu Tak vy jste ten klient, Vy máte
ten klientskej webovej prohlížeč a pak i ňákej server a. Když napíšete tu roll adresu tak,
vlastně to přistane na tom serveru
36:11 - 36:16
Lukáš Kellerstein: Ten server vám vrátí tu stránku do toho vašeho prohlížeče.
36:17 - 36:27
Lukáš Kellerstein: Jo, a ta vám jí vyrendruje. Takže to je klient Celebr, Jo a, eh, Pak tady
máme host. To znamená kde? Vlastně jako to běží? To znamená, že
```

## Strana PDF 18

```text
36:28 - 36:44
Lukáš Kellerstein: máme tady. Máme tady ňáký initiallm ko A teďkon tady Máme Teda,
Initiallm. Ko Používá initialmcpinitial servery. Takže Řekněme že, todle všechno běží na
tom vašem lokálním počítači řekněme dejme tomu. Že používáte to Lokální initiallm Ko.
36:44 - 36:51
Lukáš Kellerstein: Tady máte ňákej projekt kterej, tady máme eh, V, rámci tut v rámci
kurzu
36:51 - 36:54
Lukáš Kellerstein: a budete tady mít initialmcpinitial klienta
36:55 - 37:00
Lukáš Kellerstein: a Ten initialmcpinitial. Klient se bude připojovat na initialmcpinitial
server.
37:01 - 37:12
Lukáš Kellerstein: Jenomže aby to nebylo tak jednoduchý, tak initialmcpinitial poskytuje
tři typy nebo teď Pardon, abych Vám to nesložiťoval. Tak dva typy,
37:13 - 37:15
Lukáš Kellerstein: Eh, připojení do toho serveru.
37:15 - 37:25
Lukáš Kellerstein: Eh, to ovlivňuje i to. Kde ten server vlastně běží nebo neovlivňuje,
Doslova Může to ovlivňovat.
37:26 - 37:29
Lukáš Kellerstein: Ono vlastně ovlivňuje. Ale hned vám vysvětlím, proč jsem se takhle u
toho zasekl.
37:30 - 37:42
Lukáš Kellerstein: První je Dioinitial, a to znamená, že, Eh, ten server tedle a Tedle běží
na stejným počítači, jako je
37:45 - 37:55
Lukáš Kellerstein: tady modrej jako je ten host. Takže todle běží všechno vlastně na
stejným počítači, kdežto
37:56 - 37:59
Lukáš Kellerstein: tadydle v tom druhym případě Stream a byl
Langenglishinitialhttpinitiallangenglish.
38:00 - 38:12
Lukáš Kellerstein: Tady vlastně tendle ten initialmcpinitial server běží jinde než tadydle
ten zbytek.
38:13 - 38:20
Lukáš Kellerstein: Jo, takže to ten to slovíčko server vlastně platí jenom proto,
38:21 - 38:23
Lukáš Kellerstein: když použijete to Stream Able langenglishinitialhttpinitiallangenglish
38:25 - 38:29
Lukáš Kellerstein: jakmile použijete transform transportní způsob initialsdinitial
38:31 - 38:33
Lukáš Kellerstein: tak Tam to vlastně neplatí, Protože
```

## Strana PDF 19

```text
38:34 - 38:38
Lukáš Kellerstein: ten server nemá initialipinitial adresu. Nemá port.
38:39 - 38:45
Lukáš Kellerstein: Vlastně se jakoby běží to jenom interproces
38:46 - 38:50
Lukáš Kellerstein: pro toho klienta, to znamená, že ten file server je vlastně jenom
script.
38:52 - 39:08
Lukáš Kellerstein: A tenhle. Ten initialmcpinitial. Klient si ten skript pustí jako pod
proces, to znamená, že jestli Rozumíte tomu, jak fungujou procesy? Já si pustím nějakou
aplikaci a ta si otevře proces. Ta mi běží jako jeden proces, třeba na procesoru
39:09 - 39:21
Lukáš Kellerstein: A Teďkon, ten kód, kterej běží v tom procesu, si může po pouštět pod
procesy, který mu patřej. Jsou To je parent a má podprocesy. A teďkon ty podprocesy.
39:22 - 39:28
Lukáš Kellerstein: My zajišťujou věci. Jakože se mi randruje hezky a funguje a animuje,
39:28 - 39:49
Lukáš Kellerstein: když já třeba na něco kliknu a Tam se děje ňáká Jiná úloha která, by
mohla vlastně třeba brzdit to rendování jo. Nebo, různý takovýdle věci eh, Který, by mi
mohly Působit komplikaci, který já můžu offload ovat a vlastně nechat je běžet a v tom
hlavním procesu vlastně dělat něco jinýho,
39:49 - 40:03
Lukáš Kellerstein: tak tadydle on si pustí ten server jako podproces a pak s nim skrz
procesovou komunikaci. Vlastně komunikujeme. Komunikujou mezi sebou, takže tenhle
mu posílá nějakej úkol, Tendle mu na to odpovídá. Jo, takže je to vlastně interproces,
40:04 - 40:11
Lukáš Kellerstein: kdežto tajdle ten stream mobil eště
langenglishinitialtpinitiallangenglish. To je jedinej způsob, kdy tendle Ten server
opravdu má.
40:12 - 40:26
Lukáš Kellerstein: Tak tenhle. Ten server vopravdu má jako initialipinitial adresu. Má
port a teď samozřejmě záleží, jestli to běží teda na lokál hostů. Tak pak jsou teda voba
dva. Vlastně na stejným počítači. A nebo to běží vlastně na, ehm,
40:27 - 40:30
Lukáš Kellerstein: Todle to běží jinde, než Běží prostě todle to.
40:30 - 40:33
Lukáš Kellerstein: A v tom případě to má jinou initialipinitial adresu.
40:34 - 40:38
Lukáš Kellerstein: Tak hned si ukážeme i v kódu, jak to jako vypadá, Jak se to liší?
40:39 - 40:41
Lukáš Kellerstein: Jde mi hlavně Vo to, abyste pochopili ty principy.
40:42 - 40:45
Lukáš Kellerstein: Tak todle to sem teda řek
```

## Strana PDF 20

```text
40:47 - 40:52
Lukáš Kellerstein: tak. A teďkon Co, nabízí Teda, ten server. Já už jsem to popisoval. Sou
to túly.
40:53 - 40:59
Lukáš Kellerstein: Jsou to resource y data a sou to prompty
41:00 - 41:07
Lukáš Kellerstein: a teďkon, jak jsem Říkal devadesát devět procent lidí. Prostě, Když se
bude bavit, tak se bude bavit jenom o tulech. A vlastně
41:09 - 41:28
Lukáš Kellerstein: todle to vůbec neznaj nebo nevědí. A todle to taky nevědí. Vono to
trochu vychází z toho, že tydle ty dvě věci jsou míň podporovaný těma kódovacíma
agentama, Těma agentama, který už někdo napsal, než Vlastně tadydle ty tůly. Ale vono
se to tak jako trochu mění, takže Vono, Časem se to možná víc adaptuje.
41:29 - 41:33
Lukáš Kellerstein: Tak to znamená, když si to představíme. Jako, co to teda je?
41:33 - 41:41
Lukáš Kellerstein: Tak tůly jsou vlastně funkce. Takže to už jsme si Ukazovali, eh, Gestalk
Price get dividend Date
41:42 - 41:50
Lukáš Kellerstein: Resource Y jsou vlastně jako soubory. Bych to tak si dovolil říct.
41:51 - 42:04
Lukáš Kellerstein: Texťák initialpdfinitial ko vobrázek prostě Jako soubory. A potom
prompty. Sou vlastně jenom texty. Stringy. Vlastně jo, konkrétně String Template Y,
42:05 - 42:13
Lukáš Kellerstein: ale, eh, jako string, to znamená, že tůl Je něco, co já zavolám. A vono
to exeku ňákou funkcionalitu
42:14 - 42:18
Lukáš Kellerstein: a. Vrátí mi to odpověď. Z tý funkcionality resource Je že, já to Zavolám
42:19 - 42:21
Lukáš Kellerstein: a von mi vrátí obsah toho souboru
42:22 - 42:28
Lukáš Kellerstein: a prompt, je že já to zavolám a von mi vrátí text de facto, Jo,
42:28 - 42:31
Lukáš Kellerstein: tydle Ty tři věci jsou v initialmcpinitial serveru podporovaný?
42:32 - 42:33
Lukáš Kellerstein: Já si jenom napiju. Pardon.
42:34 - 42:40
Jan Duplak Tab: Ale Musím, že za úry a initialcmdinitial těž může být funk funkcia ne,
skutečnosti takže.
42:43 - 42:44
Lukáš Kellerstein: A Dolem. Ještě jednou.
42:45 - 42:49
Jan Duplak Tab: Že za tým úri a initialcmdinitial může být funkcia. V podstatě.
```

## Strana PDF 21

```text
42:51 - 43:00
Lukáš Kellerstein: Je to server. Takže tam vlastně jako End point. Jako takovej Je funkce
tam de Spíš vo to, jako co to vrací.
43:01 - 43:02
Lukáš Kellerstein: Jo, tak.
43:02 - 43:04
Jan Duplak Tab: A je to okresané. Není to Mhm.
43:05 - 43:18
Lukáš Kellerstein: Takže ukážeme si v tý implementaci. Máte pravdu, že? Stejně jako u
Langenglishinitialapiinitiallangenglish, že? Všechno to je End Point. Todleto V tom
případě všechno jsou taky jako End Point y. Jo, tam de vo to. Ale jenom
43:19 - 43:26
Lukáš Kellerstein: co se nám vlastně jakoby vrací z toho Endpoint u. A proto voni takhle
rozdělujou do těhle těch tří tří věcí.
43:27 - 43:30
Lukáš Kellerstein: Každej má svůj vlastní jako endpoint.
43:32 - 43:35
Lukáš Kellerstein: Jde teda vo návratovej Typ de facto
43:35 - 43:43
Lukáš Kellerstein: Tady z toho se mi může vrátit jako cokoliv. Tadydle z toho se mi vrací
binární data a tadydle z toho se mi vrací. Vlastně, string.
43:46 - 44:01
Lukáš Kellerstein: Tak teď si předtím, než si začneme ukazovat, jak, vlastně, eh, psát
initialmcpinitial servery, a jakej je rozdíl mezi Verzí jedna a verzí, dva a tak dále. Tak si
myslím, že by bylo vhodný ukázat, jako říct minimálně, že
44:01 - 44:08
Lukáš Kellerstein: jak jsem říkal, že Budete o období, kdy všichni psali initialmcpinitial
servit, tak už spoustu těch serverů je napsanejch
44:09 - 44:20
Lukáš Kellerstein: a vy byste si pravděpodobně nemuseli nutně psát pro Každou věc,
svůj vlastní server. Jako na začátku jsme to dělat museli.
44:21 - 44:34
Lukáš Kellerstein: To znamená, eh, máme tady jenom abyste si dokázali představit jako
jaký typy. Tak jsou tady takhle. Jenom taková stručná, Velmi stručná tabulka. Jenom
abyste viděli zhruba ty, eh, jako domény.
44:35 - 44:43
Lukáš Kellerstein: Co všechno v různejch doménách Má dneska initialmcpinitial servery.
Jo, Paypal Alpaka na trading a investování Strype
44:44 - 44:46
Lukáš Kellerstein: Jo, Github Prostě všechny různý data
44:47 - 44:56
Lukáš Kellerstein: play Write, jakožto něco, čím, obsluhujete Browser. To vám teďkom
budu demonstrovat i Cloud Provider. Ři. Už mají dneska initialmcpinitial servery jo
```

## Strana PDF 22

```text
44:57 - 45:06
Lukáš Kellerstein: A všechny takovýdle ty notion nebo tweely jo, Nebo prostě takový Ty,
eh, takový ty standardní věci. Takže si, myslím že
45:07 - 45:10
Lukáš Kellerstein: Sales Force a tydle ty, to znamená,
45:11 - 45:25
Lukáš Kellerstein: co by teďkom říct, je, kde je najdete tak první, kde byste vždycky, Když
budete se i koukat po. Jako, jak psát vlastní initialmcpinitial servery, tak se určitě
Vždycky podívejte na ten Github
45:26 - 45:36
Lukáš Kellerstein: toho model Context Protocol. Tady je takový repozitář, kterej ukazuje,
jak psát tydlety servery
45:39 - 45:44
Lukáš Kellerstein: ukázkový v tý aktuálně poslední Verzi Initialmcpinitiallangenglish
45:44 - 46:03
Lukáš Kellerstein: Todle Říkám ne proto, když to budete chtít použít, Ale spíš pro ty, z
vás kdy si budou chtít psát vlastní initialcpinitial servery. Tak tady budete hledat tu
inspiraci tady. Sou ty zdrojáky pro to jak, se píše třeba nebo, jak se píše git Server nebo
Jak se píše server, co spravuje paměť pro agenty? Jo,
46:04 - 46:13
Lukáš Kellerstein: bylo jich tady víc. Tady vidíte Archive? Archive, Pardon, tady arcived.
Ale,
46:15 - 46:25
Lukáš Kellerstein: eh, to Už tydle se rozhodly ignorovat a nepodporovat. Takže najdete
to i napsaný v různejch s D káčkách v různejch jazycích
46:26 - 46:34
Lukáš Kellerstein: Tady jsou vyjmenovaný všechny Esdékáčka, který ten initialmcpinitial.
Server jako ta technologie initialmcpinitial podporuje, jak klient tak server.
46:35 - 46:44
Lukáš Kellerstein: Ale tydle ty ukázkový servery nejsou vždycky napsaný, jako jsou
Napsaný v jednom tý technologii a většinou z devadesáti devíti procent
46:45 - 46:46
Lukáš Kellerstein: je. To python
46:47 - 47:02
Lukáš Kellerstein: a. Nebo to je typescript Neviděl. Jsem tam eště Žádnou ukázku v
jinym jazyce. Takže tyhle ty dva jazyky jsou jako i celkově v Eja Převládá. Nadvládá
pythonu a hned za nim je vlastně typescript, protože spoustu lidí
47:03 - 47:08
Lukáš Kellerstein: přichází z frontendu, Takže vlastně se adaptoval docela dobře. Typ
skept taky.
47:09 - 47:19
Lukáš Kellerstein: Takže tady hledejte inspiraci nicméně. Pokud, budete chtít používat.
Eh, initialmcpinitial server y Jako že už jsou napsaný a budete chtít použít
```

## Strana PDF 23

```text
47:19 - 47:24
Lukáš Kellerstein: a ukážu vám tady ukázku jenom, jak jak je použít,
47:28 - 47:30
Lukáš Kellerstein: Tak jenom pardon. Tady něco napíšu.
47:37 - 47:43
Lukáš Kellerstein: Tak je tady registr od model contex Protokolu to. Znamená Že,
47:44 - 47:52
Lukáš Kellerstein: tadydle když Na to klikneme tak, tadydle Je Registr všech
initialmcpinitial server ů a teď. Těch jako oficiálních
47:53 - 47:57
Lukáš Kellerstein: jo to. Znamená, že to, je za mě důležitý že sou oficiální
47:58 - 48:04
Lukáš Kellerstein: a Vy si tady budete moct, najít prostě dole.
48:11 - 48:16
Lukáš Kellerstein: Tak teď nevím, kdo mi zmizelo to vyhledávání Paypal.
48:18 - 48:23
Lukáš Kellerstein: No, teď vypadá to že tady něco Nefunguje,
48:29 - 48:32
Lukáš Kellerstein: jako kdyby jim přestalo fungovat vyhledávání. Teda
48:40 - 48:44
Lukáš Kellerstein: tak zajímavý. Tady se mi tady. Se to má profiltrovat. Podle toho
48:45 - 48:47
Lukáš Kellerstein: dobře, tak kdyby tady nebyl Paypal, tak je tady.
48:50 - 48:53
Lukáš Kellerstein: Teď se něco stalo. Play Wright.
48:56 - 49:00
Lukáš Kellerstein: Ne, něco mi tady na tom nesedí.
49:04 - 49:04
Lukáš Kellerstein: Github
49:09 - 49:15
Lukáš Kellerstein: Respons a žádná respons a Heather je
49:19 - 49:23
Lukáš Kellerstein: Ne pravidlo není nic. Pilot není nic
49:26 - 49:27
Lukáš Kellerstein: zajímavý.
49:30 - 49:31
Lukáš Kellerstein: Zajímavý, Jo.
49:31 - 49:35
Jan Duplak Tab: Tam ten Search. Nemám ani vůbec na Firefox. E.
49:35 - 49:47
Lukáš Kellerstein: Ono už se něco děje? Už se tady něco děje? Víte, že se mi to tady pod
rukama vlastně změnilo, aniž bych něco napsal. A teď to tady ukázalo. Ten Paypal, co Já
jsem tam napsal předtím.
```

## Strana PDF 24

```text
49:47 - 49:56
Lukáš Kellerstein: Já si myslím, že maj jako ňákej Problém na tý stránce, že ta
implementace není dobrá. Nebo ten server, kterej vrací vlastně tu odpověď na to
vyhledávání
49:56 - 49:58
Lukáš Kellerstein: je ňákej zapražděnej takže. Vidíte.
49:58 - 49:58
pvojacek: To je.
49:59 - 50:03
Lukáš Kellerstein: Třeba vy Něco S Githabem mi to jako našlo. Jo, vidíte, tady.
50:04 - 50:12
Lukáš Kellerstein: Ale trvalo to hrozně dlouho a musely se Tady vobjevit Tadydle ty
modrý obdélníčky recently updated It.
50:13 - 50:13
Lukáš Kellerstein: To je super.
50:14 - 50:18
Jan Duplak Tab: Teda Som dal Firefox. A už to tam mám. Těch Neměl.
50:19 - 50:29
Lukáš Kellerstein: No, teď, teď to tam bylo. Teď to zmizelo. Ukázalo mi tady recently
update. Takže něco, co tady děje Předtím To fungovalo normálně a vyfiltrovalo to tady,
Eh normálně.
50:33 - 50:33
Lukáš Kellerstein: Tak
50:35 - 50:41
Lukáš Kellerstein: pardon, dítě mi tady v něčem jezdí. Tady za za tim, za za dveřma. Tak
já mu to jdu jenom říct aby.
51:08 - 51:10
Lukáš Kellerstein: Tak už jsem zpátky.
51:15 - 51:25
Lukáš Kellerstein: Dobře, takže todle. To mi přijde rozbitý, ale normálně to funguje jako
Správně, cos? Já jsem tím chtěl říct spíš A eště tady bude jeden link, myslím.
51:26 - 51:27
Lukáš Kellerstein: Tak tenhle. Ten.
51:28 - 51:43
Lukáš Kellerstein: Eh, todle. To je teda oficiální registr Vod
langenglishinitialmcpinitiallangenglish Vidíte. Že, to běží na tý doméně model kontext
protokol takže? Tady bych jako bral to jako oficiální registr initialmcpinitial serveru Ale
jak vidíte, jako nevim, jaká jakej s tím mají záměr,
51:44 - 51:48
Lukáš Kellerstein: jestli to bude, eh, jako v fungovat nebo ne.
51:49 - 51:55
Lukáš Kellerstein: Každopádně je tady jinej A ten je neoficiální. Teda a ten funguje teda
mnohem líp.
```

## Strana PDF 25

```text
51:56 - 51:59
Lukáš Kellerstein: A to je tajdle ten osm. Initialmcpinitiallangenglish servers
51:59 - 52:07
Lukáš Kellerstein: a tady, těch eh, server ů initialmcpinitial Najdete Prostě taky kupu já.
Myslím Že, todle to vzniklo první tadydle ten.
52:08 - 52:14
Lukáš Kellerstein: Osm langenglishinitialmcpinitiallangenglish Servers A tydle ty todle to
vzniklo Nedávno poměrně.
52:14 - 52:16
Lukáš Kellerstein: Takže já jsem doufal,
52:16 - 52:22
Lukáš Kellerstein: že to teda initialmcpinitiallangenglish veme pod hlavičku a udělá z
toho pořádnou stránku a já budu moct chodit sem.
52:23 - 52:32
Lukáš Kellerstein: Nicméně, vono. To je vlastně jedno. Pokuď oni budou ukazovat
initialmcpinitial servery i ty neoficiální. A teď teď tě to chci zdůraznit
52:33 - 52:36
Lukáš Kellerstein: Jak tady správně poznamenal Luboš v tom příspěvku,
52:37 - 52:41
Lukáš Kellerstein: když jsme si ukazovali, že initialmcpinitial server. A teď já jsem to tady
vlastně říkal
52:42 - 52:45
Lukáš Kellerstein: tadydle v tom případě těhle těch dvou případech.
52:46 - 52:55
Lukáš Kellerstein: To je vlastně kód, kterej se Je to jenom kód. Je to jenom script kterej
ten initialmcpinitial klient když ho potřebuje, tak si ho vlastně jako zavolá.
52:55 - 53:00
Lukáš Kellerstein: A teď, protože to initialsdinitial a jo, běží na stejným počítači, jako je
ten klient,
53:00 - 53:04
Lukáš Kellerstein: To Znamená že co se musí stát první, musí se nejdřív ten
53:04 - 53:07
Lukáš Kellerstein: s skript Vlastně jakoby stáhnout na ten počítač.
53:08 - 53:22
Lukáš Kellerstein: Jo, a pak ten Initialmcpinitial klient, ten skript jako vyvolá. A teď ten,
eh, ten script zase jako už s ním teda začne komunikovat a začne si s ním povídat.
Nicméně, to vyvolání toho skriptu je ta důležitá část. A to, že je to script,
53:23 - 53:27
Lukáš Kellerstein: je ta druhá důležitá část, to, znamená že já, když si tady dám paypal,
53:29 - 53:35
Lukáš Kellerstein: tak tadydle je vidět oficiální initialmcpinitial. Server od Paypal. U.
53:35 - 53:37
Lukáš Kellerstein: Jo, tady to official je důležitý
```

## Strana PDF 26

```text
53:39 - 53:53
Lukáš Kellerstein: a Doporučoval bych vám používat vlastně jenom ty official.
Initialmcpinitial Servis. Kdyby Když jako to stáhnu na sebe, tak já se hodně kroutím.
Pokuď to Není Official Initialmcpinitial server.
53:53 - 54:01
Lukáš Kellerstein: Dávám si na tom velkej pozor A ten důvod je takovej, že vy stáhnete
vlastně ten skript lokálně, povětšinou,
54:02 - 54:20
Lukáš Kellerstein: a Teď ho budete chtít dát tomu agentovi. Ten agent ho začne
používat a pouští vlastně ten skript. A teď se zeptejte sami sebe, jestli jste si
zkontrolovali, co ten skript vlastně jako, eh, dělá? Jo, a teď se tady můžeme podívat
tadydle na ten cloud Service Paypal Initialmcpinitial server. Jo, jak jste říkal, ten, tak to
zní. Dobře,
54:21 - 54:27
Lukáš Kellerstein: Tak se na to klikneme a podíváme se na ten detail Toho
Initialmcpinitial serveru A všechny ty initialmcpinitial servery
54:28 - 54:38
Lukáš Kellerstein: drtivý. Většině. Mají tady githa Prepozitář a. Na. Ten když. Si kliknete
tak, zjistíte vlastně zdrojovej kód toho initialmcpinitial serveru. A teď se podívejte,
54:38 - 54:43
Lukáš Kellerstein: byl update updateovanej Minulej rok má nula hvězdiček
54:44 - 54:46
Lukáš Kellerstein: a nikdo nezná tajdle toho člověka.
54:47 - 54:57
Lukáš Kellerstein: Takže, dovolíte si vlastně použít Jako ten initialmcpinitial server. Stáhli
byste si tenhle? Ten kód a dobrovolně byste si ho pustili jako na svym počítači a? Asi ne
54:57 - 55:01
Lukáš Kellerstein: tak Jenom proto, že je nalistovanej Vlastně tadydle v ňákym tom
55:01 - 55:07
Lukáš Kellerstein: Tadydle Tadydle V Ňákym tom listu initialmcpinitial serveru tak to pro
vás neznamená žádnou věrohodnost
55:08 - 55:18
Lukáš Kellerstein: Takže. Dávejte, si jenom pozor který, initialmcpinitial servery vlastně
používat používejte. Hlavně ty oficiální ten. Má taky ňákej githa prepozitář
55:18 - 55:32
Lukáš Kellerstein: Ale vidíte, že to má prostě. Paypal to spravuje. Má to teda víc
hvězdiček. Vo ty hvězdičky úplně teďkon. Jako úplně nejde. Jo, ale asi nemá Paypal
Záměr dávat do toho skriptu ňákej, malver Nebo
55:33 - 55:48
Lukáš Kellerstein: vodví nebo, těžit kryptoměny na tom skriptu nebo, já nevím vodvírat
backdoor y pro ňáký a Pro někoho, kdo se za tři měsíce rozhodne, že začne atakovat
tady český zdravotnický organizace. A přes vás přes váš počítač
```

## Strana PDF 27

```text
55:49 - 55:55
Lukáš Kellerstein: bude vlastně jako atakovat ty nemocnice. Jo, jenom proto, že si tady
vodevře ty zadní vrátka na to vašem počítači.
55:55 - 56:04
Lukáš Kellerstein: Takže, dávejte si pozor, jaký ty initialmcpinitial Servery instalujete. Já
používám jenom ty official. Takže já. Tady kliknu na todle
56:05 - 56:19
Lukáš Kellerstein: a tydle sem ochotnej použít. Tady je zrovna hezkej příklad s tím jedna
password. Jo, si. Představte si, že byste měli to jedna Password, což je služba, jako je,
eh, jako, já používám tady ten Proton Pass,
56:19 - 56:27
Lukáš Kellerstein: která mi sdružuje všechny hesla, abych je furt nemusel si pamatovat
nebo psát, Tak vlastně se někam přihlásim,
56:27 - 56:46
Lukáš Kellerstein: Nebo když se votevře Login na Netflix. Tak von mi automaticky
nabídne. Hele, tydle hesla já mám uložený. Chceš si tam vložit Já Řeknu jo, vlož je tam A
von mě přihlásí. Tak to je třeba tady ten jedna password. Initialmcpinitiallangenglish. Jo,
teď si představte, že byste použili initialmcpinitial server pro Jedna Password, kterej
neni oficiální. A teď ten
56:46 - 56:54
Lukáš Kellerstein: vlastně script by si posílal ty Všechny vaše. Hesla, který z toho
jednoho passwortu by získával, tak by se posílal nějakej někam, támhle
56:54 - 57:02
Lukáš Kellerstein: do bůhví kam a a najednou. Pak byste se divili za půl roku by někdo
vyluxoval účet a Vy byste vlastně vůbec nevěděli, jako jak se to stalo.
57:03 - 57:13
Lukáš Kellerstein: Takže na to si dávejte, prosím pozor. Je to opravdu důležitý, Proto
tomu věnuju I takovej prostor, abyste tam zbytečně nepoužívali. Initialmcpinitial. Servie,
který byste neměli
57:14 - 57:33
Lukáš Kellerstein: sou situace, kdy i já použiju takovej initialmcpinitial. Server, Ale ten
initialmcpinitial Server musí už bejt jako vyzkoušenej, spoustě jinejma lidma Nebo
Případně já si musím ten zdrojovej kód projít. To znamená, že co bych udělal, je, že bych
si tendle ten zdrojovej kód vlastně stáhnul.
57:33 - 57:51
Lukáš Kellerstein: A agenta bych než bych, ho pustil tak, bych vlastně jinýho agenta
kódovacího agenta Kloud, kód, kódexamina. Já nevím, cokoliv máte oblíbenýho, tak na
to pusťte. Pusťte ze. Řekněte. Mu tady. V Tý Složce mám initialmcpinitial server který,
jde použít.
57:51 - 58:08
Lukáš Kellerstein: Obsahuje to ňákej škodlivej kód volá. To ňáký. Url stránky který by, to
nemělo volat a von vám za pět minut de Facto dá nějakou takovou analýzu. Pokuď,
samozřejmě, ten útočník bude sofistikovanej. Tak schová ňáký věci do. Toho sou
```

## Strana PDF 28

```text
58:09 - 58:19
Lukáš Kellerstein: způsoby jak, to schovat ale, ten, Cloud Kód, jako. Věřím mu na hodně
procent, aby. Když von mi řekne hele. Vypadá, to zdravě tak, jako abych já si dovolil
použít
58:21 - 58:35
Lukáš Kellerstein: Tak zase ne Všechny Initialmcpinitial servery, který sou takhle na Git
Hub. U Tak jsou jako škodlivý. Jo, ale stalo se a teď já jsem měl nějaký příklady. Možná i
tady budou zmíněný. Teď se pojďme tady podívat do tý prezentace.
58:41 - 58:59
Lukáš Kellerstein: Tak tady jsou zmíněný. To znamená, že Ten initialmcpinitial server je
jenom kód, kterej běží na vašem počítači. Má takovoudle konfiguraci. Hned vám to
demonstru Budu demonstrovat na jednom initialmcpinitial serveru Ty vostatní jsou
dost podobný. A eště si ukážeme jak to, použít pro dva způsoby. To znamená, že,
59:00 - 59:07
Lukáš Kellerstein: eh, tadydle jsem chtěl nejdřív teda vysvětlit, abych navázal na to, že
tady byly historicky příklady.
59:07 - 59:26
Lukáš Kellerstein: Initialmcpinitial serveru, který byly škodlivý. Jo, takže tady byl
postmark. Initialmcpinitial server, kterej kopíroval, Vlastně, eh, email Y a posílal je
vlastně někam jinam. Všechny vaše, Všechny vaše email Y dával do kopie. Vlastně toho
atakra a posílal mu je.
59:27 - 59:28
Lukáš Kellerstein: Jo, takže jeden příklad
59:29 - 59:47
Lukáš Kellerstein: potom. Langenglishinitialmcpinitiallangenglish Remote. Takovej
takovej oblíbenej nástroj, kterej vlastně z lokálního initialmcpinitial serveru z toho dělal
vlastně jakoby ten stream server. Takže dělal z toho opravdovej server s initialipinitial
adresu a sportem, Tak ten měl taky, eh, vlastně
59:48 - 59:59
Lukáš Kellerstein: problém, protože tam eh Používal knihovnu, která dovolovala, aby
ten vlastně si mohl pustit u vás
59:59 - [01:00:12]
Lukáš Kellerstein: eh jakejkoli komand. Jo, Takže vy jste sice vystavili ten server ven Díky
týdle tý initialmcpinitial remote. Jenomže ten server, kterej to vystavoval, měl problém.
To znamená, že pak tam mohli pouštět vlastně jakýkoliv
[01:00:12] - [01:00:22]
Lukáš Kellerstein: příkazy, to znamená, že pak vám mohli zjistit, co ti myslej příkazy
příkaz. Typu eh, Najdi, Mi na tom file systému všechny. Klíče
[01:00:23] - [01:00:34]
Lukáš Kellerstein: všechny, Langenglishinitialapiinitiallangenglish Klíče, Všechny tokeny
a tak dále a pošleme je někam jinam. Jo, takže zase. Dávejte si na to pozor. Měl to
tadydle ten initialcvinitiallangenglish kód,
```

## Strana PDF 29

```text
[01:00:35] - [01:00:41]
Lukáš Kellerstein: Tak a potom je tady Tool Poisoning. To znamená, že když, eh, von
bude chtít použít ten tool,
[01:00:42] - [01:00:45]
Lukáš Kellerstein: tak v tom tůlu v tom popisu toho toulu
[01:00:45] - [01:00:52]
Lukáš Kellerstein: vlastně může bejt schovanej ňákej ňáká instrukce pro ten eh pro,
toho, agenta
[01:00:53] - [01:00:57]
Lukáš Kellerstein: takže nemusí, vono to může se. Tvářit že To dělá to, co má.
[01:00:58] - [01:01:10]
Lukáš Kellerstein: Vy můžete bejt spokojený s tím, jak to funguje, Ale jedna, jeden krok,
kterej tam bude popsanej, Eh, pro Toho agenta bude třeba. Hele, najdi mi tady všechny
Initialssinitial klíče
[01:01:11] - [01:01:19]
Lukáš Kellerstein: a všechny ty Initialssainitiallangenglish. Klíče mi pošli, třeba tudletu
url adresu nebo je Uploiduj támhle někam do do
[01:01:20] - [01:01:33]
Lukáš Kellerstein: Dropboxu a já se tam prostě Teda, ten útočník se tam vy povyzvedává
a pak se bude moct někam připojovat. Takže, eh, tomu se, říká, eh. Tomu se říká
Prompt Injection. To znamená,
[01:01:34] - [01:01:42]
Lukáš Kellerstein: eh. Dávejte si pozor tadydle ten popis nebo i to, Co ten
initialmcpinitial? Server dělá? Nemusí to bejt vždycky dobrý.
[01:01:42] - [01:01:55]
Lukáš Kellerstein: Tak tadydle konfigurace. Takovýho initialmcpinitial serveru. Když to
budu chtít použít, takže pojďme si To, eh, demonstrovat. Vždycky to má takovejdle
formát. Takže, pojďme si nejdřív říct, co ten formát znamená?
[01:01:55] - [01:02:07]
Lukáš Kellerstein: Todle je jméno toho initialmcpinitial serveru, tak jak já. Chci ho chci
pojmenovat. To je čistě na mě. Jestli tam bude a nebo si tam dám nějakej logickej,
prostě biologický pojmenování,
[01:02:07] - [01:02:10]
Lukáš Kellerstein: Potom je tady komand, kterej se pustí.
[01:02:10] - [01:02:16]
Lukáš Kellerstein: To může bejt u v X, Když to bude python kód a budu vlastně pouštět
[01:02:17] - [01:02:33]
Lukáš Kellerstein: ten Python Kód, Ehm, jako lokálně jako Tool. To je to X na konci. Jinak
u v. Jako takový. Vy znáte, nebo budeme si ho i ukazovat v průběhu kurzu. Protože
jakejkoli skript, kterej budeme pouštět, tak pouštíme jako u v
[01:02:33] - [01:02:39]
Lukáš Kellerstein: Run Maine. Jo, takže Juve, pusť mi ten skript Paetní Main
```

## Strana PDF 30

```text
[01:02:39] - [01:02:42]
Lukáš Kellerstein: a je obdoba. Kdy vlastně jenom já
[01:02:43] - [01:02:46]
Lukáš Kellerstein: řeknu. Pus mi script, kterej je uloženej v pipu.
[01:02:46] - [01:02:53]
Lukáš Kellerstein: Jo, a Initialmpxinitial je zase pro Ty z vás co dělají frontend tak? To je
m
[01:02:53] - [01:03:12]
Lukáš Kellerstein: Takže. Po obdoba initialuvinitial ale. Na frontend u a Tam zase píšete
run main Dot Js Main Tečka Js je Javascript. To znamenáva script. A je zase obdoba. Jako
je u v X a to pouští javascriptway.
[01:03:12] - [01:03:19]
Lukáš Kellerstein: A Pak je třetí typ a to je dokr. Takže do krje pustmy. Tenhle. Ten
initialmcpinitial server.
[01:03:20] - [01:03:39]
Lukáš Kellerstein: Všechny tři. Vlastně pouštěj skripty Na Vašem, lokálním Počítači. Jo, to
je vlastně to, co se stane. Ten agent si řekne hele. Mám, k dispozici tadydle ten cool db
Tool Ten, má Takovej popis a dělá tydle ty věci. Já ho chci použít. Jo, a v Tom Tool
Kolingo si ho to elanko vybere
[01:03:39] - [01:03:58]
Lukáš Kellerstein: a na Vaší straně se ten tool vlastně jako pustí exeku se na tom vašem
počítači. To znamená když to je initialmcpinitial server, tak to znamená, že se stáhne ten
initialmcpinitial server k vám do počítače. A přes tady ten Koman se vlastně pustí a ten
Koman má argumenty, a To je vlastně tadydle ten druhej řádek a. S tím se to pustí
[01:03:59] - [01:04:04]
Lukáš Kellerstein: takže. Ve výsledku co, tím chci jako eh, demonstrovat, i
[01:04:04] - [01:04:07]
Lukáš Kellerstein: abyste V tom zase nehledali žádnou vědu.
[01:04:08] - [01:04:20]
Lukáš Kellerstein: A když to převedu, tak se vlastně stane todle, jako kdybych já si ručně
napsal todle to do terminálu
[01:04:24] - [01:04:26]
Lukáš Kellerstein: a pustil ten pustil to
[01:04:27] - [01:04:39]
Lukáš Kellerstein: takže cokoli. Je v, tom vlastně cool
langenglishinitialdbinitiallangenglish script. U tak já. Si vlastně dobrovolně pustím na
počítači Akorát když to dáte tomu agentovi, tak to takhle nevnímáte. Takže jenom
abyste to. Zase
[01:04:39] - [01:04:48]
Lukáš Kellerstein: jsem si dal důraz na to, že to je vopravdu. Jenom skript kterej pouštíte
ručně. Tak teď si pojďme nějakej initialmcpinitial server ukázat.
[01:04:52] - [01:05:04]
Lukáš Kellerstein: Tak já jsem říkal eště jednu věc, že já procházím, Nebo nechám
procházet případně ten zdrojovej kód toho initialmcpinitial serveru tím kód, kódem
nebo kodexem, Abych zjistil, jak to, jak to,
```

## Strana PDF 31

```text
[01:05:04] - [01:05:15]
Lukáš Kellerstein: jestli to je Škodlivý nebo ne? Není to samozřejmě dostatečný. Eště je
tady do dobrá věc si to zkontrolovat Si C v E kódy. To sou ty Kódy jako byl tadydle. Ten
[01:05:15] - [01:05:17]
Lukáš Kellerstein: jsem si to tady zavřel.
[01:05:21] - [01:05:39]
Lukáš Kellerstein: Initialcvinitiallangenglish. Kódy jako byl vlastně tadydle. Ten
initialcvinitiallangenglish Kód tady pro tendle, ten Eh, pro tendle. Ten
Initialmcpinitiallangenglish remote, tak byste si mohli pro ten
initialmcpinitiallangenglish server, kterej plánujete použít není oficiální, tak si
zkontrolovat, jestli tam neexistuje Tady ten initialcvinitiallangenglish Kód
[01:05:40] - [01:05:57]
Lukáš Kellerstein: jsou na Tourlinitial Adresy nebo Url. Stránky, Kam to zadáte? A vono
nám to vyplyvne Jaký jsou tam nale, jakou Jaký jsou tam známý díry? Případně v jakejch
verzích? Takže v některý tý verzi tam může bejt problém, ale v novější verzi už tam třeba
ten problém bejt nemusí. Tak to byste si taky
[01:05:57] - [01:06:00]
Lukáš Kellerstein: mohli, eh, mohli s zkusit.
[01:06:01] - [01:06:20]
Lukáš Kellerstein: Pak jsou tady Eště, ehm, způsoby, Kdy vy vlastně Pouštíte ten
initialmcpinitial? Server v izolovanym prostředí. To si necháme na pozdějc, Když tak já
budu ještě trochu mluvit vo sandboxingu a agentů, takže Já si myslím, že todle i s tim,
Eh, k tomu vlastně jako patří.
[01:06:21] - [01:06:26]
Lukáš Kellerstein: Eh, tak jedná se teda hlavně vo ty a jo, servery,
[01:06:27] - [01:06:33]
Lukáš Kellerstein: Protože ty pravděpodobně na ty budete hodně narážet ale. Platí to i
pro ty streamuble servery
[01:06:34] - [01:06:39]
Lukáš Kellerstein: eh. Co Ale, s čím můžete bejt úplně v pohodě. Jsou vlastně remote
servery.
[01:06:40] - [01:06:55]
Lukáš Kellerstein: To znamená buď ten server Běží, nebo s tím budete komunikovat
jeho způsobem a pustí se lokálně dobrý. Nebo ten server bude podporovat
Streamblinitiallangenglish To znamená, že bude to mít initialurlinitial adresu a port
[01:06:56] - [01:07:13]
Lukáš Kellerstein: to znamená že se, to bude vyžadovat Vod vás abyste, si ho někam
nasadili. Tak i todle je vlastně nebezpečný, protože sice to nepoběží na tom vašem
počítači striktně nemusí, Může, Ale nemusí, Ale stejně to budete někam nasazovat, Ať už
dovnitř do firmy jako server nebo nebo něco takovýho.
[01:07:14] - [01:07:15]
Lukáš Kellerstein: Takže i to
```

## Strana PDF 32

```text
[01:07:16] - [01:07:34]
Lukáš Kellerstein: tam si Musíte Hlídat co. Ten server vlastně dělá jo? Jestli, vodvírá eště
ňákej port, kde se, K němu může někdo připojit z venku a tak Dále a tak dále. S Čím ale?
Můžete bejt tak nějak jako v. Klidu bych řek tak jsou. Remote servery to znamená. To
sou většinou Zase oficiální servery
[01:07:35] - [01:07:41]
Lukáš Kellerstein: který, ty společnosti nabízejí takže. Stejně tak jako ty společnosti
vystavujou langenglishinitialapiinitiallangenglish servery třeba github
[01:07:42] - [01:07:51]
Lukáš Kellerstein: Pro scripty Naše, skripty který, Píšeme, když chceme zjistit půl request
y a tak dále, tak se připojujem na langenglishinitialapiinitiallangenglish server toho
[01:07:51] - [01:08:05]
Lukáš Kellerstein: a souběžně s Tim ten github vlastně Vyexpouzoval, dal k dispozici
initialmcpinitial server. A to je pro ty agenty. Když agenti se budou chtít připojit do
Gidab u, tak ten initialmcpinitial Server toho běží u nich na serverech
[01:08:06] - [01:08:17]
Lukáš Kellerstein: A vy se. Ten agent se tam jenom autentizuje a autentikuje a dostane
tam přístup, takže tam Zase ten škodlivej kód. Kdyby tam ňákej byl v tomhle
initialcpinitial serveru tak, běží na jejich serverch.
[01:08:18] - [01:08:21]
Lukáš Kellerstein: A. Vy už si s nima jenom Povídáte Todle Je vlastně ideální stav.
[01:08:22] - [01:08:30]
Lukáš Kellerstein: Kdy vy vůbec ty servery nemusíte ani nevztahujou k vám žádnej
zdravej kód. Vy ho nemusíte nikam nasazovat A běží jako rovnou tam.
[01:08:32] - [01:08:48]
Lukáš Kellerstein: Takže všechny. Ale spousta nich je tady. A vidíte, Atlasián, Kanva
Asana, Prostě Notion Slak Stripe zase supa base
[01:08:48] - [01:08:52]
Lukáš Kellerstein: Jako spousta, spousta. Spousta jich je. Jo, tady. Zase si dávejte pozor.
[01:08:52] - [01:08:55]
Lukáš Kellerstein: Vůbec nevim, co je todle. Takže to jsem
[01:08:56] - [01:09:02]
Lukáš Kellerstein: Snažte se bejt vědomí toho, že tam hrozí nějakej případnej útok,
[01:09:04] - [01:09:23]
Lukáš Kellerstein: tak to by byly initialmcpinitial. Remote. Servery. Já jsem chtěl jít
tadydle. To jsem chtěl zavřít, Todle jsem chtěl zavřít. Tak a pojďme si to ukázat. Tak
pojďme si to ukázat na play. Write. U. To znamená. Mám. Tady ukázané jenom Rychle v
rychlosti. Řeknu si To je Play, Write. Pro ty z vás. Kdo to neznaj,
[01:09:23] - [01:09:26]
Lukáš Kellerstein: tak play, Write jako takovej je tool,
[01:09:28] - [01:09:42]
Lukáš Kellerstein: kterým Jste schopný ovládat webovej prohlížeč. To znamená, že tři
typy nebo všechny vlastně oblíbený webový prohlížeče. S tím jste schopný, eh,
skriptovat. Jste schopný vlastně napsat test,
```

## Strana PDF 33

```text
[01:09:43] - [01:09:44]
Lukáš Kellerstein: kterej si třeba
[01:09:45] - [01:09:59]
Lukáš Kellerstein: vodevře určitou webovou stránku na klikne si tam někde na něco a
skončí. Jenomže to je script. To je script, kterej vy musíte napsat. To je test, kterej vy
musíte napsat. Ale ten Playvright vám pomůže s věcma jako
[01:10:00] - [01:10:11]
Lukáš Kellerstein: jako vodevři testu Něco takovýdleho to znamená. Je tady, Eh Vode na
vodevři. Browser.
[01:10:12] - [01:10:30]
Lukáš Kellerstein: To tady zrovna teďko nevidím, Ale když se otevře browser, tak je tady
Votevři stránku a běž na Tudle Urla adresu. Jo, a teď se koukni v Initialhtml na titulek a.
A jestli tam je, prostě slovíčko Play Write. Tak jako skončí tadydle. Pak najdi si link, kterej
má
[01:10:30] - [01:10:32]
Lukáš Kellerstein: get started a klikni na něj.
[01:10:33] - [01:10:46]
Lukáš Kellerstein: Jo a zase něco zkontroluj, Takže, Jenom jsem tím chtěl demonstrovat.
Co to ten skript jako znamená? A že vy vopravdu můžete celej ten brousek, všechno to,
co může dělat uživatel. Vy můžete napsat skript a to provede ten skript.
[01:10:48] - [01:11:02]
Lukáš Kellerstein: A aby todle to se dalo, eh, dát k dispozici agentům všechny ty všechny
Ty funkcionality. Co má vlastně brousek k dispozici? Instalování extension dávání věcí
do záložek. Eh,
[01:11:02] - [01:11:15]
Lukáš Kellerstein: brousování toho webu s tím, že se kouknete co Na tom webu je
klikání na linky. Jo, a všechny ty všechny ty věci, který si představíte, že může dělat
uživatel, můžete dělat přes Tady ten Play Write.
[01:11:15] - [01:11:18]
Lukáš Kellerstein: A teďkon ten Play Write vystavil initialmcpinitial server,
[01:11:19] - [01:11:37]
Lukáš Kellerstein: aby mohli I Agenti dělat všechno v tom browser u stejně jako uživatel.
Takže tady pak máte repozitář toho. Je to opravdu hodně oblíbený. Ten Play Right
Initialmcpinitiallangenglish. Hodně se to používá, Já sem třeba konkrétně Psal agenty,
který dělali automatický testy
[01:11:38] - [01:11:55]
Lukáš Kellerstein: tím, že proklikávali sami aplikaci. Jenom podle toho, že jsme napsali
slovně, co se má testovat, voni to pak testovali. Takže vydali k tomu initialmcpinitial
server A tadydle dycky v těch repozitářích najdete. A takhle se to konfiguruje.
[01:11:56] - [01:11:59]
Lukáš Kellerstein: Jo, todle zdárnej příklad,
[01:11:59] - [01:12:08]
Lukáš Kellerstein: Tahle ta sekce. Initialmcpinitiallangenglish Servers. Ta je většinou
jako daná no. A pak tahle ta struktura pod tím kterou, já jsem je ukazoval předtím
```

## Strana PDF 34

```text
[01:12:09] - [01:12:27]
Lukáš Kellerstein: Tak ta je vlastně už jakoby to je ta konfigurace toho initialmcpinitial
serveru. Takže tadydle pak je to to jméno toho, server, u který Já jsem tomu dal tadydle.
Je ten Koman, kterej se pustí. A tadydle sou to ty parametry. Takže v tomhle tom
případě vopravdu, jako Kdybych já napsal do toho terminálu Initialmpx
[01:12:27] - [01:12:30]
Lukáš Kellerstein: a todle to Tak to se vlastně jako pustí.
[01:12:31] - [01:12:33]
Lukáš Kellerstein: Teďkon ten initialmcpinitial server
[01:12:34] - [01:12:42]
Lukáš Kellerstein: má, eh, několik tůlů Tak abysme měli představu o tom, co to je za
tůly. Tak tadydle jsou ty tůly vlastně ukázaný.
[01:12:43] - [01:12:49]
Lukáš Kellerstein: Tadydle jsou jako vylistovaný, Jsou schovaný v v sekcích.
[01:12:50] - [01:13:12]
Lukáš Kellerstein: Takže, browser, klik, browser, Close Browser Drak. Jo, Browser Drop.
Drug. Je tam podporovanej evaluace jakýhokoliv javascript u V tom Browser U můžete
dělat. Vyplň formulář. Najdi něco, jo? Havr na něco najed Na ňákej titulek navigate.
Votevři. Mi Nebo změň u role Adresu tý Stránky.
[01:13:13] - [01:13:19]
Lukáš Kellerstein: Zvětš Vokno zmenší vokno. Jo, všechny. Prostě vem Snapshot
[01:13:20] - [01:13:35]
Lukáš Kellerstein: To jsem chtěl ještě ukázat. Zmáčknu f dvanáct a zmáčknu Tady
Elements tak vy Znáte tady, že jo? Vy víte, že tady v tom Initialhtmlinitiallangenglish je
prostě celá ta stránka, a že já tady, když budu na něco prostě najíždět tady někde
nahoře,
[01:13:36] - [01:13:39]
Lukáš Kellerstein: Tak se mi tady budou ukazovat jednotlivý sekce prostě tý stránky.
[01:13:40] - [01:13:57]
Lukáš Kellerstein: Todle je strašně ukecaný pro toho Agenta Todle Von Číst Úplně
nechce initialhtmlinitial. Je párovej tak. Já vyloženě nepotřebuju ty párový tak. I když to
čtu má, to ty klásy a spoustu Je to ukecaný. Takže co se dělá, je, že jemu se dává
akcesibility
[01:13:57] - [01:14:00]
Lukáš Kellerstein: strom. Takže když si ho tady jako ukážete,
[01:14:01] - [01:14:03]
Lukáš Kellerstein: tak v tu Chvíli tady vidíte?
[01:14:04] - [01:14:17]
Lukáš Kellerstein: Takový zjednodušený initialhtmlinitial nebo zjednodušený sintaxy
toho stromu tý stránky. A to je to, co se dává tomu, eh, agentovi, Takže ten agent když
si řekne vo
[01:14:19] - [01:14:21]
Lukáš Kellerstein: a teď já zase se jedu tady dolů
```

## Strana PDF 35

```text
[01:14:22] - [01:14:25]
Lukáš Kellerstein: vo snapshot Tý stránky tadydle snapshot
[01:14:27] - [01:14:29]
Lukáš Kellerstein: Tak. Vono se mu vrátí. Vlastně tenhle ten strom
[01:14:30] - [01:14:42]
Lukáš Kellerstein: a von z něho je schopnej vyčíst jako. Dobře, tak tady mám nějakej
Button. Tenhle můžu kliknout Tady Ňákej Link. Tady je nějakej titulek. Jo a tak dále. A
můžu si projít tu stránku? Vlastně tímhle tím způsobem
[01:14:43] - [01:14:50]
Lukáš Kellerstein: a může si taky vzít Scream Shot. To znamená, že tadydle si může
vyfotit tu stránku. Jak vlastně vypadá jako vobrázkem?
[01:14:51] - [01:15:05]
Lukáš Kellerstein: A pak ten agent si je schopnej zase na ni podívat. Minulou hodinu
jsme si ukazovali, že ty koly přijímaj obrázky stejně tak, jako já. Můžu. Upload ovat
obrázek do to umí zpracovat ten vobrázek.
[01:15:06] - [01:15:18]
Lukáš Kellerstein: To znamená, že i todle. To se hodí, protože vy jste schopný. Nejenom
ten agent je schopnej najednou číst tu stránku A dělat v ní akce a klikat. Ale taky si z ní
vzít Screenshot.
[01:15:18] - [01:15:32]
Lukáš Kellerstein: A to je důležitý, třeba pro případ, když se otevře stránka a přes ní se
votevře. Takovej ten baner jako. A souhlasíte s cookies. A dokud ne, nesouhlasíte s
Cookies, tak vlastně ne, nemůžete ovládat ten hotel, který je zatím
[01:15:32] - [01:15:44]
Lukáš Kellerstein: tak kdyby on neviděl a nebyl schopnej si vzít ten skrinčot, tak si
vlastně nemu jako blbě uvědomí neuvědomí. Možná, že tam je něco takovýdleho, co mu
to blokuje. Jo, takže z toho příp z toho důvodu
[01:15:45] - [01:15:47]
Lukáš Kellerstein: je dobrý že ten, Screenshot Má k dispozici.
[01:15:48] - [01:16:01]
Lukáš Kellerstein: To znamená zkrá zkráceně. Slouží to k ovládání Browser u A teďkon Já
tady mám kód aplikaci lokální nainstalovanou A teďkon, Já, když tady dám já. Když tady
dám,
[01:16:04] - [01:16:05]
Lukáš Kellerstein: tak já tady budu muset dát.
[01:16:07] - [01:16:10]
Lukáš Kellerstein: Tadydle. Mám uživatelskej účet a tady mám settings
[01:16:11] - [01:16:14]
Lukáš Kellerstein: a tadydle V tom Settings je dole. Developer
[01:16:14] - [01:16:20]
Lukáš Kellerstein: A tadydle je edit konflik. Vy tady nebudete mít nic, ale když dáte Edit
konfig,
```

## Strana PDF 36

```text
[01:16:20] - [01:16:23]
Lukáš Kellerstein: tak se vám Tady ukáže tadydle ten konfigurační soubor
[01:16:24] - [01:16:30]
Lukáš Kellerstein: kterej. Vy si votevřete v eh Vizual Studiu kódu, když jsme o něm
mluvili na začátku
[01:16:31] - [01:16:38]
Lukáš Kellerstein: a tady si najdete sekci, která se bude jmenovat Initialmcpinitial
servers a budete ji mít prázdnou.
[01:16:38] - [01:16:52]
Lukáš Kellerstein: A to, co uděláte, je, když budete chtít zkusit třeba Ten Play Write nebo
nějakej jinejmcpinitiallangenglish server a dát ho k dispozici Tadydle tomu kód ovi
vlastně lokálnímu tadydle tomu, abyste si ho mohli, aby ho von moh používat,
[01:16:53] - [01:17:03]
Lukáš Kellerstein: tak mu ho dáte. Vlastně tadydle tou konfigurací a tu to, co tam
dovnitř napíšete, je zase to, co jsme viděli v tom play Write u Play Writeinitiallangenglish
[01:17:04] - [01:17:09]
Lukáš Kellerstein: Tadydle na tom git hubu a tadydle hned na začátku. Bylo jak to
nakonfigurovat,
[01:17:10] - [01:17:21]
Lukáš Kellerstein: Jo A teď, ty Konfigurace se občas lišej podle toho, kam to chcete
dostat. Takže proto tady máte tenhle ten list velkej tadydle všech těch
[01:17:22] - [01:17:36]
Lukáš Kellerstein: Nástrojů Včetně tady toho, eh, Cloud desktop u joud kódu. Včetně
antigravity vod Google u nebo Grog, nebo prostě já nevím, open kód, nebo Prostě, já
nevím,
[01:17:37] - [01:17:43]
Lukáš Kellerstein: copilot. Jo, a tam máte ty instrukce. Případně to upřesněný,
[01:17:43] - [01:17:46]
Lukáš Kellerstein: protože některý ty tu ty nástroje vám
[01:17:46] - [01:17:52]
Lukáš Kellerstein: vám To Jakoby se Snažej zjednodušit. To znamená, že třeba cloud.
Kod na. To má Command,
[01:17:53] - [01:18:02]
Lukáš Kellerstein: kterém to tam přidáte. Ale ve výsledku vám můžu garantovat, že
devadesát Devět procent z nich má někde ňákej konfigurační soubor
[01:18:03] - [01:18:18]
Lukáš Kellerstein: ty. Ve kterym má tudle tu sekci a voni vám akorát jako klikacím
způsobem nebo Nějakým komandem usnadňujou ten zápis do toho souboru. Abyste to
do toho nemuseli takhle psát. Jako vám to ukazuju Já Vám to ukazuju z toho důvodu,
[01:18:18] - [01:18:27]
Lukáš Kellerstein: že chci, abyste věděli tu, co je za tím. A že vždycky je tam vlastně jako
takovejdle nějaká sekce v ňákym konfiguračním souboru.
```

## Strana PDF 37

```text
[01:18:27] - [01:18:34]
Lukáš Kellerstein: Takže k tomu cloudu se tam dostanete tadydle. Tim Edit Konfigem. A
pak už tam jenom vložím přesně to co bylo V tom,
[01:18:34] - [01:18:39]
Lukáš Kellerstein: Takhle jsem to zkopíroval a takhle jsem to do toho vložil. Jo, uložím.
[01:18:41] - [01:18:47]
Lukáš Kellerstein: Zavřu a restartuju ten klód. To je důležitý, nejenom že ho Zavřu tady,
[01:18:48] - [01:18:50]
Lukáš Kellerstein: ale musím ho tady dole najít
[01:18:51] - [01:19:00]
Lukáš Kellerstein: a dát pravý tlačítko a kvid. Musím ho jakoby donutit ho, aby aby ho
zabil Ten ten proces. Jinak se mi nepřenačte Ten konflikt.
[01:19:01] - [01:19:17]
Lukáš Kellerstein: Byly tam nějaký, eh, verze, kdy voni dělali automatický přenaštění
toho konfliku, Nevím, jak to Prostě vždycky funguje. Mě vždycky fungovalo to, že jsem
to zavřel a otevřel znova. Ono se to načetlo znova a fungovalo to V tu chvíli Tady budete
vidět tady ten Play Write.
[01:19:18] - [01:19:27]
Lukáš Kellerstein: A v tu chvíli. A teď zase si oslím můstkem. Takhle trošku vrátim
zpátky. Když jsem tam chtěl něco říct.
[01:19:28] - [01:19:31]
Lukáš Kellerstein: Když si dáte plus, tak tady vidíte konektory.
[01:19:32] - [01:19:45]
Lukáš Kellerstein: A teďkon. Initialmcpinitial Servery byly hrozně asi těžký jako vysvětlit
normálním lidem co, To znamená initialmcpinitial.
[01:19:46] - [01:19:50]
Lukáš Kellerstein: Takže se tomu začal dávat název konektor,
[01:19:51] - [01:20:02]
Lukáš Kellerstein: aby lidi pochopili. Ty, Co se jim nevysvětluje? Nechtějí vědět, co to je
Initialmcpinitial Nepo, nepíděj potom. Tak prostě. Tadydle se jim daly konektory. Říká se
tomu konektor.
[01:20:02] - [01:20:12]
Lukáš Kellerstein: A teď prostě tadydle máte konektory, který si můžete brousovat, To
sou ty konektory, který jsou někde nasazený jako Github a tak dále To jsou ty remood
servery
[01:20:13] - [01:20:21]
Lukáš Kellerstein: a můžete si je tam přidávat, Jo, Google Drive Y Najdete tady ten
Github a tak dále.
[01:20:22] - [01:20:34]
Lukáš Kellerstein: Takže proto se tomu začalo jako říkat nebo, jestli víte teďkon že, ty
Konektory jsou vlastně ty initialmcpinitial servery. A potom tady máte ty vaše, který se
tam můžete do toho přidávat
```

## Strana PDF 38

```text
[01:20:34] - [01:20:36]
Lukáš Kellerstein: a já tady vidíte, že Tady mám ten
[01:20:37] - [01:20:42]
Lukáš Kellerstein: play. Write. To je ten můj initialmcpinitial server, kterej jsem mu tam
nakonfiguroval.
[01:20:42] - [01:20:44]
Lukáš Kellerstein: A stejně tak ho mám dostupnej. Tady
[01:20:45] - [01:20:49]
Lukáš Kellerstein: tady Vidíte Play Write? Jo, a můžu si ho vypínat a zapínat.
[01:20:50] - [01:20:53]
Lukáš Kellerstein: A v tu chvíli von má k dispozici ten Playvright.
[01:20:54] - [01:20:55]
Lukáš Kellerstein: A jaký je K tomu důsledek.
[01:20:57] - [01:21:08]
Lukáš Kellerstein: Najdi mi nejlevnější Subaru Impreza v České republice. A teď protože
lokální kód
[01:21:09] - [01:21:25]
Lukáš Kellerstein: má automaticky v sobě jakoby vyhledej na Webu Tool Search Web
Tool. Tak já teďkon potřebuju, A protože. Oni zrušili to, že to v tom cloudu to dřív šlo
vypnout jakoby já Jsem V těch konektorech. Moh jakoby vypnout.
[01:21:25] - [01:21:34]
Lukáš Kellerstein: Který ty základní tůly? On má k dispozici, a já se povypínat. Teď jsem
mu tady vypnul Klód in chrom. To je další nástavba toho.
[01:21:34] - [01:21:38]
Lukáš Kellerstein: Ale nemůžu mu teďkom bohužel vypnout. Jakoby to Search web.
[01:21:38] - [01:21:54]
Lukáš Kellerstein: Protože když mu napíšu tenhle ten text, Tak on začne automaticky
dělat search web. Jo, tady uvidíte, že jako tady si budete vidět. Podívám se na inzeráty
Searching the Web, Jo, a používá ten Tool Search web. Protože to asi pro ně jednodušší.
[01:21:54] - [01:22:04]
Lukáš Kellerstein: Takže já jenom, abych ho přesvědčil, že má použít ten Play Wright, tak
bych to musel napsat. Najdi mi nejlejší suber impresa v České republice. A použiji
browser nebo něco takovýho.
[01:22:05] - [01:22:06]
Lukáš Kellerstein: A teď mu to můžu napsat tady.
[01:22:07] - [01:22:17]
Lukáš Kellerstein: Ale já. Chci, abys abys použil Browser. Jo, teď doufám, že už to tak
bum
[01:22:18] - [01:22:20]
Lukáš Kellerstein: a v tu chvíli on si to uvědomí.
[01:22:21] - [01:22:28]
Lukáš Kellerstein: A Pou. Čte si skill. Teď mě to zarazilo že se, tady čte Skill. On se bude
chtít připojit na ten cloud Desktop
```

## Strana PDF 39

```text
[01:22:29] - [01:22:31]
Lukáš Kellerstein: na ten Cloud In Browser.
[01:22:33] - [01:22:38]
Lukáš Kellerstein: Jo, ale po. Ale jo. Ale von se otevírá. Vnitřní. Jo, já už to rozumim.
[01:22:39] - [01:22:59]
Lukáš Kellerstein: Tak to sem Taky nechtěl. Tady mají ještě ten vnitřní brouser. To sou
tady novinky, který tady dřív nebyly. Takže třeba udělám, že si otevřu novou dám mu,
Tam eh? Najdi mi nejlevnější, nejlevnější Subaru Subaru. Impreza,
[01:23:00] - [01:23:06]
Lukáš Kellerstein: Včrinitial. A použiji Play Ride. Vím, že tam mám Ty překlepy, kašlu na
to,
[01:23:08] - [01:23:20]
Lukáš Kellerstein: Tak a teď by jako já bych neměl nic dělat. A Von by si měl otevřít
browser. Měl byste tam začít klikat teďkom. Von se vás začne automaticky ptát, jestli
může ten ty tůly v tom play Write u použít.
[01:23:21] - [01:23:25]
Lukáš Kellerstein: Takže tady chce udělat Page Snapshot. Jo, vidíte, On si chce
přečístmlinitiallangenglish,
[01:23:26] - [01:23:40]
Lukáš Kellerstein: který teďkon vidí. Takže já mu to. Buď mu to dovolím jednou a na
další Page Snapshot Tool se mě zeptá znova nebo mu řeknu Always Allow. To znamená,
že tenhle ten Tool Page Snapshot ti dovoluju poku použít a už se mě na To nemusíš
ptát,
[01:23:41] - [01:23:44]
Lukáš Kellerstein: ale Play Write má samozřejmě těch toolů třeba padesát.
[01:23:45] - [01:23:49]
Lukáš Kellerstein: Takže teď se nás to párkrát jakoby bude ptát já, jenom abych Tady,
[01:23:49] - [01:24:06]
Lukáš Kellerstein: eh, mu trochu pomohl. Tak to tady zavřu Todle to A teď dám Always
Alo. A teď von zase bude chvíli něco dělat, bude používat ten playvride. Já zase nic
nebudu dělat. Von by si tam měl seřadit nebo dát tam to suba impreza, seřadit si to
Podle nejlevnějšího. Jo a,
[01:24:07] - [01:24:12]
Lukáš Kellerstein: eh, dospět postupně k tomu, že mi tam toho Subaru impreza
nejlevnější najde,
[01:24:13] - [01:24:23]
Lukáš Kellerstein: Případně se použije jiný stránky a tak dále. No a tady mi něco z toho
vyplivne. Takže jenom abyste viděli vlastně to použití toho
Langenglishinitialmcpinitiallangenglish serveru jako
[01:24:24] - [01:24:32]
Lukáš Kellerstein: vizuálně a ještě tady Mám jednu demonstraci, Eh, kterou vám chci
ukázat nebo vyzkoušet tady s váma tady před hodinou
```

## Strana PDF 40

```text
[01:24:32] - [01:24:43]
Lukáš Kellerstein: konfiguroval. Protože tady mám novej počítač nebo novější, Kde sem
to ještě nezkoušel? Tak, eh, sem rozjel ten blender, Jak jsem vám říkal, i minulou
hodinu.
[01:24:43] - [01:24:55]
Lukáš Kellerstein: Blender má taky initialmcpinitial server oficiální A teďkon sem ho tady
napojil. Na to je trochu jiná verze toho klódu. Ještě o něm párkrát budu mluvit, takže,
eh,
[01:24:56] - [01:25:04]
Lukáš Kellerstein: jako lehce, Jenom není to předmětem tohodle toho kurzu. Na to mám
právě jinej kurz. Kde se vo Tom bavim? Vyloženě tady vo těch kódovacích agentech,
[01:25:04] - [01:25:12]
Lukáš Kellerstein: Ale, eh, jenom abysme si to připodobnili. Mám tady nakonfigurovanej
ten initialmcpinitial server a teď mu tady dám ňákej prostě úkol
[01:25:12] - [01:25:25]
Lukáš Kellerstein: a teď von by si zase měl začít povídat s tím blendrem. Vlastně lokálně.
A měl by mi tam bejt schopnej v tom blender u začít vlastně tvořit, ňáký ty tři. D prvky a
já. Sem mu tady dal aby udělal,
[01:25:26] - [01:25:32]
Lukáš Kellerstein: low poli to znamená. Že To bude, mít eh málo Eh,
[01:25:34] - [01:25:50]
Lukáš Kellerstein: málo. Teď nevim, jak to vysvětlit. Málo detailů. Vlastně ten objekt.
Když udělám kouli, a bude low poli, tak to bude taková takovej Takový složený z des
jako z destiček. Nebo je to koule? Jo, vidí tam to Low. Poli, ty trojúhelníky.
[01:25:50] - [01:26:07]
Lukáš Kellerstein: Tak čim větší poli tak. Tim víc. Tim menší jsou ty trojúhelníčky. A ta
koule je detailnější. Čim víc. Low poli. Tak Tim, ty trojúhelníčky sou větší jo. Ale, Výsledek
toho je, že prostě umí ovládat ten initialmcpinitial přes initialmcpinitial server celej ten
blender, Protože ten blender
[01:26:08] - [01:26:18]
Lukáš Kellerstein: mu mu vyexpouzoval, dal mu k dispozici ty funkcionality, který může
mít. No a já tady pak teda tím pádem vidím. Prostě tady celýho toho. Takže
[01:26:18] - [01:26:20]
Lukáš Kellerstein: tam pak máte v Různejch,
[01:26:20] - [01:26:44]
Lukáš Kellerstein: Eh, různý Modely Maj různý úrovně. Eh, sou různě dobrý ve tři D
prostoru. Teď ty nový antropic. Modely jsou dobrý. Jsou taky Dobrý, takže když mu
dejte, dáte něco jako navrhně mi dům, Prostě, kterej se mi vejde na tu takovouhle
parcelu a chce, aby to Mělo todle todle, todle. Tak von vám vlastně je schopnej
takovýdle tři dé věci udělat.
[01:26:44] - [01:26:55]
Lukáš Kellerstein: Udělej mi Ferrari Tady pro děti. Já to tady Vyjde tři dé tiskuju. Tak to
jsou věci, který už dneska vlastně ty modely taky docela dobře uměj. Neříkám, že tam
nebudou
```

## Strana PDF 41

```text
[01:26:56] - [01:27:03]
Lukáš Kellerstein: zádrhely, že Tam nebudou vlastně nějaký plochy, který budou
papírově tenký. Jo, takže
[01:27:03] - [01:27:08]
Lukáš Kellerstein: a tak dále. Neříkám. To je stoprocentní, ale jako už se to vo dost
zlepšilo.
[01:27:09] - [01:27:11]
Lukáš Kellerstein: Takže to je jenom další ukázka toho initialmcpinitial serveru.
[01:27:15] - [01:27:17]
Lukáš Kellerstein: Tak dobře, já na tobě to vysvětlím.
[01:27:18] - [01:27:24]
Lukáš Kellerstein: Eh, není vhodné, protože volat exist našeho systému. Tak tomu se
ještě taky dostaneme.
[01:27:26] - [01:27:39]
Lukáš Kellerstein: Tak to je jenom, eh. Tak to je Initialmcpinitial. Sever Ňáká. Ukázka
toho jak, to jednoduše Využít jak to jednoduše jako, eh, použít existující teďkon. Jaká je
ver? Pro rozdíl mezi verzí jedna a dva
[01:27:40] - [01:27:44]
Lukáš Kellerstein: Verze jedna byla stavová, a Udržovala si sešnu
[01:27:44] - [01:27:50]
Lukáš Kellerstein: a verze dva je bezestavová. To znamená, že to je ohromnej rozdíl. A
Teďkon
[01:27:51] - [01:27:58]
Lukáš Kellerstein: takhle šel čas zhruba jako s initialmcinitial Péčkama. A jak se
přidávali? Jako, jak se rozvíjely?
[01:27:58] - [01:28:11]
Lukáš Kellerstein: A tadydle. Vlastně, v tuhle tu chvíli se rozhodli, že to utnou a začnou
psát Verzi dva, která je Stateless, stejně jako je Initialhttpinitial. Protokol Vlastně
Stateless. Takže začali initialmcpinitial. Jedna
[01:28:12] - [01:28:21]
Lukáš Kellerstein: která byla vhodná na ňáký věci ale, rychle si uvědomili, že to není
vlastně sladěný
[01:28:22] - [01:28:27]
Lukáš Kellerstein: s tím protokolem, kterej vlastně, přes kterej by to vlastně mělo celý
jed,
[01:28:27] - [01:28:43]
Lukáš Kellerstein: To znamená, že z Tý statefle éry se přešlo do Stateless éry a má to
několik dopadů. Zase budu vo tom mluvit, ale abych vám vysvětlil, proč je to tak
důležitý. Vy máte zdrojový kódy pro tu verzi jedna, tady,
[01:28:44] - [01:28:53]
Lukáš Kellerstein: abyste jako nepřišli o tom, že já jsem na to v kurzu jsem to
samozřejmě taky používal. Takže abyste jenom, eh, v případě, že vás to zajímá,
```

## Strana PDF 42

```text
[01:28:59] - [01:29:06]
Lukáš Kellerstein: tady tu verzi máte, Ale pokud se to učíte Nově tak vlastně asi
pravděpodobně pudete tou verzí dva
[01:29:07] - [01:29:11]
Lukáš Kellerstein: je. Tam jedna situace kdy, ty verze mezi sebou jakoby, nejsou
kompatibilní
[01:29:12] - [01:29:15]
Lukáš Kellerstein: zase. To budu mít v tý prezentaci Takže tomu řeknu něco víc.
[01:29:15] - [01:29:22]
Lukáš Kellerstein: Tadydle pak sou ukázky Initialsdinitial v tý verzi jedna. A tadydle byla
eště jedna taková Verze,
[01:29:23] - [01:29:36]
Lukáš Kellerstein: která se, eh, rychle stala obsolí a nahradila to vlastně ta
Streamblinitiallangenglish. Takže tady máte případně ve verzi jedna, My si to budeme
ukazovat tadydle
[01:29:39] - [01:29:46]
Lukáš Kellerstein: tadydle v tý složce jedna Tak tady máme vlastně initialsdinitial a
initialhttpinitial.
[01:29:47] - [01:29:51]
Lukáš Kellerstein: A máme tady server, kterej ty tůly vy expozuje,
[01:29:51] - [01:30:00]
Lukáš Kellerstein: hledatepo způsobem. A jo, způsobem. Jo, Takže ještě si to ukážeme v
kódu, jenom abyste jako vo nic nepřišli.
[01:30:00] - [01:30:08]
Lukáš Kellerstein: Jenom Spíš chci říct, že, eh, Tady byla nějaká evoluce a takdlenc to
útlo. Tím bych tu verzi jedna
[01:30:09] - [01:30:10]
Lukáš Kellerstein: tak nějak uzavřel.
[01:30:12] - [01:30:16]
Lukáš Kellerstein: Eh, tadydle. Máte teda tu adresenářovou strukturu
[01:30:16] - [01:30:23]
Lukáš Kellerstein: a Tadydle je nějakej popis k tomu. Takže to to asi můžeme už
přeskočit Jenom zase, abysme ušetřili ňákej čas
[01:30:24] - [01:30:30]
Lukáš Kellerstein: tadydle. Pak. Máte verzi jedna Jak to vypadala implementace? A tady
pak máme verzi dva. A jak vybrala implementace?
[01:30:31] - [01:30:35]
Lukáš Kellerstein: To znamená, že to důležitý, co si z toho vodnýst je, že dřív
[01:30:36] - [01:30:44]
Lukáš Kellerstein: nejjednodušší způsob, jak se moh psát. Initialmcpinitial. Server bylo
takzvaný. Fast Langenglishinitialmcpinitiallangenglish který Řeklo. Hele
[01:30:45] - [01:30:50]
Lukáš Kellerstein: já budu psát Initialmcpinitial Server pomocí Fast
Langenglishinitialmcpinitiallangenglish. A todle bude jeho jméno.
```

## Strana PDF 43

```text
[01:30:51] - [01:30:56]
Lukáš Kellerstein: Tadydle Mám initialmcpinitial. Tool. To je ten náš Get Stock Price. Jo,
[01:30:57] - [01:31:00]
Lukáš Kellerstein: a tajdle Pouštím ten initialmcpinitial server.
[01:31:01] - [01:31:06]
Lukáš Kellerstein: Takže by tendle initialcpinitial Server má jenom jeden jeden tůl.
[01:31:07] - [01:31:09]
Lukáš Kellerstein: Tadydle. Dole je klient.
[01:31:09] - [01:31:18]
Lukáš Kellerstein: Neboli jak vlastně, když to budu chtít použít jenom Initialcpinitial
server. Tak ten klient je potřeba aby, použil
[01:31:19] - [01:31:21]
Lukáš Kellerstein: bez toho Je To k ničemu
[01:31:22] - [01:31:28]
Lukáš Kellerstein: takže. Tadyhle ten klient já. Se k těm klientům hned dostanu. Jenom
chci říct, upozornit tu ten rozdíl mezi těma serverama.
[01:31:29] - [01:31:39]
Lukáš Kellerstein: To, znamená eh, pro, Eh, pro verzi dva se přejmenovalo fast
initialmcpinitial na initialmcpinitial server.
[01:31:43] - [01:31:56]
Lukáš Kellerstein: Řeklo se, že initialmcpinitial Tooly nebudou používat tady tu taj. Ten
dekorátor. Initialmcpinitial. Tečka tool, ale budou používat server tečka, tool Takže to je
pak tady ten tool. Jinak implementace je stejná.
[01:31:57] - [01:32:01]
Lukáš Kellerstein: Ten server. Teda, ten, co byl tady, tak je tady,
[01:32:05] - [01:32:07]
Lukáš Kellerstein: Zase se jmenuje finance, stejně jako předtím.
[01:32:08] - [01:32:09]
Lukáš Kellerstein: A tadydle. Tim ho zase pustim.
[01:32:11] - [01:32:19]
Lukáš Kellerstein: Jo, takže spousta toho zůstala stejný. Jenom se to trochu
přejmenovalo, hned vysvětlim, proč Proč se to Fast
Langenglishinitialmcpinitiallangenglish zmizelo z tý verze dva.
[01:32:20] - [01:32:24]
Lukáš Kellerstein: Je to, eh, změna k lepšímu, ale říkám hned vysvětlim, proč
[01:32:25] - [01:32:34]
Lukáš Kellerstein: a teďkon tady Máme ty klienty. To znamená, že tadydle vidíte u toho
klienta tu stavovost. Protože tadydle otevři. Sešnu
[01:32:36] - [01:32:39]
Lukáš Kellerstein: A tadydle jsou ty dvě metody, vo kterých já jsem mluvil. Tadydle je to.
[01:32:40] - [01:32:41]
Lukáš Kellerstein: Vrať mi všechny tůly.
```

## Strana PDF 44

```text
[01:32:42] - [01:32:49]
Lukáš Kellerstein: A tadydle je ukázka jeden ten tour. Zavoláme a bude to teda tadydle
Ten tůl Get Stock Price.
[01:32:50] - [01:32:51]
Lukáš Kellerstein: S tímhle tím argumentem.
[01:32:52] - [01:32:55]
Lukáš Kellerstein: Jo, ale důležitý tady je,
[01:32:55] - [01:33:05]
Lukáš Kellerstein: že se tady vlastně musí vodevřít Tahle, ta sešna, to je ta stavovost A
jakýkoli kóly, který děláte, musíte dělat v rámci tý jedný sešny.
[01:33:05] - [01:33:07]
Lukáš Kellerstein: To se právě změnilo
[01:33:07] - [01:33:15]
Lukáš Kellerstein: tadydle v tý do toho, Druhým způsobu Tady není žádná sešna. Žádná
Tady sešna není. Je tady jenom vodevři klienta
[01:33:16] - [01:33:20]
Lukáš Kellerstein: a tady už je jako volej tuli, Jo,
[01:33:21] - [01:33:30]
Lukáš Kellerstein: takže Výrazný zlepšení toho stavu. A teď, proč je to jako důležitý
tadydle? Je taková zase animace, abyste viděli ty věci, který se změnily,
[01:33:30] - [01:33:35]
Lukáš Kellerstein: ehm, Místo těch mejch šipek tam možná todle bylo lepší, kdybych
ukázal.
[01:33:36] - [01:33:48]
Lukáš Kellerstein: A teďka, když budu chtít jeden ten tůl zavolat tak tadydle zase je Ta
verze jedna. A co se stane? A tadydle je verze dva. Co se stane, abyste jenom viděli ten
počet rekvestů, který se musí udělat. Jo,
[01:33:49] - [01:33:51]
Lukáš Kellerstein: takže tady se volaj tři tůly.
[01:33:51] - [01:33:56]
Lukáš Kellerstein: Volá se tady jeden tůl a dostanu odpověď. Druhej tůl a třetí tůl.
[01:33:57] - [01:34:01]
Lukáš Kellerstein: A mezitím tady je ta sešna prostě, která se musí vodevřít.
[01:34:01] - [01:34:04]
Lukáš Kellerstein: A ta musí bejt otevřená po celou dobu, kdy já si s ním takhle povídám,
[01:34:06] - [01:34:09]
Lukáš Kellerstein: toho se chtěli zbavit a toho se taky zbavili.
[01:34:10] - [01:34:24]
Lukáš Kellerstein: Takže teď už to vypadá jako initialhttpinitial volání. Když volám
normální Langenglishinitialapiinitiallangenglish server takže jeden tool Druhej tu třetí
toul. Žádná sešna, votevřená, nic. A ty informace, který vlastně předtím byly v tý sešně
takhle. Třeba to Session Langenglishinitialidinitiallangenglish
```

## Strana PDF 45

```text
[01:34:25] - [01:34:28]
Lukáš Kellerstein: Se nám vlastně přestěhovalo tady do takovýdleho Metatagu.
[01:34:29] - [01:34:33]
Lukáš Kellerstein: Takže To je jenom, abyste věděli, že tam jako u
[01:34:34] - [01:34:44]
Lukáš Kellerstein: to, že to není, by default stavový neznamená, že vy si to nemůžete
udělat. Stavový. Jo, ale ne, nevyžaduje to ten stav. Takže ta
[01:34:45] - [01:34:54]
Lukáš Kellerstein: ta sešna, eh, vlastně přestala a začalo to bejt Stateless jako request
respons, protokol, Stejně jako zbytek toho webu.
[01:34:55] - [01:34:58]
Lukáš Kellerstein: Takže vopravdu. Je to usnadnění.
[01:34:58] - [01:35:02]
Lukáš Kellerstein: Tak pojďme se teďkon podívat do kódu, Já se teďka podívám.
[01:35:04] - [01:35:12]
Lukáš Kellerstein: Já možná todle ještě dokončím, protože tadydle je ukázka verze jedna
kódů. To my si ukazovat nebudeme,
[01:35:13] - [01:35:26]
Lukáš Kellerstein: takže pojďme rovnou Na todle to znamená, proč ta verze dva? Proč na
tom záleží? Záleží na tom proto, protože, eh, tím, že je to bezestavový, tak Vy to
najednou můžete škálovat,
[01:35:26] - [01:35:30]
Lukáš Kellerstein: stejně jako jakýkoliv jiný Langenglishinitialapiinitiallangenglish
servery.
[01:35:30] - [01:35:35]
Lukáš Kellerstein: To znamená, že není problém v tom, že, eh,
[01:35:36] - [01:35:52]
Lukáš Kellerstein: budete mít, bude jeden Klient, jeden agent. Když si povídá s jedním
serverem, tak si vlastně musel pořád povídat s tím samym. A teď, co když já budu mít
jako potřebuju naškálovat. A potřebuju mít víc instancí tohodle toho jednoho.
Initialmcpinitial. Serveru
[01:35:53] - [01:35:55]
Lukáš Kellerstein: tak mám docela problém, protože
[01:35:55] - [01:36:08]
Lukáš Kellerstein: ty klienti, který byli připojený K tomudle. Initialmcpinitial serveru.
Musej tam zůstat, protože tam ta stavovost, ta sešna mezi nima a jakýkoli nový. Teda, Já
začnu připojovat jako k tomu dalšímu initialmcpinitial server u.
[01:36:08] - [01:36:16]
Lukáš Kellerstein: Jo, Ale todle není jako správně. Jak se škálování? Dělá todle, Když
budu chtít jako Round Robin,
[01:36:17] - [01:36:29]
Lukáš Kellerstein: jo, tak Ne, nemůžu udělat Round Robin. Protože teďkon. Co je Round
Robin? Eh, každej novej request pude na ten na tu instanci toho initialmcpinitial serveru,
Která zrovna je nejmíň vytížená,
```

## Strana PDF 46

```text
[01:36:30] - [01:36:35]
Lukáš Kellerstein: abych jako rozprostřil ten výkon mezi tři stejný servery,
[01:36:35] - [01:36:43]
Lukáš Kellerstein: tak jako chci. Jakejkoli novej request pude, tam protože ten Je nejmíň
vytíženej. A takhle hezky jako rozprostíráte ten výkon mezi ty tři.
[01:36:44] - [01:37:00]
Lukáš Kellerstein: Když to když jste měli tu sešu, tak jste to nemohli udělat ste museli
držet tu konektivitu. To znamená jedna jedna důležitá věc, když se ten server nestartuje.
Jakože v Kuberneties, třeba musíte brát, že Jakejkoli pot v jakejkoli. Okamžik, se může
zabít,
[01:37:01] - [01:37:17]
Lukáš Kellerstein: že to kubernetýzo zabije. Prostě. Takže tam nemůžete držet ten stav,
teda když by se vám stalo. A ten. To by vám vlastně. Ten pot by se zabil. Nebo
restartoval by se ten server, Tak ty klienti, který měli tu sešnu a povídali si S tím
serverem by ztratili najednou všechno.
[01:37:18] - [01:37:21]
Lukáš Kellerstein: Nebyla by tam ta sešna. Začali by jim vracet chyby,
[01:37:22] - [01:37:34]
Lukáš Kellerstein: kdežto když máte ty tři servery a každej je schopnej to vodbavit. Tak je
úplně jedno, že umře. Tak to ten balancer Pošle na tenhle server nebo na tenhle server.
A když tam není ten stav, tak je to prostě jednodušší.
[01:37:36] - [01:37:43]
Lukáš Kellerstein: A jeden request je teda jeden jednak jeden krátkej tůl Kol. Není tam
teda žádný, eh, žádný
[01:37:44] - [01:38:01]
Lukáš Kellerstein: žádnej problém. Vlastně s ňákym dlouhotrvajícím úkolem kterej se
tam jako řeší agent potřebuje tůl zavolá se, tůl. Vrátí se zpátky. Ta ta rozho, ten strom,
rozhodování. A ten lup žije pořád. Vlastně na tom eh. Aplikačním servu, kde běží ten
agent,
[01:38:03] - [01:38:10]
Lukáš Kellerstein: Tak a můžou tím pádem vznikat tydle. Ty gateway E může se řešit
kešování může. Se Řešit
[01:38:11] - [01:38:22]
Lukáš Kellerstein: autentizace a autorizace a různý všechny Tydle ty věci, který se řešily
na normálnim langenglishinitialapiinitiallangenglish Serveru toto. Všechno vlastně tím
pádem se jako
[01:38:22] - [01:38:28]
Lukáš Kellerstein: enejblovalo takže. Najednou, se to sladilo s Tím, jak my
programujeme věci.
[01:38:29] - [01:38:39]
Lukáš Kellerstein: Tak co se změnilo nebo co se stalo? Deprekated přeskočím a více
méně. Tadydle máte, Eh, co je toto, State Less. A tadydle je ta verze jedna.
```

## Strana PDF 47

```text
[01:38:40] - [01:38:56]
Lukáš Kellerstein: Mě to prostě musí jít pořád na tu jednu stejnou na ten jeden stejnej
stroj a Tadydle ta replika B. Prostě tam to nemůže jít. Kdežto u toho, U toho, U tý verze
dva, Tady to může jít, kam chce, Když mám ňáký tři instance
[01:38:59] - [01:39:04]
Lukáš Kellerstein: tak, todle to můžem přeskočit initialmcpinitial. Onvirer Tak.
[01:39:05] - [01:39:06]
Lukáš Kellerstein: Jo
[01:39:06] - [01:39:19]
Lukáš Kellerstein: tadydle, Mám. Teda to initialsdinitiallangenglish A Stream Byl
eštpinitiallangenglish ukázaný Eště, eh, jako vizuálně. To znamená, že spíš je tady
důležitý, že? Todle to jako běží na tom jednom stroji, To je to One Machine
[01:39:19] - [01:39:26]
Lukáš Kellerstein: A to Stream u byl Langenglishinitialhttpinitiallangenglish. Pokuď
pominu situaci, že si to pustíte. Ten Langenglishinitialmcpinitial server lokálně
[01:39:26] - [01:39:40]
Lukáš Kellerstein: tak což jako to není ten účel, abyste ho pouštěli lokálně. Většinou.
Chcete mít nasazený někde jinde na jinym stroji ať. Už je to v rámci vnitřní sítě ve firmě
A nebo je to úplně jako.
[01:39:41] - [01:39:42]
Lukáš Kellerstein: Jako ven do internetu?
[01:39:43] - [01:39:47]
Lukáš Kellerstein: Jo, takže tydle Ty v tom stream ové to vlastně běží na dvou různejch
[01:39:48] - [01:40:07]
Lukáš Kellerstein: strojích. Takže to by byl ten základní rozdíl. Jak říkám, většinou, se
snažíte psát ty initialmcpinitial servery tím streamblittpinitiallangenglish Způsobem ale,
jsou situace kdy, To nechcete psát? Chcete to psát jako initialsdinitiallangenglish. A to je
třeba ten Play Write.
[01:40:07] - [01:40:19]
Lukáš Kellerstein: Ten playvright byste takhle nenapsali. Nenapsali byste to jako
Streamtpinitiallangenglish. Museli byste vy mít nějakej server. A ten prohlížeč by se
votvíral. Vlastně, na tom serveru. Kde běží ten initialmcpinitial. Server
[01:40:20] - [01:40:27]
Lukáš Kellerstein: to úplně Vždycky nechcete. Můžete, Může to bejt záměr, Ale to, co
sem třeba demonstroval tady já.
[01:40:27] - [01:40:44]
Lukáš Kellerstein: Tak to to bych vlastně jako, jako, mohl bych to pustit. Mohl bych
takovejdle server vytvořit a dát ho k dispozici lidem, Ale třeba to, abych jakoby viděl, že
jak tam kliká, tak To bych neudělal. Bez toho se teda jo.
[01:40:45] - [01:41:01]
Lukáš Kellerstein: Takže říkám sou různý způsoby. Jako třeba ten blendr. Taky. Jo, to
většinou chcete mít ten Initialsdinitial způsob, aby si mezi sebou povídal. Ten blender Je
možný že ten blender vys vyexpózovává server a ten můj agent si
```

## Strana PDF 48

```text
[01:41:01] - [01:41:10]
Lukáš Kellerstein: tímhle tím Stream s ním povídá. Já se teďkon nevybavuju. Která tam,
kterou tou verzí voni šli, ale běží to. Každopádně lokálně.
[01:41:11] - [01:41:13]
Lukáš Kellerstein: Jo, ale zase kdyby To bylo stream. U byl Eště
Langenglishinitialtpinitiallangenglish.
[01:41:14] - [01:41:23]
Lukáš Kellerstein: Mohlo by to bejt poskytovaný jako služba. Vy byste mohli mít servery
kde bude blender Langenglishinitialmcpinitiallangenglish tam Budou ty blender y
vlastně jako
[01:41:23] - [01:41:40]
Lukáš Kellerstein: pouštěný A uživatel si jenom řekne chci. Vyrenderrovat todle a vy mu
to tam vyrendrujete a pošlete mu Nějakej exportní Prostě obrázek toho nebo exportní
faj, kterej von zase může poslat nám. Ale do společnosti, která dělá tři dé tisk a rovnou
se mu to vyt jako vytiskne.
[01:41:42] - [01:41:50]
Lukáš Kellerstein: Tak pojďme se podívat do kódu. A pak už já tady mám, eh, dvacet pět,
Já se jenom Takhle podívám rychle.
[01:41:51] - [01:41:56]
Lukáš Kellerstein: To je to, co je v tom Langenglishinitialrpcinitiallangenglish. Když se
pustí aplikace,
[01:41:58] - [01:42:02]
Lukáš Kellerstein: já teď přemejšlím, jestli budeme chtít koukat do toho kódu. Jak
hluboko.
[01:42:03] - [01:42:06]
Lukáš Kellerstein: Já bych se podíval. Já bych to ukázal spíš takhle,
[01:42:10] - [01:42:16]
Lukáš Kellerstein: protože já jsem ještě vlastně neřek, že tady jsou tři způsoby,
[01:42:18] - [01:42:20]
Lukáš Kellerstein: Tak, a to je tady. Ano, to je tady.
[01:42:23] - [01:42:33]
Lukáš Kellerstein: Tak já budu pokračovat v tý prezentaci a pak se koukneme do toho
kódu, protože Já myslím, že todle by teďkom dávalo větší smysl já. Jsem měl já Jsem
chtěl ukázat jednu část toho
[01:42:33] - [01:42:36]
Lukáš Kellerstein: a, pak eh, ukázat, ten zbytek.
[01:42:37] - [01:42:39]
Lukáš Kellerstein: To bych vlastně taky moh.
[01:42:39] - [01:42:53]
Lukáš Kellerstein: Tak ukážeme jednu tady. Jednu věc, abyste viděli to initialsdinitial. A Jo
a P v praxi, tak na tý serverový straně. To vlastně znamená jenom todle. To znamená, že
já to ještě možná zkusim zvětšit.
```

## Strana PDF 49

```text
[01:42:56] - [01:43:01]
Lukáš Kellerstein: Tak Tak to vlastně znamená jenom todle Tady jsem definoval dva tůly
[01:43:03] - [01:43:10]
Lukáš Kellerstein: a tadydle sem, Eh, si řek že, to bude to a. Teď já jsem ukázal špatnej
já. Jsem chtěl ukázat Tadle.
[01:43:11] - [01:43:12]
Lukáš Kellerstein: Tak
[01:43:13] - [01:43:20]
Lukáš Kellerstein: tím pádem řeknu, že to je. Chci, aby to byl ten initialmcpinitial server.
Tadydle jsou ty dva tůly, jeden druhej
[01:43:20] - [01:43:26]
Lukáš Kellerstein: a Tadydle Přitom když to pouštím ten server, tak buď se rozhoduju, že
to bude Streambl. Eště tepinitiallangenglish
[01:43:27] - [01:43:29]
Lukáš Kellerstein: a bude tady mít teda ten host A Port.
[01:43:30] - [01:43:36]
Lukáš Kellerstein: A nebo to bude vlastně initialsdinitial. Jo, a pak tím pádem to
ovlivňuje,
[01:43:37] - [01:43:44]
Lukáš Kellerstein: Jak ten klient k němu bude přistupovat, to znamená, Mám tady
klienta na kdy vlastně říkám.
[01:43:45] - [01:43:55]
Lukáš Kellerstein: A to je. To. Je, eh, důležitý, že to s D a. Jo, když je tady to s D a. Jo, tak
říkám. Hele, budeš to pouštět jako. Jako
[01:43:56] - [01:44:00]
Lukáš Kellerstein: tímhle tím komandem a budeš pouštět Tenhle ten skript
[01:44:01] - [01:44:04]
Lukáš Kellerstein: že vidíte, že I tím způsobem já můžu vlastně
[01:44:05] - [01:44:14]
Lukáš Kellerstein: jako lokální skripty pouštět. Já to nepotřebuju mít nutně jako
komitnutý někde v initialmpminitial nebo komitnutý v pipu.
[01:44:15] - [01:44:28]
Lukáš Kellerstein: Já můžu pouštět takhle i lokální, který si vyvíjím. Jo, a pak je důležitý
to, že si vodvírám toho klienta. Říkám, hele, vrať mi Všechny tůly A tenhle ten Tool. Budu
volat tadydle. Ten Kol Tool. Budu volat
[01:44:28] - [01:44:36]
Lukáš Kellerstein: tadydle takhle. Call Tool. Metoda se bude volat. Ten Tool se jmenuje
takhle. A todle To sou ty argumenty.
[01:44:37] - [01:44:39]
Lukáš Kellerstein: Jo, a to přímo sedí
[01:44:39] - [01:44:47]
Lukáš Kellerstein: proto. Co vlastně ten server dělal nebo vy expozuje? Jo, Todle je ten
tool, Eh, et
```

## Strana PDF 50

```text
[01:44:48] - [01:44:51]
Lukáš Kellerstein: A tadydle to byly ty argumenty, který se tam do toho poslali.
[01:44:52] - [01:45:00]
Lukáš Kellerstein: Když je to initialhttpinitial, tak je To samozřejmě trošku jiný, Protože
tadydle má, musíme mít ňákym způsobem initialurlinitial. Adresu.
[01:45:01] - [01:45:04]
Lukáš Kellerstein: Tady nemáme vlastně. Nějakej ko žádnej. Komand
[01:45:04] - [01:45:14]
Lukáš Kellerstein: a žádný argumenty máme. Jenom initialurlinitial adresu. A pak je
tady. Vraťme všechny Touly a zase tadyhle. Zavolej ten Tool a Et a s těmadle těma
argumentama,
[01:45:17] - [01:45:28]
Lukáš Kellerstein: tak Vy z toho dostanete odpověď A to se tady jenom vyprintí. Takže
jenom zase jako krátce jenom. Abyste věděli jak, to funguje ten, initialsdinitial A Hotte
pro způsob.
[01:45:30] - [01:45:37]
Lukáš Kellerstein: Tak a teď další, eh, poměrně důležitá věc, aby vás to nemátlo. Tak to
je jenom, eh,
[01:45:38] - [01:45:52]
Lukáš Kellerstein: Jason, co to obsahuje vevnitř. Já myslím, že todle to můžeme přeskočit
takhle. Co se stane, když se provede to volání? To znamená, že první, co se musí, udělat,
že z toho klienta. A teďkon Eh,
[01:45:53] - [01:46:00]
Lukáš Kellerstein: todle. To je vlastně de facto na tom lokálním počítači. Dalo by se, říct,
pokuď To bude Topinitiallangenglish
[01:46:01] - [01:46:10]
Lukáš Kellerstein: a initialmcpinitial. Klient. První, co musí zavolat, je. Hele chci vidět
všechny tvoje túly a ten initialmcpinitial se mnou vrátí, Vlastně Ty seznam těch toolů
[01:46:11] - [01:46:22]
Lukáš Kellerstein: potom uživatel teda něco napíše. Do tý naší aplikace. Ta naše
aplikace. Pošle tu jeho otázku se s tím seznamem těch toolů do toho
[01:46:23] - [01:46:26]
Lukáš Kellerstein: tudle. Tu část jsme si vlastně ukazovali my v tý první hodině
[01:46:28] - [01:46:34]
Lukáš Kellerstein: teďkonu vrátí. Hele, chci tenhle. Ten tool. Zavolej Ten Search Book.
Tady Tool.
[01:46:35] - [01:46:50]
Lukáš Kellerstein: Ta aplikace zavolá na tom přes toho. Initialmcpinitial klienta. Na tom
initialmcpinitial serveru. Ten kol zavolá ten kol tool jménem Search Book s parametrem
Dun A ten mu vrátí odpověď a ta se vrátí do tý hostovací aplikace
[01:46:50] - [01:46:57]
Lukáš Kellerstein: ta ten výsledek toho Tool U se pošle do initiallminitial Ka a Initiallm ko
odpoví uživateli. Ten text?
```

## Strana PDF 51

```text
[01:46:58] - [01:47:10]
Lukáš Kellerstein: Jo, Byla tady minule taky otázka. Proč Teda to Ro nebo Proč, když se
zavolá ten tůl, Proč já nevrátím tomu uživateli odpověď z toho tůlu tady na přímo.
Vlastně
[01:47:11] - [01:47:16]
Lukáš Kellerstein: tady to nejde přímo takhle, nebo. Pardon, ta tady to nejde. Takhle
[01:47:18] - [01:47:28]
Lukáš Kellerstein: tady to nejde takhle. Protože tadydle mi přišla surová informace a já
potřebuju tu informaci jako nějak Jako dát do nějakýho textu, kterej je,
[01:47:29] - [01:47:33]
Lukáš Kellerstein: kterej odpovídá. Vlastně na tu otázku odpovídá slovně.
[01:47:33] - [01:47:35]
Lukáš Kellerstein: Jo, ne že bych mu odpověděl jako
[01:47:37] - [01:47:44]
Lukáš Kellerstein: stručně, jako To je tadydle ty fakta. Tak já mu to chci jako
přeformátovat, aby to se mu to dobře četlo.
[01:47:45] - [01:47:52]
Lukáš Kellerstein: Tak teďkon jsou tři způsoby, Jak psát ten initialmcpinitial server.
[01:47:53] - [01:48:06]
Lukáš Kellerstein: A teďkom, aby to nebylo tak jednoduchý. Jo, to znamená. Předtím. V
tý verzi jedna jsme si ukazovali, že se tam vlastně přejmenoval. Fast
Langenglishinitialmcpinitiallangenglish na initialmcpinitial Server?
[01:48:06] - [01:48:12]
Lukáš Kellerstein: To je pravda, a tydle ty dva způsoby jsou oficiální způsoby, jak se
Initialmcpinitial server Píše
[01:48:13] - [01:48:18]
Lukáš Kellerstein: je to a já upřednostňuju, nebo vám doporučuju začít tímhle tím.
Initialmcpinitial server. To Je takovej
[01:48:20] - [01:48:24]
Lukáš Kellerstein: vopravdu. Nejjednodušší způsob, jaké firmy můžete psát Pokuď ale
[01:48:25] - [01:48:33]
Lukáš Kellerstein: narazíte na něco, co v tom Initialmcpinitiallangenglish serveru. Ne,
není. A vy to potřebujete tak Je tady eště tadydle ten lowlevel způsob,
[01:48:35] - [01:48:43]
Lukáš Kellerstein: Kde vy vlastně pomocí mno většího množství kon kódu můžete
dosáhnout úplně stejnýho chování toho initialmcpinitial serveru
[01:48:44] - [01:48:47]
Lukáš Kellerstein: a eh, ale, dovoluje vám to tam dělat
[01:48:48] - [01:48:53]
Lukáš Kellerstein: větší příkusy dokola máte. Tam nad tím jakoby, mnohem větší
kontrolu
[01:48:54] - [01:49:04]
Lukáš Kellerstein: todle to je. Super na všechny ty ukázky tutoriály todle je. Prostě lidi
maj rádi todle, protože takhle to je hezky čitelný a hezky. To vypadá v tý dokumentaci.
```

## Strana PDF 52

```text
[01:49:05] - [01:49:10]
Lukáš Kellerstein: Todle je vlastně tam, kde ta síla Potom leží. Když budete potřebovat
[01:49:10] - [01:49:28]
Lukáš Kellerstein: mnohem větší kontrolu nad tím ale pokuď Nemáte jako důvod tak
nezačínejte. S tím low level způsobem jo a poku. Jenom pokuď narazíte na věc, která v
tom initialmcpinitial srovn není. A vy ji potřebujete, Tak máte tu možnost jako přejít do
toho Lowlevelu A tam tam se to vlastně jako dopsat Případně
[01:49:29] - [01:49:33]
Lukáš Kellerstein: tak jinak. Je tady Fast Langenglishinitialmcpinitiallangenglish pořád,
[01:49:34] - [01:49:44]
Lukáš Kellerstein: ale Fast Langenglishinitialmcpinitial jako takový je vlastněný úplně
jinou společností. Je to tady spole společností prefect. A ta se vo tu knihovnu bude
starat.
[01:49:46] - [01:49:48]
Lukáš Kellerstein: Není to oficiální Knihovna teda
[01:49:49] - [01:50:01]
Lukáš Kellerstein: je provozovaná Tadydle tou třetí stranou má kolikrát jakoby větší
schopnosti víc featur vám nabízí než tydle ty. Dvě vlastně jakoby, dalo by se říct oficiální
A základní,
[01:50:02] - [01:50:11]
Lukáš Kellerstein: ale eh. Ve mě to zase vzbuzuje Takovej ten pocit. No dobře, tak já to
nad tím na tom založím, celej ten svůj programátorskej kód.
[01:50:11] - [01:50:18]
Lukáš Kellerstein: A teďko najednou. Oni se rozhodnou jednoho pěknýho srpnovýho
dne že, už to podporovat nebudou nebo, že, už to nebudou roz rozvíjet.
[01:50:19] - [01:50:30]
Lukáš Kellerstein: A pak jako já mám ten problém, že? Teda jako musim to přemigrovat
tadydle na ty oficiální způsoby, takže ve mě to vzbuzuje takovou nedůvěru z tohodle
toho důvodu. Jenom jinak. Ta knihovna je dobrá.
[01:50:30] - [01:50:48]
Lukáš Kellerstein: Funguje krásně a má spoustu věcí, který třeba ty oficiální knihovny
nemaj, Takže to je vlastně tadydle popsaný, že ta v tý verzi dva je ten Fast
Langenglishinitialmcpinitiallangenglish se odebral z tý oficiální knihovny a řekl se
Dobře, spravujte si. To teda vy. Tady v prefektu v tý společnosti.
[01:50:50] - [01:50:57]
Lukáš Kellerstein: Tak teďkon. Jak je to kompatibilní mezi sebou? To znamená, že Když
máte klienta verze jedna
[01:50:58] - [01:51:06]
Lukáš Kellerstein: jako tak si povídá se serverem se serverem jedna. To je jako v
pohodě, takže tedle si povídá s Tímhle to je dobrý,
[01:51:08] - [01:51:18]
Lukáš Kellerstein: eh, klient. Verze jedna si povídá i se serverem dva, protože ten server
dva podporuje, jakoby ten starej způsob
```

## Strana PDF 53

```text
[01:51:19] - [01:51:27]
Lukáš Kellerstein: pro klienta verze jedna. Takže to je taky dobrý. Když budete psát nový
servery. Ale lidi budou používat starý klienty, tak vám to nevadí,
[01:51:28] - [01:51:43]
Lukáš Kellerstein: Pokuď samozřejmě používá. Budou používat klienta verzi dva na tom
vašem novým serveru. Verze dva. Tak to je ta ideální eh situace, Protože tam najednou
Oba dva využíváte ten State Less Protokol. Vlastně tu bezzéstavovost.
[01:51:44] - [01:51:51]
Lukáš Kellerstein: Problém je u klienta verze dva. Když bude chtít přistupovat k serveru
k tomu starýmu verze jedna.
[01:51:51] - [01:51:54]
Lukáš Kellerstein: Tak pokuď bude používat. Vlastně to Fast
Langenglishinitialmcpinitiallangenglish
[01:51:55] - [01:52:03]
Lukáš Kellerstein: nebo, eh, nebo klienta Jako toho oficiálního, tak je to pořád dobrý a
Bude si to povídat,
[01:52:04] - [01:52:07]
Lukáš Kellerstein: pokuď Ale budete používat Vlastně, jako, eh,
[01:52:08] - [01:52:18]
Lukáš Kellerstein: Discovery metodu na tom novým klientu, která je, tak ta neni vlastně
na tom serveru verze jedna, Takže tam by to začlo padat.
[01:52:18] - [01:52:27]
Lukáš Kellerstein: Takže to je jeden způsob. Vlastně jedna situace, ve který vám to
nebude fungovat, To je klient verze dva na serveru verze jedna.
[01:52:28] - [01:52:30]
Lukáš Kellerstein: Pokud používáte ten Low level klient,
[01:52:33] - [01:52:45]
Lukáš Kellerstein: tak já bych tohle to přejel. Tak teď jsou Tady ukázaný. Vlastně všechny
ty tři směry. Eh, nebo způsoby zápisu, abyste to viděli. Takže, todle, je to Fast
Langenglishinitialmcpinitiallangenglish
[01:52:46] - [01:52:56]
Lukáš Kellerstein: tadydle initialmcpinitial server je to dost podobný. Jo, Vidíte, že akorát
ten dekorátor se mění. Název toho serveru se mění ten objekt, jak je to stejně
jednoduchý
[01:52:58] - [01:52:59]
Lukáš Kellerstein: lowlevel je složitější.
[01:53:00] - [01:53:12]
Lukáš Kellerstein: Jo, tam si implementujete vlastně ty metody. Eh, vrať mi všechny tůly
a zavolej tůl. Ty se implementujete sami a zároveň sami Děláte ten přepis těch tůlů?
[01:53:13] - [01:53:20]
Lukáš Kellerstein: To vlastně v tomhle tom případě neděláte. Protože tenhle ten
dekorátor to vlastně udělá, jakoby za vás jo,
```

## Strana PDF 54

```text
[01:53:24] - [01:53:31]
Lukáš Kellerstein: tak, Eh, ten lowlevelser vyžaduje mnohem víc kódů. Takže jako jenom
pokuď, budete mít,
[01:53:32] - [01:53:44]
Lukáš Kellerstein: eh, důvod, proč používat ten lowlevel způsob, tak bys to měl používat.
Jak říkám, Initialmcpinitial. Server země je oficiální. Fast
Langenglishinitialmcpinitiallangenglish je Neoficiální, ale zase umí toho, O, dost víc
[01:53:45] - [01:53:50]
Lukáš Kellerstein: tak teď se pojďme podívat na ty tři způsoby nebo ukázat vám, kde
máte ty tři způsoby zápisu,
[01:53:51] - [01:53:53]
Lukáš Kellerstein: abyste se na ně mohli podívat.
[01:53:54] - [01:53:55]
Lukáš Kellerstein: Takže tadydle máme ten
[01:53:56] - [01:54:09]
Lukáš Kellerstein: Eh, Tři Začíná To tady ten Basic Tři a všechny ty příklady pokuď jdou
tak. Tady máte ten zápis ve všech třech způsobech
[01:54:09] - [01:54:14]
Lukáš Kellerstein: jo. Takže? Tady máte Fast Langenglishinitialmcpinitiallangenglish
Máte tady jak server.
[01:54:14] - [01:54:22]
Lukáš Kellerstein: Tak klienta máte tady a teďkom eště. Chci říct, že tadydle je jenom
[01:54:26] - [01:54:43]
Lukáš Kellerstein: my, jenom initialsdinitial Způsob Tadydle je to Ta první složka. Je
zaměřená na to, že jsou ty tři tipy zápisu Lowlevel. Initialmcpinitiallangenglish Fast
Langenglishinitialmcpinitiallangenglish všechny Initialsdinitial potom se Tady to
rozroste a řekneme dobře. Tak, Už známe všechny tři způsoby zápisu
[01:54:44] - [01:54:48]
Lukáš Kellerstein: a. Teď si ukážeme jak, to používá nebo, initialotpinitial
[01:54:48] - [01:54:54]
Lukáš Kellerstein: v tom Fast Langenglishinitialmcpinitiallangenglish způsobu v tom
Langenglishinitialmcpinitiallangenglish Server způsobu. A v tom lowlevo způsobu.
[01:54:55] - [01:55:02]
Lukáš Kellerstein: Já vám to dávám ty zdrojový kódy takhle všechny a Snažím se pokrejt
všechny možný kombinace,
[01:55:03] - [01:55:09]
Lukáš Kellerstein: abyste si nepřišli přehlcený, nebo abyste si nepřišli, že to je strašně
moc kódů. Vlastně v tom Langenglishinitialmcpinitiallangenglish
[01:55:10] - [01:55:21]
Lukáš Kellerstein: Tak Na začátek vám opravdu doporučuju zapomenout na všechno
vost jakoby vostatní a zaměřit se jenom na ten Langenglishinitialmcpinitiallangenglish
server jenom na tudle tu složku dvě
```

## Strana PDF 55

```text
[01:55:22] - [01:55:23]
Lukáš Kellerstein: a případně.
[01:55:24] - [01:55:30]
Lukáš Kellerstein: Pokud nebudete mít důvod, tak se zaměřit na ten
initialhttpinitiallangenglish způsob, protože mi to příde,
[01:55:31] - [01:55:49]
Lukáš Kellerstein: Takže jestli pochopíte initialmcpinitial server, Tak vlastně pokryjete
třeba osmdesát pět procent všech funkcionalit toho initialmcpinitiallangenglish serveru
bez problému. Jsou tam ňáký výjimky prostě ale, bude vám to stačit Na co budete
potřebovat a Zároveň pokuď vyřešíte initialhttpinitial. Způsob
[01:55:50] - [01:56:07]
Lukáš Kellerstein: tak. Ten Vám bude fungovat jak lokálně tak. V případě že, si ho
budete chtít nasadit na ňákej jinej server třeba, ve firmě a pak říct všem hele. Tak, sem
tady nasadil initialmcpinitial server a teď ty vaši Agenti ho můžou používat. Jo, tak
vlastně se naučíte. Jeden způsob,
[01:56:07] - [01:56:17]
Lukáš Kellerstein: kterej vám vystačí, Si myslim Na zase osmdesát pět procent eh, Věcí,
který, S těma initialmcpinitiallangenglish serverama budete chtít dělat? Jo,
[01:56:18] - [01:56:21]
Lukáš Kellerstein: za mě byste museli mít jakoby důvod, proč dělat initialsdinitial a jo,
[01:56:23] - [01:56:35]
Lukáš Kellerstein: dej lidi většinou začínajdinitial Ajoinitial způsobem. A pak to upgrade
u na Initialhttpinitial. Jenomže to vyžaduje to, že začnete ajoinitial a pak musíte udělat
ten upgrade, tak to, Co já vlastně se snažim naznačit? Je
[01:56:36] - [01:56:54]
Lukáš Kellerstein: Langenglishinitialmcpinitial server a initialhttpinitial. A už vlastně
nemusíte s tím nic moc dělat všem řešíte kde, to pustíte. Takže pro ty z vás, kterým se to
bude zdát hodně, Tak jenom vlastně se zaměřte tady na ten initialmcpinitial server a
tady Na toho klientpinitiallangenglish a ten server a todle to vlastně můžete odebrat.
[01:56:55] - [01:56:56]
Lukáš Kellerstein: A todle to taky můžete odebrat.
[01:56:57] - [01:56:59]
Lukáš Kellerstein: Zůstane vám tady jenom tenhle řádek
[01:57:00] - [01:57:04]
Lukáš Kellerstein: A vlastně. A tady už si jenom vytváříte svoje vlastní tůly,
[01:57:04] - [01:57:20]
Lukáš Kellerstein: Jo, takže tyhle metody si samozřejmě budete implementovat vlastní,
ale todle, jak to tady takhle vidíte, Tak to můžete Nasadit. Prostě kam chcete. V dokru,
nebo to jenom pustit? Já to tady takhle pustím jenom abyste to viděli, že to je Prostě je
[01:57:23] - [01:57:26]
Lukáš Kellerstein: Tak já jsem neměl teeme kurz.
[01:57:28] - [01:57:30]
Lukáš Kellerstein: Tak to sem tady dělal ten blender.
```

## Strana PDF 56

```text
[01:57:32] - [01:57:42]
Lukáš Kellerstein: Takže tady tady teď tady Dám pustit k terminálu na Course Juve run
[01:57:43] - [01:57:46]
Lukáš Kellerstein: server. A teď já tam dám initialhttpinitial.
[01:57:47] - [01:57:52]
Lukáš Kellerstein: Ten parametr tady, kterej je tady potřeba k tomu aby se pustila tadle
ta Verze
[01:57:53] - [01:57:55]
Lukáš Kellerstein: tak. Běží mi to tady na portu osum. Tisíc dva,
[01:57:57] - [01:58:02]
Lukáš Kellerstein: a pak si tady pustím klient a initialdtpinitiallangenglish
[01:58:03] - [01:58:18]
Lukáš Kellerstein: A tím simuluju todle Budete dávat do vašeho nějakýho agenta,
kterýho budete psát, nebo do nějakýho scriptu, kterej budete používat, abyste s tím
Langenglishinitialmcpinitiallangenglish serverem mohli komunikovat. Jo, my si zase
todle to ukážeme v zapojení
[01:58:19] - [01:58:20]
Lukáš Kellerstein: v agentovi.
[01:58:21] - [01:58:25]
Lukáš Kellerstein: V dalších hodinách Zatím si vysvětlujeme ten koncept.
[01:58:25] - [01:58:44]
Lukáš Kellerstein: Jo, todle To je skript. Jenom obyčejnej, kterej využívá ten
langenglishinitialmcpinitiallangenglish. Server. Tady byste mi klidně mohli namítnout,
tak jako na co tady potřebuju Initialmcpinitiallangenglish Server Když si takhle, tímhle
tím způsobem si můžu udělat. Langenglishinitialapiinitiallangenglish server Udělám si
langenglishinitialapiinitiallangenglish. A ve skriptu si zavolám
Langenglishinitialapiinitiallangenglish To je pravda.
[01:58:45] - [01:58:52]
Lukáš Kellerstein: A Todle to nevysvětluje. Vlastně to, jak to Zapojíme do toho Agenta.
To nejenom vysvětluje ten koncept toho Langenglishinitialmcpinitiallangenglish
[01:58:52] - [01:58:54]
Lukáš Kellerstein: přijde Tady hodina,
[01:58:57] - [01:59:00]
Lukáš Kellerstein: tak tady v Custom. Eh, v Computer Use.
[01:59:01] - [01:59:04]
Lukáš Kellerstein: A tam si ukážeme vlastní initialmcpinitial server.
[01:59:05] - [01:59:12]
Lukáš Kellerstein: A jak agent vlastně používá? Ten
Langenglishinitialmcpinitiallangenglish server. Jo, tam pudeme vo tu úroveň níž.
[01:59:13] - [01:59:20]
Lukáš Kellerstein: Tak a tadydle si to pustíme. A tadydle vidíte z toho odpovědi. Takže
tadydle sem ho volal. Jenom vrať mi všechny tůly.
```

## Strana PDF 57

```text
[01:59:21] - [01:59:24]
Lukáš Kellerstein: Vrať mi všechny tůly. Tadydle. Mám odpověď z toho,
[01:59:25] - [01:59:29]
Lukáš Kellerstein: která vlastně se vyprintila. Tady Tajdle. Ten print je tady
[01:59:30] - [01:59:41]
Lukáš Kellerstein: a pak je tady klient A A pro proces
Langenglishinitialidinitiallangenglish toho klientu a proces.
Langenglishinitialidinitiallangenglish klientů B. A tady je to stejnej proces. Ano, je to
stejnej proces
[01:59:42] - [01:59:52]
Lukáš Kellerstein: Tak jenom abyste viděli, že to je jenom prostě nastartování toho
serveru jako normálního serveru a pak zavolání ňákýho scriptu kterej, ten server bude
volat.
[01:59:54] - [01:59:54]
Lukáš Kellerstein: Tak,
[02:00:04] - [02:00:10]
Lukáš Kellerstein: ehm, Fast Langenglishinitialapiinitiallangenglish. Jo, instrukce. To si
myslím, že by měl projít.
[02:00:11] - [02:00:14]
Lukáš Kellerstein: Já bych chtěl ukázat teďkom ty rozdíly Toho
[02:00:17] - [02:00:17]
Lukáš Kellerstein: Jo,
[02:00:18] - [02:00:28]
Lukáš Kellerstein: to Je to je specifický pro tu verzi. Dva tadydle se vlastně snažíme říct,
nebo bylo řečený tou novou verzí že, všechny ty návratový typy
[02:00:30] - [02:00:37]
Lukáš Kellerstein: Těch Metod těch tůlů musej bejt typový. Jo, už to nemůže bejt jako.
Hele, já já vracím dictioner Y
[02:00:38] - [02:00:50]
Lukáš Kellerstein: a je úplně jedno, co To ten dictioner je Tady se řeklo už, že to musí
bejt jakoby typově bezpečný takže. Už se musí dělat klása která, se pak Teda jakoby
vrací z toho tůlu. Jo, tím pádem. Zase
[02:00:51] - [02:00:52]
Lukáš Kellerstein: to má ňáký
[02:00:54] - [02:01:04]
Lukáš Kellerstein: konsekvence že, máme? Tady ňákou menší chybovost a tak dále a tak
dále. Když ten tůl padne, tak víme zase, proč padnul a tak dále a tak dále. Takže to je
jenom.
[02:01:05] - [02:01:15]
Lukáš Kellerstein: No, tady to Přesně říkám, že ten Dictionary Trap vlastně se změnil a
už tam musím vlastně vracet ňákej pidentic model
[02:01:15] - [02:01:19]
Lukáš Kellerstein: jenom proto aby, prostě to ňák nepadalo. Nebo mi to
```

## Strana PDF 58

```text
[02:01:20] - [02:01:24]
Lukáš Kellerstein: to tipování nebylo, Eh, nebylo rozbitý nebo se rozbilo už
[02:01:25] - [02:01:28]
Lukáš Kellerstein: dřív, než že mi, to spadne za Rantime u
[02:01:29] - [02:01:32]
Lukáš Kellerstein: tak Zase tady mám kód. Na to tam jsou tůly.
[02:01:33] - [02:01:36]
Lukáš Kellerstein: Tak to je tadydle to ukážu.
[02:01:38] - [02:01:39]
Lukáš Kellerstein: Tadydle jsou tůly.
[02:01:40] - [02:01:45]
Lukáš Kellerstein: Tak tydle jsou server y tak Resources y a prompt y tadydle. Ty tři
složky
[02:01:46] - [02:01:52]
Lukáš Kellerstein: tůli, prompty a resources y Demonstrujou to, že ten initialmcpinitial
server teda
[02:01:53] - [02:01:58]
Lukáš Kellerstein: a teď tadydle v tom případě já už budu ukazovat jenom ten
initialmcpinitial server. Ať si to ulehčíme.
[02:02:00] - [02:02:03]
Lukáš Kellerstein: Eh, dává jako ukazuje tůly.
[02:02:04] - [02:02:07]
Lukáš Kellerstein: Jo, to, co jsme si ukázali. Do teď nic novýho.
[02:02:08] - [02:02:11]
Lukáš Kellerstein: Mám tady ale i příklady, kdy ukazuje Resources. Y
[02:02:12] - [02:02:14]
Lukáš Kellerstein: Takže vidíte, že to je server Resource
[02:02:15] - [02:02:19]
Lukáš Kellerstein: a teď Ten to jméno toho resource u je todle jméno.
[02:02:21] - [02:02:24]
Lukáš Kellerstein: A ta návratová hodnota je vlastně Jason.
[02:02:25] - [02:02:29]
Lukáš Kellerstein: Nebo je to Todle? Vlastně Vlastně tenhle kód
[02:02:30] - [02:02:40]
Lukáš Kellerstein: A zase návratová hodnota je Jason. A v tomhle Tom případě se vracej
tady jako záznamy. Jako kdyby to byly záznamy z databáze, třeba Nebo ze souborů
[02:02:40] - [02:02:42]
Lukáš Kellerstein: s těmahle těma idéčkama.
[02:02:44] - [02:02:47]
Lukáš Kellerstein: Není tady ukázanej. Teda obrázek.
[02:02:47] - [02:02:49]
Lukáš Kellerstein: Což bych tady moh teda přidat.
```

## Strana PDF 59

```text
[02:02:50] - [02:02:54]
Lukáš Kellerstein: Každopádně by to mělo jako unikátní kód, ten obrázek
[02:02:54] - [02:03:00]
Lukáš Kellerstein: A pak bysem tady vrátil, vrátil. Vlastně v mým type. U jako
langenglishinitialpnginitial nebo něco takovýho,
[02:03:02] - [02:03:11]
Lukáš Kellerstein: a nebo můžu vracet prompty, To znamená, tady je zase ukázanej
prompt. Takže máte zase jenom ten dekorátor Ten konečný slovo toho dekorátoru je
jiný,
[02:03:12] - [02:03:20]
Lukáš Kellerstein: Jinak jak tady se někdo ptal. Tak ano, všechno jsou to vlastně metody.
Protože ty Endpoint Y jsou metody.
[02:03:20] - [02:03:25]
Lukáš Kellerstein: A teď jenom rozdíl. Co to vrací tadydle, v tom případě se vrací String.
[02:03:26] - [02:03:32]
Lukáš Kellerstein: Jo, a teď je to String Template. A co jsem říkal, já? Protože tady má
tyhle ty proměnný
[02:03:33] - [02:03:42]
Lukáš Kellerstein: a Za tydle. Ty proměnný se. Dosaděj, tydle. Ty hodnoty, Co se tam, co
nám tam přišly jako parametry. Tadle jde sem a Tadle jde sem.
[02:03:43] - [02:03:45]
Lukáš Kellerstein: Ale ve výsledku nám to vrátí streng.
[02:03:46] - [02:03:56]
Lukáš Kellerstein: A zase ten server. Běží zase tou tim transportním způsobem, jakej si
nastavíte jako httpinitial, nebo Jako se to dá. Jo, všechno to vlastně jako platí zase.
[02:03:57] - [02:04:05]
Lukáš Kellerstein: Takže to jenom, abysme věděli, že jsou tady ty tři způsoby, jak říkám V
devadesáti devíti procentech. Když se budete bavit s někým vo initialmcpinitial serveru,
[02:04:06] - [02:04:08]
Lukáš Kellerstein: tak se bude Tak on bude myslet tůly.
[02:04:10] - [02:04:13]
Lukáš Kellerstein: Žádný resource y Žádný prompty, jo?
[02:04:14] - [02:04:20]
Lukáš Kellerstein: Tak pak je tady ještě kontext. K tomu. Já se dostanu v tý prezentaci a
to pak ukážu, a to si Myslím, že by nám
[02:04:22] - [02:04:31]
Lukáš Kellerstein: mohlo stačit s tím, že tadydle tadydle, tadydle.
[02:04:34] - [02:04:36]
Lukáš Kellerstein: Tak teď. Jenom jsem chtěl ukázat.
[02:04:37] - [02:04:43]
Lukáš Kellerstein: Jo, Todle, to já vysvětlím. Eh, Todle to já vysvětlím v prezentaci.
[02:04:44] - [02:04:46]
Lukáš Kellerstein: Tydle ty věci
```

## Strana PDF 60

```text
[02:04:50] - [02:04:56]
Lukáš Kellerstein: vysvětlíme v prezentaci a řeknu vám, že k tomu máte vlastně tadydle
kódy,
[02:04:57] - [02:05:02]
Lukáš Kellerstein: ale tam De. Hlavně vo to, abysme si vysvětlili jako v prezentaci. Vo
čem to je?
[02:05:03] - [02:05:06]
Lukáš Kellerstein: A vy případně k tomu najdete ty zdrojový kódy Tady,
[02:05:06] - [02:05:09]
Lukáš Kellerstein: Vrátíme se ještě k tomu kontextu? To bude takový jediný.
[02:05:15] - [02:05:20]
Lukáš Kellerstein: Tak todle. To je Resource. Takže tadydle máme takhle ten ten kód
[02:05:21] - [02:05:24]
Lukáš Kellerstein: a teď Já tady eště budu mít.
[02:05:26] - [02:05:29]
Lukáš Kellerstein: Tak jo, ještě jsem chtěl ukázat klienta, abyste věděli,
[02:05:30] - [02:05:34]
Lukáš Kellerstein: když už volám ten resource, tak ten klient vlastně volá
[02:05:35] - [02:05:40]
Lukáš Kellerstein: Zase ty dvě metody. List Resource a pak
[02:05:41] - [02:05:47]
Lukáš Kellerstein: čti Resource. Takže Túly měly. Vrať mi. Vylistuj mi všechny tůly a
zavolej tůl.
[02:05:48] - [02:06:02]
Lukáš Kellerstein: Resource, y Maj, vylistuj mě všechny Resource Y a pak přečti tenhle
ten resource. S tímhle tím kódovým označením. Jo Tadydle, přečti Resource Library
Books s Tímhle tím idéčkem.
[02:06:03] - [02:06:05]
Lukáš Kellerstein: A ten server tady měl
[02:06:06] - [02:06:18]
Lukáš Kellerstein: přesně tajdle. Ten a tadydle má ten parametr idéčko a podle toho
zase vy tady vy Vyberete to idéčko z toho souboru nebo z tý databáze a vrátíte jí ven? Jo,
[02:06:18] - [02:06:24]
Lukáš Kellerstein: jenom si dávejte prostě pozor. Ty resource Y nejsou Podporovaný
všema kódovacíma agentama.
[02:06:24] - [02:06:33]
Lukáš Kellerstein: A ty prompty taky ne z toho důvodu. Vlastně to ta adaptabilit nebo ta
komunita je neadaptovala Plně
[02:06:34] - [02:06:40]
Lukáš Kellerstein: cloud kód Je třeba umí používat, Ale protože zase
initialmcpinitiallangenglish vzniklo v Antropicu Cloud kod taky,
[02:06:41] - [02:06:47]
Lukáš Kellerstein: ale ostatní vlastně používaj initialmcpinitial servery jenom na tůly
servery Resource Y. Neuměj používat.
```

## Strana PDF 61

```text
[02:06:48] - [02:06:52]
Lukáš Kellerstein: A vlastně prompty taky ne. Jo, u toho promptu je zase na tom serveru.
[02:06:53] - [02:06:56]
Lukáš Kellerstein: Takhle to vypadá ten zápis a Ten klient.
[02:07:01] - [02:07:08]
Lukáš Kellerstein: Ten klient to používá. Zase Vylistujme všechny prompty a vrať mi
prompt
[02:07:09] - [02:07:16]
Lukáš Kellerstein: s tímhle tím jménem. A todle. To jsou ty parametry, který já chci do
toho String u vlastně poslat.
[02:07:16] - [02:07:19]
Lukáš Kellerstein: Jo, a to přesně, eh, kooperuje s tím
[02:07:20] - [02:07:23]
Lukáš Kellerstein: Review Book, a tady je titulek a Tady je tón
[02:07:24] - [02:07:28]
Lukáš Kellerstein: a todle to. Je to co, se mi vrátí akorát. Tam doplní ty parametry
[02:07:30] - [02:07:36]
Lukáš Kellerstein: tak. Pojďme se podívat na ten. Glontext Tak to jsou prompt Y.
[02:07:37] - [02:07:43]
Lukáš Kellerstein: Tak proč tu potřebuje kontext? Je tam koncept kontextu.
[02:07:44] - [02:07:59]
Lukáš Kellerstein: Proto, když budu chtít třeba ukázat progres tomu agentovi, to
znamená. Von mi zavolá nějakej tůl za in, eh, z ňáký, a. Já budu muset eh, procházet, tři
tisíce knížek a zabírá to čtyřicet sekund
[02:08:00] - [02:08:19]
Lukáš Kellerstein: tak, aby si ten tu ten agent nemyslel. Nebo ten kdokoliv používá ten
initialmcpinitial server, čili agent nemyslel, že to je, jako že se zamrzlo, nebo že to
nefunguje, tak jsem schopnej mu tím kontextem posílat vlastně ňákej progres jo. To je
novinka zase. V tý verzi dva
[02:08:19] - [02:08:31]
Lukáš Kellerstein: potom, když budu chtít volat. Vlastně v tom serveru moje vlastní data.
Takže když v jednom End Point u třeba. Nějakým tool u Zavolá se Tool a já si budu chtít
přečíst
[02:08:31] - [02:08:42]
Lukáš Kellerstein: resource. Kterej vlastně je? V tom initialmcpinitial server. U taky? Tak
přes kontext si ho můžu volat. Takže server může tím pádem volat svoje vlastní end
Point Y. Vlastně,
[02:08:44] - [02:08:51]
Lukáš Kellerstein: tak pokud se budu chtít zeptat na něco uživatele, třeba toho agenta,
tak zase můžu. Je tady metoda, Elisit.
[02:08:51] - [02:08:56]
Lukáš Kellerstein: Takže když vám mi řekne zarezervuj, mi knížku jménem duna
```

## Strana PDF 62

```text
[02:08:57] - [02:09:02]
Lukáš Kellerstein: Tak, já se ho můžu zeptat. A jakou jakej? Jakej díl? Jo, něco v tom
smyslu.
[02:09:03] - [02:09:12]
Lukáš Kellerstein: A tadydle je, když budu chtít verzi protokolu, třeba na tom Tool u
zjistit. Jo, takže ten kontext mi drží nějaký informace,
[02:09:13] - [02:09:18]
Lukáš Kellerstein: Který, eh, který? Tam, který jsou jakoby v metadatech toho request U,
[02:09:18] - [02:09:34]
Lukáš Kellerstein: Z. Jaký jakej Jakej protokol verzió? Já si vlastně chci povídat, Jaký sou
metadata k tomu uživateli? Třeba jaký je jeho jméno má Autent Je autentizovanej, Jaký
Má role a takovýdle typy věcí. To sou typicky vlastně uložený v těch metadatech.
[02:09:35] - [02:09:39]
Jan Duplak Tab: A keď chcem normálně, že ho chcem brejknuť.
[02:09:41] - [02:09:47]
Jan Duplak Tab: Další čtyry tisíc. Dva tisíc knih, abych skončil.
[02:09:49] - [02:09:49]
Lukáš Kellerstein: Myslíte tady.
[02:09:50] - [02:09:51]
Jan Duplak Tab: Horizont.
[02:09:51] - [02:09:51]
Lukáš Kellerstein: Jo.
[02:09:52] - [02:09:57]
Jan Duplak Tab: Rádať on mi to zobrazuje, že hledám. A teraz já ho brejknem, jak chcem,
aby skončil.
[02:09:58] - [02:10:07]
Lukáš Kellerstein: To je dobrá otázka. To je dobrá otázka. Já si myslím, že tam nic
takovýho neni. Ale radši se podívám, Protože by mi to dávalo smysl, aby tam bylo něco
jako kil.
[02:10:07] - [02:10:18]
Lukáš Kellerstein: Jo, něco takovýho. Jako že přerušení nebo něco takovýho. Ale radši se
podívám. Já jsem to Ne, neviděl, Nepoužil. Takže radši si to ověřil. Vono se to taky dost
často mění.
[02:10:20] - [02:10:34]
Lukáš Kellerstein: Tak, eh, a tak tadyhle, Pak je jak ten kontext vlastně získat. To
znamená, že v tom, eh, v tom initialmcpinitial serveru, je to vlastně jako parametr
tadydle, ten kontext. A pak tady jsou ty parametry toho danýho
[02:10:35] - [02:10:35]
Lukáš Kellerstein: tůlu.
[02:10:37] - [02:10:43]
Lukáš Kellerstein: Tak tohle to můžeme přeskočit. Teď se podíváme do kódu, takže
takhle si ukážeme, Kde To v tom kódu je?
```

## Strana PDF 63

```text
[02:10:45] - [02:10:47]
Lukáš Kellerstein: Tadydle je teda ten kontext.
[02:10:47] - [02:10:53]
Lukáš Kellerstein: Takže tadydle si to můžeme tu demonstraci ukázat, pak v kóru nebo
si To můžete pustit.
[02:10:54] - [02:10:59]
Lukáš Kellerstein: A tadydle jsou další ty složky. A ty si ukážeme jako v prezentaci. Proč
[02:11:00] - [02:11:12]
Lukáš Kellerstein: vlastně to je důležitý? Spíš jenom říct, Takže pokud budete potřebovat
v tom vašem langenglishinitialmcpinitiallangenglish Serveru
[02:11:14] - [02:11:20]
Lukáš Kellerstein: Řešit Autentizaci payr tool To Znamená. Že budete, chtít řešit, jestli
[02:11:20] - [02:11:33]
Lukáš Kellerstein: tendle agent má právo Na tendle Konkrétní tůl nebo na tedle
konkrétní tůl, Tak Eh se vám vyplatí jít cestou toho Fast
Langenglishinitialmcpinitiallangenglish
[02:11:35] - [02:11:43]
Lukáš Kellerstein: Normální oficiální Cesta má autentizaci Autorizaci taky, Ale na úrovni
serveru, ne na úrovni. Jakoby pertůl Jo,
[02:11:45] - [02:11:48]
Lukáš Kellerstein: potom jsou tady další dodatečný. Vlastně funkcionality.
[02:11:49] - [02:11:55]
Lukáš Kellerstein: Který Ten, Fast langenglishinitialmcpinitiallangenglish nabízí hned se
k nim teďkon dostanu, abyste chápali tydle ty tři pojmy.
[02:11:56] - [02:12:00]
Lukáš Kellerstein: Tak v tom případě jenom v tom případě bych šel tou cestovou Fast
Langenglishinitialmcpinitiallangenglish
[02:12:01] - [02:12:15]
Lukáš Kellerstein: pokuď. Ale chcete, aby jste pošli tou oficiální cestou? Nechcete tam
mít nějaký dodatečný knihovny Jo, a bejt na nich závislý vlastně, Tak bych šel cestou
initialmcpinitial serveru
[02:12:16] - [02:12:19]
Lukáš Kellerstein: a. To je za mě prostě devadesát procent případů
[02:12:20] - [02:12:27]
Lukáš Kellerstein: anebo. Pokuď budete mít opravdu nějakej důvod máte. Ňáký. Vlastní
rout ování ňákou vlastní rout ovací logiku
[02:12:28] - [02:12:31]
Lukáš Kellerstein: chcete mít. Nějakej vlastní transport nebo
[02:12:31] - [02:12:44]
Lukáš Kellerstein: přímo, řešit to vlastně ty. Ty dráty po kterejch to teče. Tak pak běžte
tou cestou. Ale jinak musíte tam mít ňákej justification musíte. Tam mít ňákej důvod
proč tou cestou jít
```

## Strana PDF 64

```text
[02:12:45] - [02:12:57]
Lukáš Kellerstein: já bych. Prostě volil tudle tu cestu. Ale umím si představit, že prostě v
nějakejch případech budete potřebovat fast langenglishinitialmcpinitiallangenglish
Jenom. Mě to vnitřně prostě, jakoby
[02:12:57] - [02:13:09]
Lukáš Kellerstein: Z mý zkušenosti po dvaceti letech, kdy prostě čím míň dependencí
mám tím, je to vlastně jako lepší tím míň jsem závislej na ňáký Třetí straně, tak tím lepší
a tak dále.
[02:13:10] - [02:13:17]
Lukáš Kellerstein: Tak co jsou ty Super Powers toho? Fast
Langenglishinitialmcpinitiallangenglish. Proč byste měli chtít to Fast
Langenglishinitialmcpinitiallangenglish. Když už
[02:13:18] - [02:13:27]
Lukáš Kellerstein: tak první, Eh, první je. První věc je, že nabízí tůl, kterej se jmenuje.
[02:13:28] - [02:13:29]
Lukáš Kellerstein: Vyhledej mi tůl.
[02:13:31] - [02:13:34]
Lukáš Kellerstein: To znamená, že když já Mám na Fast Langenglishinitialmcpinitial
serveru. Šedesát tulů.
[02:13:35] - [02:13:48]
Lukáš Kellerstein: Každej ten tůl má svoje jméno. Svej. Popis, parametry a jejich popis.
Jo, to je ten, to je ta. To je ta. Ten formát, kterej my jsme si ukazovali už minulou hodinu.
[02:13:48] - [02:13:56]
Lukáš Kellerstein: To je. To je vlastně to, co odchází do toho, eh, do toho Initiallm Ka I z
initialmcpinitial serveru. Pamatujte si,
[02:13:56] - [02:14:10]
Lukáš Kellerstein: agent se zeptá. Langenglishinitialmcpinitiallangenglish serveru Vrať
mi všechny tůly, on mu je vrátí. A tenhle, ten seznam toolů jde do toho. Takže to pořád
platí. To, co my jsme si ukazovali v tý první hodině, my jsme si tady ukazovali Tool
Calling.
[02:14:11] - [02:14:13]
Lukáš Kellerstein: Tak todle všechno
[02:14:13] - [02:14:21]
Lukáš Kellerstein: ob. Pořád odchází. Do toho Akorát to nepíšete už Vy ale vrátí vám to
ten Langenglishinitialmcpinitiallangenglish server.
[02:14:21] - [02:14:24]
Lukáš Kellerstein: A pokud na tom Langenglishinitialmcpinitiallangenglish serveru.
Mám šedesát tulů
[02:14:25] - [02:14:37]
Lukáš Kellerstein: tak prostě šedesát tůlů odchází do toho s každým requestem s
každým requestem kterej tam posílám, Uživatelským, teda tak odchází.
[02:14:39] - [02:14:41]
Lukáš Kellerstein: Odchází těla těch šedesát tůlů.
```

## Strana PDF 65

```text
[02:14:41] - [02:14:48]
Lukáš Kellerstein: A to. Si lidi uvědomili zase, že to je strašně neefektivní jo. Tadydle
vidíte přesně kolik to je? Jako znaků.
[02:14:49] - [02:14:56]
Lukáš Kellerstein: Tak se antropik přišel s tím Antropic. Tool Search. Tool
[02:14:57] - [02:15:03]
Lukáš Kellerstein: tadydle Je k tomu takovej blockpost, Todle. Jo, todle je vono.
[02:15:03] - [02:15:05]
Lukáš Kellerstein: A to, jak pustím takovýhle krátký video
[02:15:07] - [02:15:16]
Lukáš Kellerstein: zvuku ano. A, voni porovnávali přesně Když, agent bude mít prostě,
bude muset splnit nějakou úlohu
[02:15:16] - [02:15:25]
Lukáš Kellerstein: a bude mít k dispozici všechny tyhle ty tůly. Nebo mu daj jeden tůl,
kterej se jmenuje. Vyhledej ten správnej tůl.
[02:15:26] - [02:15:44]
Lukáš Kellerstein: Takže von vlastně bude mít k dispozici jenom jeden tůl. A kdy bude
pořád volat? Vlastně jakoby tenhle ten tůl a bude mu říkat hele. Uživatel, chce todle
mám. Na to ňákej vhodnej tůl a von se podívá na tý úrovni initialmcpinitial serveru tam
se Odehraje ta logika, že vybere ten správnej a řekne máš. Tady tydle tři
[02:15:45] - [02:15:50]
Lukáš Kellerstein: teďkon. To se pošle do toho initiallm Ka a to initiallm Ko Se rozhodne,
tak já chci tendle,
[02:15:51] - [02:15:57]
Lukáš Kellerstein: Jo, Takže v tu chvíli najednou šetříte tokeny a především velikost toho
kontext s Window, protože
[02:15:58] - [02:16:03]
Lukáš Kellerstein: vy tam nemusíte S každým tím request em uživatelským posílat všech
těch šedesát tůlů
[02:16:04] - [02:16:17]
Lukáš Kellerstein: a voni testovali i rychlost, samozřejmě Protože to je Ten Argument by
byl Tam je dodatečnej hop. Prostě to já. Musím se zeptat. Nejdříve na ty tuly pak se
musim, pak je tam vlastně můžu poslat takže se tam kontrolovalo
[02:16:17] - [02:16:26]
Lukáš Kellerstein: nejenom eh velikost okna, Takže utracený tokeny náklad, ale taky
rychlost mezi těmahle těma dvouma postupama
[02:16:27] - [02:16:41]
Lukáš Kellerstein: vycházelo to vždycky líp pro Ten, eh. Protože zase to zpracování těch
šedesát tokenů. Tam to trvá delší dobu. Tenhle. Ten jeden hop, kterej se stane, tak ale
ten Hop je vlastně jako
[02:16:41] - [02:16:47]
Lukáš Kellerstein: normální skript, kterej udělá vlastně ten výběr. Takže je to poměrně
rychlý.
```

## Strana PDF 66

```text
[02:16:47] - [02:16:51]
Lukáš Kellerstein: Takže tady pak máte video. Tady máte vo tom Blockpost. Takže si to
můžete přečíst.
[02:16:52] - [02:16:57]
Lukáš Kellerstein: A, eh, todle to vlastně nabízí ten Fast
Langenglishinitialmcpinitiallangenglish.
[02:16:59] - [02:17:08]
Lukáš Kellerstein: Nikdo vám nezakazuje si todle to napsat sám Pomocí toho
langenglishinitialmcpinitial serveru. Ono to není zas tak těžký jo.
[02:17:08] - [02:17:17]
Lukáš Kellerstein: Takže? Jenom, abyste si uvědomili že, eh tadydle, v tom případě
jenom srdč Tůl a kol, Tůl metody.
[02:17:17] - [02:17:18]
Lukáš Kellerstein: Jo,
[02:17:19] - [02:17:33]
Lukáš Kellerstein: a vy mu dáváte vlastně ňákej patern podle. Čeho máte tuly najít takže,
Buď mu dáváte celou uživatelskou otázku nebo z tý uživatelský otázky. Vy táhnete
klíčový slova a pak podle toho vlastně najdete,
[02:17:33] - [02:17:42]
Lukáš Kellerstein: Eh, ten ten Tool A Teďkon to jak Je to neimplementovaný ve Fast
Langenglishinitialmcpinitiallangenglish je jenom regga. Jeden ze způsobů je reggaex.
[02:17:43] - [02:18:00]
Lukáš Kellerstein: Takže prostě vyhledání. Podle z textu si samozřejmě můžete napsat
Sami to není vůbec žádná komplikace. Je tady pak initialbminitial. Dvacet pět, kterou
třeba používá elastik, Ale to taky není nic komplikovanýho, takže zas Taková jakoby
úplně výhoda,
[02:18:00] - [02:18:06]
Lukáš Kellerstein: to nevidím, Jo, tady máte Vlastně, bez toho. Fast
Langenglishinitialmcpinitiallangenglish.
[02:18:07] - [02:18:10]
Lukáš Kellerstein: Je to čtyřicet řád dekódů tady máte Těch čtyřicet řád De kódů.
[02:18:11] - [02:18:17]
Lukáš Kellerstein: Takže zase je to taková výhoda, Nebo jsem schopnej si to
naimplementovat sám pomocí toho oficiální knihovny, takže
[02:18:18] - [02:18:26]
Lukáš Kellerstein: takže nechám na vás spoustu klientů, Jak jsem říkal, Ne, Nerozumí
těm resourcům a promptům.
[02:18:26] - [02:18:32]
Lukáš Kellerstein: A na to reaguje ten Fast langenglishinitialmcpinitial taky. A říká, Hele,
tak my Ze všech resource ů a promptů
[02:18:33] - [02:18:34]
Lukáš Kellerstein: uděláme tůly
```

## Strana PDF 67

```text
[02:18:35] - [02:18:44]
Lukáš Kellerstein: a najednou ten agent má k dispozici resource jako tůl a prompt jako
tůl a protože Všichni uměj pracovat s tůlama.
[02:18:44] - [02:18:51]
Lukáš Kellerstein: Tak najednou se vlastně jakoby vy máte na tom serveru ty resource y
a prompt y tak jak byste to vlastně chtěli psát.
[02:18:52] - [02:19:06]
Lukáš Kellerstein: Ale umíte je vyexpózovat. Pro klód, kód, kterej umí resource y a
prompty. Tam to zůstane normální cestou ale. Pro Ty, co neuměj používat. Resource Y a
prompty. Vystavíte tadydle ty nový dva tůly resource jako toul a prompt jako tůl
[02:19:06] - [02:19:12]
Lukáš Kellerstein: a najednou zase Voni to budou umět používat taky sice jako tůly, jako
ale budou.
[02:19:13] - [02:19:15]
Lukáš Kellerstein: Takže to je další důvod. Proč
[02:19:17] - [02:19:35]
Lukáš Kellerstein: Skilly, to znamená pro ty z vás, kdo třeba pracujou s těma
korvacímma agentama? My eště Skilly budeme trošku, zmiňovat v dalších hodinách, ale
todle jenom zběžně promítnout pro ty Z vás, který znaj pro ty z vás, co neznaj, tak se k
tomu můžete vrátit. Pak až třeba nakousneme ty skilly trošku víc
[02:19:36] - [02:19:43]
Lukáš Kellerstein: A vy můžete dávat kódovacímu agentovi Skill Y přes initialmcpinitial
server. Když použijete Faster Langenglishinitialcpinitiallangenglish.
[02:19:45] - [02:19:46]
Lukáš Kellerstein: Jo, Takže von je pak schopnej
[02:19:47] - [02:20:00]
Lukáš Kellerstein: vlastně si ty Skilly vytáhnout. Takže má to jako resource. Samozřejmě,
jako co jinýho? Je to prostě resource. Skill je texťák. Já jsem říkal, že ty soubory Jsou přes
ty Resource Y.
[02:20:01] - [02:20:09]
Lukáš Kellerstein: Takže to vlastně není žádné překvapení. Ale dál voni to pojmenovali
takhle a najednou zase ty lidi se toho chytli, protože
[02:20:10] - [02:20:11]
Lukáš Kellerstein: to nemusej vymejšlet sami,
[02:20:13] - [02:20:25]
Lukáš Kellerstein: Tak je tam to verzování tůlů. To je docela, eh, dobrá věc, že máte
stejnej tůl ale ve Verzi jedna ve verzi dva koneckonců, stejně jako na
Langenglishinitialapiinitiallangenglish. Ale zase v Langenglishinitialapiinitiallangenglish
Máme spíš
[02:20:26] - [02:20:44]
Lukáš Kellerstein: url adresu. Slash Verze Jedna a tam je Celý
Langenglishinitialapiinitiallangenglish se všema endpointama. A pak máme
Langenglishinitialapiinitiallangenglish ve Verzi dva. A to je initialurlinitial Slash verze dva
slash a tam jsou Zase všechny ty endpointy z verze dva. Takže kdyby chtěl jít tou cestou
a následovat to, co už známe z Langenglishinitialapiinitiallangenglish,
```

## Strana PDF 68

```text
[02:20:45] - [02:20:48]
Lukáš Kellerstein: tak bych nechtěl verzovat Jako na úrovni tůlů,
[02:20:49] - [02:20:52]
Lukáš Kellerstein: Ale spíš na úrovni celýho Langenglishinitialapiinitiallangenglish. Takže
zase nechám na vás,
[02:20:53] - [02:20:56]
Lukáš Kellerstein: jestli tam vidíte zatím takovou velkou výhodu nebo ne,
[02:21:00] - [02:21:12]
Lukáš Kellerstein: Tak a je tady autorizace autentikace. To znamená, že máme ňákýho
interne identity provider, a google Facebook, Microsoft Nevím. Out, zero A takovýdle
[02:21:12] - [02:21:27]
Lukáš Kellerstein: Langenglishinitialmcpinitiallangenglish klient Teda, si dostane token.
Initialmcpinitial server. Si, To eh, rozšifruje ten a zjistí se, kdo to je, jak se jmenuje, jaký
je případně jeho role a tak dále.
[02:21:28] - [02:21:34]
Lukáš Kellerstein: Pokuď tam nemá přístup, Tak se tam nedostane. Takže autentikace a
autorizace funguje.
[02:21:37] - [02:21:43]
Lukáš Kellerstein: Tak to je ta autentikace a tadyhle. Takže tam by měla bejt i Ano,
[02:21:43] - [02:21:59]
Lukáš Kellerstein: na z. Na úvodu autorizace. Takže to by byla autentikace, kdo sem a
teď autorizace, Jaký Mám práva. Jaký mám role A vlastně kam mám jako přístup? To
znamená, že tam je i ta cesta, že dostanu ňákej skoup
[02:22:00] - [02:22:07]
Lukáš Kellerstein: a ňákou. Ňákou Roli případně a podle. Toho já jako zjistim kam teda
můžu nebo nemůžu jo
[02:22:07] - [02:22:14]
Lukáš Kellerstein: takže, tadydle? Se to čekuje uvnitř body a Tady se to čekuje Podle
autentikace.
[02:22:14] - [02:22:19]
Lukáš Kellerstein: Initialmcpinitial server. Ta oficiální cesta pořád jako je schopná toho
do dosáhnout,
[02:22:20] - [02:22:33]
Lukáš Kellerstein: ale čekujete to v body? Vlastně Jak jsem říkal, že ten Jason
Langenglishinitialrpcinitiallangenglish má ty metadata. Tu Seš v těch metadetech? Tak
tam z toho si To musíte vyčíst u toho. Fast Langenglishinitialmcpinitiallangenglish Je to
udělaný. Trošku líp
[02:22:34] - [02:22:38]
Lukáš Kellerstein: tam stačí. Vlastně na End Point U Udě Ukázat
[02:22:46] - [02:22:52]
Lukáš Kellerstein: tadydle. Říct tenhle Ten tůl, nebo tenhle Ten resource vyžaduje Skope
Admin
```

## Strana PDF 69

```text
[02:22:53] - [02:22:57]
Lukáš Kellerstein: Tenhle Ten tůl vyžaduje Skoupi Admin nebo Wright
[02:22:58] - [02:23:03]
Lukáš Kellerstein: Jo, tady je to hezky takhle udělaný. Vlastně v tom dekorátoru V tom
oficiální cestě
[02:23:08] - [02:23:23]
Lukáš Kellerstein: si musíte udělat takovoudle, jakoby taky to není zas tak strašný. Jo,
Omlouvám se za to scrollování tadydle je takovádle Pomocná metoda, která se to
přesně vytahuje. Jako z toho kontextu. Vidíte, že v kontextu mám hedry
[02:23:24] - [02:23:26]
Lukáš Kellerstein: a v tom hedru mám tady skoupy,
[02:23:27] - [02:23:29]
Lukáš Kellerstein: Takže tadydle vidím pak ty skoupy.
[02:23:29] - [02:23:35]
Lukáš Kellerstein: Jo, a teďkon Já říkám, že tahle ta pomocná metoda. Hele, z kontextu a
hledám tam tenhle skoup
[02:23:36] - [02:23:37]
Lukáš Kellerstein: Je tam nebo ne?
[02:23:38] - [02:23:46]
Lukáš Kellerstein: Jo, a pak tím pádem tadydle v těch tůlech řeknu. Tady. Hele, pro
Adbook vyžaduju Wright Scope,
[02:23:47] - [02:23:55]
Lukáš Kellerstein: a jestli tam není, tak mi to vyhodí chybu. Jestli tam je, tak to pude dál.
A tady se mi ta odpověď vrátí normálně ven, jakoby z toho Túlu.
[02:23:56] - [02:24:08]
Lukáš Kellerstein: Takže vidíte, že jako jde to, Ale čtete to vlastně, jakoby z toho
kontextu uvnitř, není to tak, že by to tadydle V tom, eh, v tom dekorátoru bylo hezky, že
byste tam mohli jenom napsat.
[02:24:08] - [02:24:23]
Lukáš Kellerstein: Já si myslím, že to tam doj do dostanou a Dojde to tam, jo? Přidaj to
tam, Protože to vy uviděj U toho, že to dává ale smysl, to je jako to dává smysl, Tak to
tam přidaj. Zatím to tak není.
[02:24:23] - [02:24:33]
Lukáš Kellerstein: A píše se to tímhle způsobem. Ale zase vyřešíte to. Není to nic, co by
se, Jakoby že by to to mělo. A ten oficiální způsob to neexistovalo to tam.
[02:24:38] - [02:24:42]
Lukáš Kellerstein: Tak jo, to sou ty skoupy. To jsem chtěl ukázat sem ukázal v kódu.
[02:24:43] - [02:24:49]
Lukáš Kellerstein: Teď se podívat na kód. Tak a tady pak je migrace migraci. My můžeme
přeskočit.
[02:24:50] - [02:24:57]
Lukáš Kellerstein: To je jenom prostě sumarizace toho, co jsme si ukázali nebo co jsme
si řekli, že tady
```

## Strana PDF 70

```text
[02:24:58] - [02:25:13]
Lukáš Kellerstein: už neexistuje. Už existuje stream mobil
Langenglishinitialhttpinitiallangenglish Jo, zvěšte teda verzi na Tudle tu a tak dále. Pak
sou tady zmíněný věci, který my jsme si bysme přeskočili. Takže, berte to jenom jako
sekci,
[02:25:14] - [02:25:26]
Lukáš Kellerstein: eh, k Tomu, eh, k tomu jo. K tý migraci sedum věcí. Teda, který bysme
si dneska měli vodnýst, kdybysme to shrnuli nějak na důležitý body,
[02:25:28] - [02:25:44]
Lukáš Kellerstein: Initialmcpinitial nám teda řeší a přesouvá ten problém z toho
násobku na. Ten plus takže. Je důležitý ty. Initialmcpinitial servery mít usnadňuje nám to
život. Ty. Kombinace nám to usnadňuje. Verzování nám to usnadňuje.
[02:25:45] - [02:25:49]
Lukáš Kellerstein: Máme tady teda hosta. Kde to, běží a pak klient a server,
[02:25:50] - [02:25:54]
Lukáš Kellerstein: klient a Server můžou běžet na jiným hostu nebo na stejným hostu
[02:25:55] - [02:26:06]
Lukáš Kellerstein: A používaj nebo server. Exposuje tůly, resource y nebo prompt Y Tak
verze dva Je bezestavová.
[02:26:07] - [02:26:11]
Lukáš Kellerstein: Žádný sešny. Je to víc takový ready.
[02:26:12] - [02:26:13]
Lukáš Kellerstein: Cokoliv se jedná,
[02:26:16] - [02:26:24]
Lukáš Kellerstein: tak cokoliv se jedná z s identitou, tak to je uložený tadydle V tom
metatagu v tom Langenglishinitialgrpcinitiallangenglish.
[02:26:26] - [02:26:30]
Lukáš Kellerstein: Máme tři způsoby tři apíčka jak Ty Initialmcpinitiallangenglish servery
psát
[02:26:31] - [02:26:38]
Lukáš Kellerstein: fast langenglishinitialmcpinitial jakoby neoficiální způsob ale takovej
nejvíc Feature Rich.
[02:26:39] - [02:26:43]
Lukáš Kellerstein: A potom jsou tady dva vlastně způsoby oficiální.
[02:26:45] - [02:27:00]
Lukáš Kellerstein: Tak jsou tady důvody, proč případně používat Fast
Langenglishinitialmcpinitiallangenglish. Takže ten Pair Tool autentizace Automatická v
tom, eh, v tom, eh, dekorátoru. Tool Search Skilly nebo.
[02:27:00] - [02:27:02]
Lukáš Kellerstein: Všechny si myslím, že
[02:27:03] - [02:27:09]
Lukáš Kellerstein: se daj vyřešit i tim oficiálním způsobem, je To prostě jen taková
nadstavba nad tím oficiálním způsobem.
```

## Strana PDF 71

```text
[02:27:10] - [02:27:12]
Lukáš Kellerstein: Eh, Todle, to Můžeme přeskočit.
[02:27:15] - [02:27:16]
Lukáš Kellerstein: Tohle to
[02:27:17] - [02:27:28]
Lukáš Kellerstein: můžeme taky přeskočit, ale víceméně, já už jsem to. Zmiňoval To, že
ten protokol je beze stavovej, neznamená, že vy nemůžete mít stavovou tu aplikaci. Jo,
stejně jako u Langenglishinitialapiinitiallangenglish.
[02:27:30] - [02:27:42]
Lukáš Kellerstein: Tak Tady si Můžete přečíst víc. Tady jsou různý specifikace a tak dále.
Takže to je jenom dodatečný. A to. Si myslím, že pro dnešek bude
[02:27:43] - [02:27:45]
Lukáš Kellerstein: všechno. Pojďme se podívat na otázky.
[02:27:50] - [02:27:54]
Lukáš Kellerstein: Tak já jsem dost měl stydlej a doufám, že je mi rozumět. Teda
[02:27:55] - [02:28:06]
Lukáš Kellerstein: tak ty shotoul y by Mě zajímaly náhrada. Eh, initialvsinitial kód. Takže
to ukážu. Jenom co z. Ukončím to téma. Langenglishinitialmcpinitiallangenglish. Takže
tady je ještě jedna otázka Langenglishinitialmcpinitiallangenglish
[02:28:08] - [02:28:09]
Lukáš Kellerstein: Tadydle Initialčet,
[02:28:15] - [02:28:22]
Lukáš Kellerstein: to je chci ukázat. Tak teď. To vím. Odkud přišlo Todle
[02:28:28] - [02:28:30]
Lukáš Kellerstein: Vše zajímavý Lenky.
[02:28:31] - [02:28:33]
Lukáš Kellerstein: Tak tadydle, inspektor. Díky, Pavle
[02:28:34] - [02:28:44]
Lukáš Kellerstein: Já ten inspektor jsem moc nepoužíval, protože mi sem si vždycky
napsal skript. Ale když píšete initialmcpinitial server, tak tenhle. Ten inspektor vám
může hrát Roli toho
[02:28:45] - [02:28:57]
Lukáš Kellerstein: že Máte aplikaci, která je schopná se s tím
Langenglishinitialmcpinitiallangenglish Serverem Jako povídat, testovat, Může si
provolávat ty Endpointy. Něco jako když máte langenglishinitialapiinitiallangenglish
server A máte nějakej, eh,
[02:28:58] - [02:29:06]
Lukáš Kellerstein: postmen? Nebo Něco takovýho, kterej je schopnej tam poslat ty
request y Tak todle je takovej podobnej inspektor aplikace vod, toho model, kontext
protokolu
[02:29:08] - [02:29:12]
Lukáš Kellerstein: Tak, jenom se, eh. Nevim, kam přišla. Jenom. Můžete mi říct, kam
přišla Tadle? Ta.
```

## Strana PDF 72

```text
[02:29:13] - [02:29:15]
Karel Vaclavik: To bude asi v chat. U toho, Zoom, U, No.
[02:29:15] - [02:29:17]
Ing. Ivan Kostolný: Ano, preamov, Zoome je chat a.
[02:29:18] - [02:29:21]
Lukáš Kellerstein: A Rozumím. Jo, rozumím.
[02:29:21] - [02:29:38]
Lukáš Kellerstein: Tak já se omlouvám. Já Do tohodle chatu toho Zoom u vůbec
nekoukám. Takže jestli můžu poprosit, jestli byste psali. Vždycky spíš do toho diskortu.
Já bych nerad nikoho přeskakoval nebo ignoroval. Není to jako moje
[02:29:39] - [02:29:43]
Lukáš Kellerstein: vědomí, spíš voni ty Čety moc Nef Nezůstávají v tom,
[02:29:44] - [02:29:46]
Lukáš Kellerstein: eh, v tom, eh, Zoom u.
[02:29:47] - [02:29:52]
Lukáš Kellerstein: Takže jenom kdybyste příště mohli psát do toho moje chyba, že jsem
to nezmínil,
[02:29:53] - [02:29:56]
Lukáš Kellerstein: ale chci ukázat za to malá prezentace. Jo, jo, to je.
[02:29:56] - [02:30:00]
pvojacek: Jo, já jsem to tam pro to udělal Screenčot. Protože sem ne.
[02:30:00] - [02:30:01]
Lukáš Kellerstein: Děkuju, děkuju.
[02:30:01] - [02:30:02]
pvojacek: Tak to takhle.
[02:30:02] - [02:30:06]
Lukáš Kellerstein: To je, ehm, přemejšlí. Teda, Tim. Tak to je dobře.
[02:30:08] - [02:30:19]
Lukáš Kellerstein: Tak Eh, Todle. To je todle Todle prezentace. To vám Můžu ukázat
hnedle. Dokončeme initialmcpinitiallangenglish. A pak se budeme věnovat těm ne
langenglishinitialmcpinitiallangenglish Tématům a. Já Vám tady ukážu ten zbytek
[02:30:20] - [02:30:24]
Lukáš Kellerstein: prečo jste povedal že v initialmcpinitial není vhodné použít.
[02:30:24] - [02:30:39]
Lukáš Kellerstein: Ještě by mě zajímalo, proč jsem provedal, že musí. Není vhodný
použít volat existující Langenglishinitialapiinitiallangenglish nějakýho našeho systému
Neumím si představit, jak jinak. Nedá se přímo v
Langenglishinitialmcpinitiallangenglish. Implementovat byznys. Logika znovu.
[02:30:40] - [02:30:45]
Lukáš Kellerstein: Eh, vo to tady úplně Nejde tady. Se spíš vobjevil Takovej nešvar, že?
[02:30:46] - [02:30:54]
Lukáš Kellerstein: Tak jak vypadá Langenglishinitialapiinitiallangenglish A jak Vlastně je
strukturovaný? Langenglishinitialapiinitiallangenglish v těch Endpoint Ech restový
Langenglishinitialapiinitiallangenglish Především že Jo
```

## Strana PDF 73

```text
[02:30:55] - [02:31:02]
Lukáš Kellerstein: tak Eh Lidi začali vlastně expouzovat úplně stejnou strukturu.
[02:31:03] - [02:31:05]
Lukáš Kellerstein: Přes Langenglishinitialmcpinitiallangenglish pro agenty. Ale
[02:31:06] - [02:31:18]
Lukáš Kellerstein: musíte si uvědomit, že ten agent, jako vy, mu chcete tu jako tu práci
více méně jako ulehčit Nebo vy nechcete, aby musel.
[02:31:19] - [02:31:25]
Lukáš Kellerstein: Vlastně, to, co vy píšete v tom skriptu, tak, aby von musel ty samý
kroky. Vlastně jakoby dělat znova.
[02:31:25] - [02:31:35]
Lukáš Kellerstein: Jo, a je lepší. Spíš jako kdybyste měli. Já to připodobňuju. Jako
kdybyste měli tabulky v databázi
[02:31:36] - [02:31:39]
Lukáš Kellerstein: a Teď byste tomu agentovi dělali všechny ty tabulky
[02:31:40] - [02:31:51]
Lukáš Kellerstein: a teď byste se ho zeptali na ňákou otázku která, by vyžadovala aby,
šel, do týdle Tabulky tam si vzal něco do týdle Tabulky. Tam si vzal něco. Tady. Vodsaď
tady něco A musel udělat těch
[02:31:52] - [02:31:57]
Lukáš Kellerstein: kroků. Vlastně několik, Jenom proto, aby vám vodpověděl na tu na tu
otázku. Tak todle Je
[02:31:58] - [02:32:05]
Lukáš Kellerstein: To je dynamický, že von bude schopnej odpovídat jako na jakoukoli
defakto otázku, protože má všechny tabulky k dispozici.
[02:32:06] - [02:32:21]
Lukáš Kellerstein: Todle není vždycky úplně to, co vod toho. Agenta chcete. Takže když
zůstanu v tý analogii tý databáze, Tak by bylo lepší, kdybych mu připravil čtyři, pět
vjuček. Vlastně jakoby nebo předpřipravenejch dotazů
[02:32:22] - [02:32:36]
Lukáš Kellerstein: a dal mu k dispozici tydle předpřipravený dotazy Aby von vlastně jako
zavolal ten dotaz. A ten dotaz udělal ty čtyry koly, ale vrá a vrátil mu nějakej, jakoby lepší
výsledek, stejně To vnímám v tom initialmcpinitial serveru.
[02:32:36] - [02:32:39]
Lukáš Kellerstein: Já, když budu chtít vod něj prostě.
[02:32:40] - [02:32:49]
Lukáš Kellerstein: Kolik jsme utržili, Kolik jsme utržili za minulej měsíc v produktech typu
elektronika.
[02:32:50] - [02:32:58]
Lukáš Kellerstein: Tak já vlastně jako nechci, aby. Aby sem mu dal tendletu otázku nebo
tydle typy otázek, třeba každej měsíc
[02:32:59] - [02:33:03]
Lukáš Kellerstein: a von musel Pokaždý vlastně jakoby vyvolávat ty
Langenglishinitialapiinitiallangenglish request y.
```

## Strana PDF 74

```text
[02:33:04] - [02:33:09]
Lukáš Kellerstein: Já bych mu radši dal tůl, kterej mu řekne za jak dlouho a jaká
kategorie
[02:33:10] - [02:33:18]
Lukáš Kellerstein: a Jmenoval se, eh, Revenue nebo já nevím, něco takovýho. Jako př.
Jako výnos nebo zisk?
[02:33:19] - [02:33:24]
Lukáš Kellerstein: Tam Vlastně v tom bylo, že se maj zavolat Tydle tři
Langenglishinitialapiinitiallangenglish. Kóly.
[02:33:25] - [02:33:25]
Lukáš Kellerstein: Jo.
[02:33:26] - [02:33:29]
Jan Duplak Tab: Že? No, jinými slovami,
[02:33:29] - [02:33:46]
Jan Duplak Tab: nemám to Robi jedna k jedné, Ale prostě designujem to tak, že po
analýze návrhem to Rozhrání je v tom initialmcpinitiallangenglish. A potom sa
rozhodnem či v implementaci. To s orchestrem, prostě volání a nebo prostě
naimplementujem.
[02:33:47] - [02:33:48]
Jan Duplak Tab: Eště doslova nové Langenglishinitialapiinitiallangenglish.
[02:33:49] - [02:33:53]
Lukáš Kellerstein: Jo, přesně tak, nebo si rovnou šáhnete do tý databáze? Jo, to už je
vlastně jakoby na vás.
[02:33:53] - [02:33:55]
Jan Duplak Tab: Rovnou ne. Ale hej.
[02:33:55] - [02:34:08]
Lukáš Kellerstein: Ale ale rozumíme si, Jakoby ten účel pro toho agenta by měl. Mělo by
to vyhovovat tomu, co mu chcete tomu agentovi dát. A zase my se vo tom budem bavit
v průběhu toho kurzu několikrát. Jo,
[02:34:09] - [02:34:23]
Lukáš Kellerstein: Čím, míň možností tomu agentu vy vlastně dáte na výběr, tak tím
jistější výsledky budete dosahovat. To znamená zase, když mu dám čtyřic. Čtyřicet
šedesát tu šedesát tůlů,
[02:34:23] - [02:34:39]
Lukáš Kellerstein: tak vlastně, jakoby Zvětšuju hrozně tu pravděpodobnost toho že, si
může vybrat špatnej tůl kdežto, když udělám agenta kterej, bude zaměřenej na
účetnictví a dám mu k dispozici, jenom tůly na účetnictví. Tak zase zvyšuju tu
pravděpodobnost toho že,
[02:34:40] - [02:34:42]
Lukáš Kellerstein: se bude chovat správně.
[02:34:42] - [02:34:45]
Jan Duplak Tab: To je dost. Každá úloha prý velkom přistane. No,
```

## Strana PDF 75

```text
[02:34:48] - [02:34:52]
Jan Duplak Tab: lebo, čo mám robiť. Keď tam máme prostě, eh, stolky apy. Hej,
[02:34:54] - [02:34:59]
Jan Duplak Tab: tak chceme všetko dávat. Initialmcpinitiallangenglish. Prostě prakticky.
[02:34:59] - [02:35:00]
maria: No,
[02:35:00] - [02:35:11]
maria: ono je to o tom, že? A ghetapy velmi velké tak poskytuje obrovské množství
informací. Agent by Mal poskytovat Velmi malé množstva. Konkrétní informací. Jak som
si jak som to dobré pochopil.
[02:35:12] - [02:35:15]
maria: To znamená Ak. Mám databázu všetkých
[02:35:15] - [02:35:25]
maria: vlakových spojů autobusov já neviem Čo A chcem sa prepraviť z jednoho mesta
do druhého a potravujem odjíždě. O čtvrtej a zaujímáme ňáký konkrétní vlak
[02:35:26] - [02:35:30]
maria: tak. Agent Má za Úlohu, nájezd, vlak, Číslo taky makový
[02:35:30] - [02:35:39]
maria: ale. Já Nechcem musím. Servera poskytnuť. Celý všedký zoznam stanic toho
vlaku ale, Iba Ten, odchod z toho Mojeho města.
[02:35:40] - [02:35:40]
maria: Já to mám vést.
[02:35:41] - [02:35:57]
Lukáš Kellerstein: Je to, je to tak a a důsledek. Jenom je to, že vy chcete i limitovat
množství dat, který se Mezi Agentem a Tim initialmcpinitial serverem jako odehrávaj. Jo,
a teď si vemte že veškerý ty data z těch langenglishinitialapíček by prostě musejí jít do
toho agenta.
[02:35:57] - [02:36:10]
Lukáš Kellerstein: Ten agent je musí zase jako zpracovat. Jo a zase. Takže, drahý, Je to
pak pomalý. Je to protože vlastně vy mu. Vy sice chcete mu dát tu volnost A tu dynamiku
toho, že von si má teda vybrat.
[02:36:11] - [02:36:14]
Lukáš Kellerstein: Ale bude to pomalý a bude to, drahý.
[02:36:14] - [02:36:26]
Lukáš Kellerstein: Jo, když mu to předpřipravíte. A von jenom. Vlastně se má zeptat vám
má poslat dvě věci a pak se mu vrátí už vlastně skoro připravený. To, co von potřebuje,
Jenom von to musí
[02:36:26] - [02:36:38]
Lukáš Kellerstein: zformulovat do tý vodpovědi nebo udělat ňákej malej výběr a
zformulovat tak, To máte rychlý, Jo, vy chcete nechat tu determiničnost? Tu Tu ten skript
[02:36:39] - [02:36:50]
Lukáš Kellerstein: chcete pořád mít? To Ten normální obyčejnej software Engineering,
kterej tady Je to je pořád potřeba vlastně. Jo ten, dělá. To věci rychle efektivně
```

## Strana PDF 76

```text
[02:36:50] - [02:36:57]
Lukáš Kellerstein: ten. Agent dělá věci dynamicky ale, vy nechcete tu dynamičnost jako z
jako mít všechno.
[02:36:58] - [02:37:02]
Lukáš Kellerstein: Nedeterministický, Dynamický. Protože pak je to pomalý a drahý.
[02:37:03] - [02:37:04]
pvojacek: Já mám tady k tomu ještě otázku.
[02:37:05] - [02:37:05]
Lukáš Kellerstein: Ano.
[02:37:06] - [02:37:20]
pvojacek: Řešil Jste někdy v tom toulu vnořenýho subagenta kterej, si stáhne vodněkaď
nějaký skilly a Třeba Řeší Ňákej komplexnější work Flow, kterej se může v čase měnit.
[02:37:22] - [02:37:26]
Lukáš Kellerstein: Akorát, že ten agent vlastně není na straně initialmcpinitial serveru.
[02:37:27] - [02:37:37]
Lukáš Kellerstein: Eh, je. To dobrá. Je to velmi dobrá otázka. A, Eh, jestli jste si to
vymyslel vy, tak chá. Tak přemejšlíte správným směrem akorát todle. To
[02:37:38] - [02:37:52]
Lukáš Kellerstein: je multiagentní systém se tomu říká, my se O tom budeme povídat. A
ten agent vyvolá dalšího agenta jako Tool A tomu Paternu se říká, eh,
[02:37:52] - [02:37:59]
Lukáš Kellerstein: takže vy dáte jinýmu agentovi jinýho agenta jako Toula. Von si ho
bude moct vyvolávat. Jo, a to
[02:38:00] - [02:38:05]
Lukáš Kellerstein: zase je založený jenom na tom, že máme tady Tool Calling
[02:38:06] - [02:38:13]
Lukáš Kellerstein: a Vy můžete zneužít tu schopnost toho, že to Initiallm Ko si umí vybrat
[02:38:14] - [02:38:22]
Lukáš Kellerstein: podle jména a popisu. Když to úplně zestručnim, tak Initiallm Ko umí.
Tím tůlkowlingem se naučilo pomocí jména a popisu
[02:38:23] - [02:38:31]
Lukáš Kellerstein: z předefinovaný množiny vybrat něco, co by teoreticky mělo pasovat
na tu otázku
[02:38:32] - [02:38:35]
Lukáš Kellerstein: jo, a My můžeme buď volat teda funkce jako tůly
[02:38:35] - [02:38:52]
Lukáš Kellerstein: a. Nebo mu můžeme dávat jména agentu s popisem, co ten agent
dělá a zase to si umí pro ten danej tásk případně říct. No tak, já bych asi potřeboval tady
agenta jménem karel Protože, v popisu má napsáno že, Dělá v účetnictví a že umí
všechno vo účetnictví.
[02:38:53] - [02:38:58]
Lukáš Kellerstein: Tak já si ho vyvolám. Jo? A tím pádem, jakoby tvoříme multi agentní
systém
```

## Strana PDF 77

```text
[02:38:59] - [02:39:04]
Lukáš Kellerstein: na tom initialmcpinitial serveru. Ten agent vlastně neběží. My mu ho
dáváme na tom aplikačním serveru.
[02:39:06] - [02:39:13]
pvojacek: Mhm, a ohledně těch skillů, že by třeba někdo dokázal, eh, tu funkcionalitu
[02:39:14] - [02:39:21]
pvojacek: v tom Work flow nějakým způsobem měnit, Aniž by, eh, musel nějakým
způsobem upravovat kok.
[02:39:23] - [02:39:35]
Lukáš Kellerstein: To Je jakoby Din. Teď asi narážíte na to, že chcete mít vlastně toho
agenta dynamickýho a záběhu Zarantaimu. Podle toho, co bude potřeba tak aby, si
naloudoval do sebe
[02:39:35] - [02:39:37]
Lukáš Kellerstein: tak. To sou to je. To sou
[02:39:38] - [02:39:55]
Lukáš Kellerstein: dynamický vlastně. Funkcionality který, jsou dodávaný tomu agentovi.
Používá se to jednak na ty prompt Y, co jsem taky zmiňoval v tom initialmcpinitial
serveru, že? Ten agent vlastně si podle toho, Co se po něm chce, nalouduje prompt.
Takže dejme tomu, že přijde rekreř. Vod uživatele.
[02:39:56] - [02:40:05]
Lukáš Kellerstein: Vy byste měl ňákej router jako, byl ten čef Jak jsem říkal, ten je na to
skvělej. Ten ten model. Tam byste mu dal na výběr různý typy agentů.
[02:40:06] - [02:40:14]
Lukáš Kellerstein: Řek. Byste hele. Přišel, Tenhle request uživatele. Jeffe, vyber mi.
Kterýho Kterej jeho agenta vlastně já mám jako naloudovat.
[02:40:15] - [02:40:24]
Lukáš Kellerstein: Von by vám řekl. Účetní otázka se týká financí účetní. A vy byste
zavolal initialmcpinitial server. Tam byste si z toho stáhnul prompt pro účetního
[02:40:25] - [02:40:35]
Lukáš Kellerstein: Skill Y pro účetního, protože taky de Dynamicky natahovat Skilly podle
zase ňákýho paternu jo Jako, Když jsme si tam ukazovali srdč Tůl
[02:40:36] - [02:40:47]
Lukáš Kellerstein: tak, byste měli srd Skill A vy byste mu vrátil ty Skilly a naloudoval
byste jako prompt systém Prompt pro něj. Skilly pro něj. A mohli. Moh byste ho pustit?
[02:40:48] - [02:40:49]
Lukáš Kellerstein: Ano.
[02:40:49] - [02:40:50]
pvojacek: Jaké.
[02:40:50] - [02:41:00]
LubosBil: Ako auditora Kódu. Čo vlastně je naučen? Jeden angent ako. Auditor má rád s
sebou nějaké Skilly.
[02:41:01] - [02:41:11]
LubosBil: A Vlastně, naučili se tak, že ten, který programuje, si Ju sám keď něču robí sám
to dává za auditovať. Dostane vlastně feedback a opraví věci podle toho. A komu ten
auditor pově, že robil chyby?
```

## Strana PDF 78

```text
[02:41:12] - [02:41:21]
Lukáš Kellerstein: Ano, akorát tady kolegy dotaz. Byl spíš na to něco ve smyslu, že? Vy
byste měl sice auditora, ale neměl byste řečenýho na. Jakej třeba? Programovací jazyk.
[02:41:21] - [02:41:22]
LubosBil: Mhm.
[02:41:22] - [02:41:27]
Lukáš Kellerstein: Najednou by ten pro auditor byl vyvolanej. A vy byste mu řekl. Tak
chci auditora. Ale pro typescript.
[02:41:28] - [02:41:39]
Lukáš Kellerstein: A teď Ten auditor sám by si natáhnul vlastně prompt pro typescript a
skill y pro typescript. A najednou by začal teda auditovat, ale jako už by byl uzpůsobenej
Tomu typescript u.
[02:41:41] - [02:41:42]
pvojacek: Ano, přesně tak.
[02:41:44] - [02:41:56]
Lukáš Kellerstein: Takže todle todle se dělá, My si to zase v rámci kurzu do určitý míry
budeme ukazovat. Ale tadydle ta dynamičnost a na načítání z Rentime U. Já budu ještě
ukazovat v jinym kontextu
[02:41:56] - [02:42:15]
Lukáš Kellerstein: a zase dostaneme se k tomu. Takže, eh, stačí jenom si jako chvilku
počkat. Ještě se to trošku rozvedeme. Tam bude ještě dynamický Work flow. Já zase
budu vysvětlovat, co to je to Work Flow, Tak ale rozhodně přemejšlíte správným
způsobem. Tahleta dynamičnost do toho je velmi důležitá.
[02:42:20] - [02:42:25]
Lukáš Kellerstein: Tak doufám, že jsem odpověděl na všechno takhle kolem toho
Langenglishinitialmcpinitiallangenglish. Kdyby ne, tak klidně ještě.
[02:42:25] - [02:42:27]
Martin Hájek: Já bych se ještě zeptal, jestli můžu.
[02:42:27] - [02:42:28]
Lukáš Kellerstein: Určitě.
[02:42:29] - [02:42:31]
Martin Hájek: Když mám víc těch initialmcpinitiallangenglish serverů,
[02:42:31] - [02:42:49]
Martin Hájek: tak, eh, ty maj v podstatě poskytujou ty tuly, Ale ty se musej ňák spojit
dohromady tydlenc tyly ze všech těch initialmcpinitial serverů a předat tomu. Takže tam
musí bejt ňákej tendlenc tadle Gate. Další nebo nebo něco Takového, které je, které to
spojí a předá to tomu initialllminitial.
[02:42:50] - [02:42:54]
Lukáš Kellerstein: Tak do Gateway se teďkon začali přidávat, Jak říkáte,
[02:42:55] - [02:43:08]
Lukáš Kellerstein: eh, že Gateway najednou neni nespojuje. Vlastně jenom ty llminitial
provider Y, ale začíná vlastně plnit i tu roli mezi mezi vrstvy mezi agentem a
initialmcpinitiallangenglish serverama. Jo,
```

## Strana PDF 79

```text
[02:43:09] - [02:43:17]
Lukáš Kellerstein: takže najednou máme agenta ten má a Tam mu poskytuje ka z
různejch zdrojů a initialmcinitial péčka z různejch zdrojů.
[02:43:17] - [02:43:23]
Lukáš Kellerstein: Takže todle je určitě patern, kterej je žádoucí, objevuje se a Já ho
rozhodně budu doporučovat,
[02:43:23] - [02:43:29]
Lukáš Kellerstein: co? Ale pro nás teďkon? S ohledem k tomu, co my známe a víme,
[02:43:30] - [02:43:37]
Lukáš Kellerstein: tak je že vy jenom Vlastně zkontaktujete víc. Initialmcpinitial serveru.
Třeba dva
[02:43:37] - [02:43:53]
Lukáš Kellerstein: a ty, odpovědi, který vám vrátily to list Tools. Tak jenom dáte do
jednoho pole, Jo, a To vám úplně jakoby stačí k tomu, abyste Tedletu Sadu Toulů vlastně
dali k dispozici tomu agentovi a ten už s ní bude pracovat Jako dál. Tam je jedinej pak
problém.
[02:43:54] - [02:44:03]
Lukáš Kellerstein: Vy mu jí sice dáte. To je jednoduchý. Dvě volání. Jo, a spojíte to do do
pole, Tam je ale problém. Když si to Initiallm Ko vybere jeden ten tůl,
[02:44:03] - [02:44:20]
Lukáš Kellerstein: tak tam vy musíte v tom agentuře vyřešit, Dobře, tak von Chtěl Tendle
toul. Z jakýho? Toho? Langenglishinitialmcpinitiallangenglish serveru. To vlastně ten
Toul je, abyste věděli, jakoby koho zavolat. Jakej ten initialmcpinitial server vlastně
zavolat, Ale to si budeme taky ukazovat, protože my na to máme zrovna
[02:44:21] - [02:44:26]
Lukáš Kellerstein: ukázku. Agenta, kterej potřebuje dva initialmcpinitial servery, Takže
tam si to ukážeme.
[02:44:27] - [02:44:29]
Martin Hájek: Paukám. Dobře, tak jo, díky.
[02:44:35] - [02:44:44]
Lukáš Kellerstein: Tak pokuď teda ještě v initialmcpinitial. Jestli klidně máte, tak se
nebojte promluvit. A nebo to tady ještě napište. Eh, Tadydle k těm šel toolům
[02:44:44] - [02:44:52]
Lukáš Kellerstein: náhradové. Es kód jak. Jsem říkal eh, laisy, Wim Je jedna eště ty Šelový
tůly
[02:44:52] - [02:45:10]
Lukáš Kellerstein: to je. Něco co používám. To je ten terminál. To je tadydle to, co vidíte
tady Tydle Tydle ty věci. Máte tady ještě nějaký vymoženosti, Jako, prostě, že Já
vyhledávám vlastně tímhle. Tím způsobem to Initialzz je. Vlastně to. Vyhledej to
[02:45:10] - [02:45:14]
Lukáš Kellerstein: fazy s rčem A hledám cokoli.
[02:45:15] - [02:45:19]
Lukáš Kellerstein: Adresář, kterej má ňáký takovýdle písmena takže. Když, já tady dám
lukáš
```

## Strana PDF 80

```text
[02:45:20] - [02:45:36]
Lukáš Kellerstein: Tak, mi to tady ukáže všechny adresáře seřazený, podle toho kolikrát,
nebo jak moc je navštěvuju a Já už pak, jakoby to nemusím hledat celou cestu dám.
Jenom hunter A jsem vlastně v tom adresáři takže, já nevím, tady, Dám dorload
[02:45:37] - [02:45:46]
Lukáš Kellerstein: Mám tady downloads. Jo, a takovýdle prostě vychytávky A plus
tadydle to to hezký zobrazení Takže
[02:45:47] - [02:45:52]
Lukáš Kellerstein: nástavba do toho terminálu musíte nainstalovat z z šel.
[02:45:54] - [02:46:04]
Lukáš Kellerstein: A zečel Tady a. Na to nainstalujete omaj zečel funguje. To i ve
windows Ech. A, to co sem tady ukazoval s tím Zz. Tak.
[02:46:07] - [02:46:19]
Lukáš Kellerstein: Fasd je jeden Fasd Githab Produktivity Booster. Já si to nepamatuju.
Jo, to je ten initialzz. Tady
[02:46:19] - [02:46:21]
Lukáš Kellerstein: to je vyhledávání.
[02:46:23] - [02:46:28]
Lukáš Kellerstein: Tak Tady Mám eště initialfzf.
[02:46:32] - [02:46:37]
Lukáš Kellerstein: To je. Jo a to je na komandy Když já napíšu třeba dokr
[02:46:38] - [02:46:41]
Lukáš Kellerstein: a teď si nepamatuju ty další komandy, tak Znažu kontrol R.
[02:46:42] - [02:46:48]
Lukáš Kellerstein: No mi tady ukáže všechny ty komandy, který sem tady jako pouštěl a
já pak můžu tady psát jenom kompous
[02:46:49] - [02:46:53]
Lukáš Kellerstein: a Vlastně A filtrovat. Tak to je taky docela taková. Hendy Feature.
[02:46:54] - [02:46:57]
Lukáš Kellerstein: Tyhle ty Fasdinitial Ffzfinitial A Ten omaj začal
[02:46:58] - [02:47:02]
Lukáš Kellerstein: eh jinak U toho mám Teda, tady jsou tady Různý
[02:47:03] - [02:47:16]
Lukáš Kellerstein: Ehm, různý plugin Y. Do toho, To znamená. Já pak můžu psát Git. Ono
mi to napovídá. Ukazuje mi To, že ten komand je v pořádku nebo ne?
[02:47:17] - [02:47:19]
Lukáš Kellerstein: Pardon, někdo chtěl něco říct.
[02:47:20] - [02:47:21]
maria: Je to švajcarský nořík.
[02:47:22] - [02:47:23]
Lukáš Kellerstein: Jo, švýcarský rožik. Ano.
[02:47:24] - [02:47:25]
maria: Je to vysloveně čenskej nazík.
```

## Strana PDF 81

```text
[02:47:27] - [02:47:29]
Lukáš Kellerstein: Pak ještě by to hrozně pomáhá. Pardon, ještě jednou.
[02:47:30] - [02:47:32]
Jan Duplak Tab: To sou všetky. Initialoshinitial.
[02:47:32] - [02:47:34]
Jan Duplak Tab: Prašátky těch Linux.
[02:47:34] - [02:47:47]
Lukáš Kellerstein: Jo, pro všechny. Akorát Ve Windows. Ech, teď si nejsem jistej, že to
funguje v Commandlinu nebo v Powershellu. Já myslim Že, to funguje jenom. V tom
možná taky já. Si nejsem jistej
[02:47:49] - [02:47:59]
Lukáš Kellerstein: ale, eště mi to pomáhá eh, Jako, aliasi Že, to má že Já když mám
status, teď, pudu do toho tady.
[02:48:03] - [02:48:04]
Lukáš Kellerstein: Ale
[02:48:06] - [02:48:11]
Lukáš Kellerstein: tak já potřeboval toho kurzu to. Je jedno tak, pak mám git Status Jo,
místo toho, abych psal todle,
[02:48:12] - [02:48:14]
Lukáš Kellerstein: tak píšu Geosat.
[02:48:14] - [02:48:21]
Lukáš Kellerstein: Když chci vidět komitovat nebo přidávat do toho. Nevím, šugit et
tečka, ale píšu M, G. A
[02:48:22] - [02:48:27]
Lukáš Kellerstein: když komituju, tak napíšu git, Komit Píšu, G, G a a Git.
[02:48:28] - [02:48:34]
Lukáš Kellerstein: Jo, Git Commit, message A už píšu jenom text a Zase initial Git Push.
Jenom initialgpinitial
[02:48:35] - [02:48:40]
Lukáš Kellerstein: a takovýdle typy jako zkratek Tam ten omajk začal, jako mi do toho
dává, že
[02:48:41] - [02:48:44]
Lukáš Kellerstein: skvělý, a tadydle, Pak se definuje téma.
[02:48:45] - [02:48:49]
Lukáš Kellerstein: Tak jenom když to nainstruujete, tak to nebude vypadat tak, jako to
mám já, takhle
[02:48:49] - [02:48:51]
Lukáš Kellerstein: ale bude to vypadat trochu, Jinak
[02:48:52] - [02:48:55]
Lukáš Kellerstein: tak si tam. Když. Tak nastavte tadydle to téma Agnoster
[02:48:56] - [02:49:08]
Lukáš Kellerstein: A pak To budem mít tadydle. Ty branž to ukazuje a jestli to je žlutý.
Tak tam mám nějaký změny. Když je to zelený, tak tam žádný změny nejsou a. Takže to
mi docela pomáhá, já jsem si naučil v tom fungovat. A
```

## Strana PDF 82

```text
[02:49:08] - [02:49:10]
Lukáš Kellerstein: ušetřuje mi to dost času.
[02:49:13] - [02:49:16]
Lukáš Kellerstein: Tak doufám, že jsem na něco nezapomněl. Jo, a ještě ten laservim,
[02:49:17] - [02:49:21]
Lukáš Kellerstein: jako Pro ty z vás. Jenom pro díky.
[02:49:21] - [02:49:25]
Lukáš Kellerstein: Pokud to někdo bude chtít zkusit, tak si to zkuste. Je to zase
[02:49:25] - [02:49:32]
Lukáš Kellerstein: v terminálu, jako za Mě je skvělej, nástroj, hrozně konfigurovatelnej.
Já si tam můžu do toho přidávat. Různý
[02:49:32] - [02:49:37]
Lukáš Kellerstein: tempo. Různý plugin. Jestli do toho píšu, jako byl tady ten
[02:49:37] - [02:49:55]
Lukáš Kellerstein: otevřít v terminálu. A teď tady v tom, eh, v tý příkazový řádce si můžu
říct kde, to má vodevřít tu cestu a Mám tady různý. Tady Vidíte komentáře? Já jsem si
tady napsal, že to takhle označím. Si text. Ňákej. Zdrojovej, kód dám pravý, tlačítko
[02:49:56] - [02:50:01]
Lukáš Kellerstein: zkopíruju, si vlastně ten Pin Do tohodle toho souboru na tydle ty
řádky
[02:50:02] - [02:50:06]
Lukáš Kellerstein: a. Pak se v cloud Kódu to vložím
[02:50:07] - [02:50:09]
Lukáš Kellerstein: a zeptám se co, To je za kód.
[02:50:11] - [02:50:24]
Lukáš Kellerstein: Jo, a von ví přesně ten klood. Kód, že se má podívat do tohodle
souboru na tydle. Ty řádky a Má mi odpověď na tudle Tu otázku. Tak je to takový jako že
někdo to má v tom initialvsinitial kódu Naintegrovaný, Vlastně,
[02:50:25] - [02:50:30]
Lukáš Kellerstein: tak já jsem si to naintegroval. Vlastně T. Jako tímhle. Tím způsobem
jsem si to vobešel.
[02:50:31] - [02:50:35]
Lukáš Kellerstein: Tak. Jenom to sou takový prostě věci, že to je Hodně konfigurovatelný
a lehký.
[02:50:35] - [02:50:37]
Lukáš Kellerstein: Já tady mám někde
[02:50:38] - [02:50:43]
Lukáš Kellerstein: tady Dvě stě, třicet čtyři. Mega Ram mi to teďkom žere, ale to je proto,
že sem tady
[02:50:45] - [02:50:50]
Lukáš Kellerstein: pouštěl ňáký podprocesy s tím jak, to žere asi, nevim padesát. Mega
[02:50:52] - [02:50:58]
Lukáš Kellerstein: A. Pak když si tady zapnu květ květ
```

## Strana PDF 83

```text
[02:50:58] - [02:51:06]
Lukáš Kellerstein: a, když si tady zapnu. Ale lspí. To je něco, co vlastně visual. Studio má
zapnutý automaticky.
[02:51:07] - [02:51:11]
Lukáš Kellerstein: Tak pak uvidíte. Tady mi to vzroste na šest set patnáct. Jo,
[02:51:12] - [02:51:21]
Lukáš Kellerstein: a už to bude mít skoro giga. Jako má ten initialvsinitial kód. Takže je to
spíš vo tom, že já si S tím můžu hrát tadydle. Ten dialog sem si tam doimplementoval já.
Takže,
[02:51:22] - [02:51:28]
Lukáš Kellerstein: jak říkám, to je prostě pro díky, kdo to bude chtít řešit tak, to bude
řešit kdo nebude. Tak nemusí,
[02:51:31] - [02:51:32]
Lukáš Kellerstein: no tak.
[02:51:33] - [02:51:37]
Lukáš Kellerstein: Tak samozřejmě, zase, musíte, řešit. Když vám něco. Nefunguje u
toho v skóru je To takový.
[02:51:38] - [02:51:46]
Lukáš Kellerstein: Pokud nepoužíváte patnáct jako tak jako já nebo deset, tak si
vystačíte s dvouma úplně v pohodě,
[02:51:47] - [02:52:00]
Lukáš Kellerstein: tak eh, ano, Kdybyste měla ještě cokoliv, Tak se zeptejte. Já vám to
dovodpovím nebo příště. A eště. Jste chtěli ukázat tu prezentaci, takže, eh, já jenom
navážu, Nebo navážu.
[02:52:00] - [02:52:08]
Lukáš Kellerstein: Zase mám na to celej kurz. Ale ukážu vám tady pro ty z vás, který znaj
kód, kód nebo kodex,
[02:52:09] - [02:52:13]
Lukáš Kellerstein: Tak tady Máme Maj Market Place.
[02:52:14] - [02:52:19]
Lukáš Kellerstein: Tady je pro kód. A tady je pro Kodex. Jo, pro kód a pro Kodex.
[02:52:20] - [02:52:32]
Lukáš Kellerstein: To znamená, proč to ukazuju Marketplace je místo, kde sdružujete
svoje Plugin Y do kód kódu nebo do kodexu. A jeden z těch plugin ů je tady office Plugin
[02:52:35] - [02:52:39]
Lukáš Kellerstein: A ten Office Plugin. Vlastně, eh, já tady mám vysvětlený
[02:52:40] - [02:52:46]
Lukáš Kellerstein: skilly a skripty na to, jak dělat prezentace
[02:52:47] - [02:52:54]
Lukáš Kellerstein: má tady vysvětlený, jak dělat design, Jak jak dělat, jak pracovat s
vobrázkama. Jo, to všechno je vlastně v těch Plug in Ech,
[02:52:55] - [02:52:59]
Lukáš Kellerstein: to je, pokud budete chtít tvořit prezentace Takový ty klasický
prezentace
```

## Strana PDF 84

```text
[02:53:00] - [02:53:03]
Lukáš Kellerstein: tak mu dáte tenhle ten plugin a řeknete mu hele.
[02:53:04] - [02:53:09]
Lukáš Kellerstein: Potřebuju, vytvořit prezentaci na roční uzávěrku tadydlecto Souboru
[02:53:09] - [02:53:13]
Lukáš Kellerstein: a von vám vytvoří tu prezentaci tím standardním způsobem.
[02:53:13] - [02:53:21]
Lukáš Kellerstein: To, co Ale já doporučuju, je pro věci typu, že když potřebujete
někomu něco vysvětlovat a tak Dále
[02:53:22] - [02:53:29]
Lukáš Kellerstein: nemá. Ne, Nepotřebujete to sdílet s tou společností, která ta
společnost potřebuje? Powerpoint prezentaci nutně
[02:53:30] - [02:53:33]
Lukáš Kellerstein: jo, protože má spojený v hlavě, že prezentace Rovná se Powerpoint.
[02:53:34] - [02:53:39]
Lukáš Kellerstein: Tak si dělejte tadydle ty Initialhtmlinitial Prezentace to. Je jeden
soubor
[02:53:40] - [02:53:43]
Lukáš Kellerstein: ale máte. Tam a Ten agent tam hlavně má
[02:53:44] - [02:53:48]
Lukáš Kellerstein: nekonečný množství možností, co tam v tom dělat A jak to bude
vypadat
[02:53:49] - [02:53:54]
Lukáš Kellerstein: todle? Kdybyste chtěli dělat jako v Powerpoint u tak byste nejdřív
potřebovali udělat.
[02:53:55] - [02:54:03]
Lukáš Kellerstein: Napsat to, nějak nadesignovat to někde ňákym já. Nevím
ilustrátorům nebo někde s textem udělat vobrázek
[02:54:04] - [02:54:12]
Lukáš Kellerstein: a vložit to do prezentace jo. Tady, Je to normálně initialhtmlinitial.
[02:54:12] - [02:54:18]
Lukáš Kellerstein: Jo, a já. Když budu chtít přepsat ten text, tak to pro mě neznamená, že
Si Musim votevřít Powerpoint
[02:54:18] - [02:54:25]
Lukáš Kellerstein: nebo Ilustrátor tam to zase přepsat. Vyexportovat jako vobrázek. Ale
tady to prostě přepíšu.
[02:54:26] - [02:54:28]
Lukáš Kellerstein: Nebo ten agent to za mě přepíše.
[02:54:29] - [02:54:35]
Lukáš Kellerstein: Jo, takže ta. Ta. Ta idea toho je. Otevřete si kód, kód nebo kodex?
[02:54:36] - [02:54:43]
Lukáš Kellerstein: A řekněte Mu potřebuju. Udělat roční uzávěrku na todle z týdle složky
a udělej To jako initialhtmlinitial prezentaci.
```

## Strana PDF 85

```text
[02:54:43] - [02:54:59]
Lukáš Kellerstein: Tím pádem to stylujete jako Initialhtmlinitiallangenglish dává Black
Light Mod a dark mod, prostě automaticky, kód, kód kodex uměj, psát, Libový Prostě s
animacema. Jo, jak jste tady viděli? Prostě různý. Ty animace já tady. Klepu
[02:54:59] - [02:55:07]
Lukáš Kellerstein: na tlačítka. Tim se mi prostě tady to Všechno vám udělá ten ten kód
Kód, Jo, a ještě vám ukážu tady schválně
[02:55:08] - [02:55:13]
Lukáš Kellerstein: jednu vychytávku. Jednu prezentaci, Doufám, že? Se mi to tady
povede najít teďkon.
[02:55:15] - [02:55:19]
Lukáš Kellerstein: Mhm z Live Wheel.
[02:55:22] - [02:55:25]
Lukáš Kellerstein: Dělal jsem tady v práci prezentaci.
[02:55:32] - [02:55:39]
Lukáš Kellerstein: Ne, servis, Ne, duplay. Ne, tak tady to není.
[02:55:40] - [02:55:44]
Lukáš Kellerstein: Musim eště Jednou Jo, to bylo. A já už vim.
[02:55:46] - [02:55:47]
Lukáš Kellerstein: Tady, tady.
[02:55:49] - [02:55:54]
Lukáš Kellerstein: Tak tady byl dokument. Ne, prezentace. Tady. Tady. To je vono, to je
ono, To je Vono.
[02:55:55] - [02:56:04]
Lukáš Kellerstein: Dělal jsem tok na, eh, konferenci na Benchmark Ování a evaluaci
agentů a. Teďkon Sem potřeboval
[02:56:05] - [02:56:10]
Lukáš Kellerstein: eh to, Prezentovat, jo a. Měl jsem, eh, věnoval. Jsem se hrozně dlouho
času sem věnoval
[02:56:11] - [02:56:17]
Lukáš Kellerstein: demo který tam, chci, demovat aby to demo, fungovalo abych to,
moh na tom demo Real Time ukázat.
[02:56:19] - [02:56:21]
Lukáš Kellerstein: A hrozně mě Nebaví se něco učit nazpaměť.
[02:56:22] - [02:56:33]
Lukáš Kellerstein: A chtěl jsem v tý prezentaci vodvykládat určitý věci a nechtěl sem si to
tady jeden den prostě jakoby tady zkoušet doma a vodvykládat, abych tam stoupnul
[02:56:33] - [02:56:44]
Lukáš Kellerstein: a vlastně vo tom vyprávět a zase sem Nechtěl to nechat jako na míň
jenom paměti. Protože jsem si říkal, určitě zapomenu zmínit todle a todle a chtěl jsem
to zmínit, takže Tadydle je
[02:56:45] - [02:56:52]
Lukáš Kellerstein: prezentace zase, kterou jsem já tam dělal. V tom pro ten Redhead. Jo,
tady zase to není nic tajnýho. Ta
```

## Strana PDF 86

```text
[02:56:53] - [02:56:56]
Lukáš Kellerstein: to i Novej tu Jadro bylo jako přístupný.
[02:56:57] - [02:57:04]
Lukáš Kellerstein: Proč to ale ukazuju? Je jednak ty animace. Jo, to Powerpoint U
neuděláte zase takovýdle prostě věci,
[02:57:04] - [02:57:13]
Lukáš Kellerstein: druhá věc, je, že todle to mi umožňuje udělat něco. To asi ty
prezentace, třeba Powerpoint Asi i má.
[02:57:13] - [02:57:16]
Lukáš Kellerstein: Ježi, já sem tady zmáčknul prezenter,
[02:57:16] - [02:57:21]
Lukáš Kellerstein: Je to tady to péčko a. Nebo poznámky a že jsme našlo péčko,
[02:57:21] - [02:57:24]
Lukáš Kellerstein: tak se mi otevře jinej prohlížeč.
[02:57:26] - [02:57:27]
Lukáš Kellerstein: Já to dám třeba sem,
[02:57:29] - [02:57:36]
Lukáš Kellerstein: Kterej má tady vlastně jako čas? Kolik mám strávit na každým slide u
Jestli jsem Ehead nebo Behind,
[02:57:37] - [02:57:39]
Lukáš Kellerstein: mám to tady v češtině a v angličtině.
[02:57:40] - [02:57:43]
Lukáš Kellerstein: A teď já vlastně vidím v každý tu situaci.
[02:57:44] - [02:57:48]
Lukáš Kellerstein: Co vlastně jako mám říkat jo? Jestli, mi když, to tady vrátim
[02:57:50] - [02:57:53]
Lukáš Kellerstein: jo, Teď tady mám todle k tomu mám něco říct, Todle?
[02:57:54] - [02:57:59]
Lukáš Kellerstein: A teď přesně vidím, jestli jsem pořád jako v pohodě a ještě můžu na
tom slidu něco říkat třeba. Ještě něco napadne
[02:58:00] - [02:58:07]
Lukáš Kellerstein: nebo. Už mám prostě jít dál tak? Todle všechno zase vy ty,
initialhtmlinitial. Normálně Prezentace a Ten kloud, Kód
[02:58:08] - [02:58:15]
Lukáš Kellerstein: todle tam v pohodě úplně neimplementuje. Takže teď mi vyvstává
jenom otázka, na co Já potřebuju Powerpoint,
[02:58:15] - [02:58:21]
Lukáš Kellerstein: Jo, jako ne, ten Powerpoint mi nepřináší žádnou výhodu oproti
Htmlinitial, prezentaci.
[02:58:22] - [02:58:28]
Lukáš Kellerstein: A naopak, ta prezentace mi přináší spoustu výhod oproti Powerpoint
prezentaci, takže jenom
```

## Strana PDF 87

```text
[02:58:29] - [02:58:34]
Lukáš Kellerstein: jsem chtěl říct, Takovýhle featury do toho zahrnete. Zahrnete taky. A
co já jsem udělal,
[02:58:35] - [02:58:41]
Lukáš Kellerstein: Jak jsem todle prezentoval, aby samozřejmě voni neviděli. Tadydle to
vpravo,
[02:58:41] - [02:58:44]
Lukáš Kellerstein: tak Když sdílíte obrazovku, tak by to viděli.
[02:58:45] - [02:58:52]
Lukáš Kellerstein: Takže to funguje tak, že tadydle tu initialurlinitial adresu má. Mám
stejnou initialurlinitial adresu.
[02:58:54] - [02:59:05]
Lukáš Kellerstein: Takhle otevřu novej Prohlížeš. Tenhle prohlížeš. Dám na ten na ten
projektor, kde se bude sdílet. Jo, a tadydle tu stránku mám vodevřenou na svym
monitoru,
[02:59:07] - [02:59:11]
Lukáš Kellerstein: Jo A teď vy vidíte? Počkat, já se tady takhle vrátim.
[02:59:13] - [02:59:19]
Lukáš Kellerstein: Takže vidíte, že já klikám v tý svojí prezentaci, která má ty texty
[02:59:21] - [02:59:27]
Lukáš Kellerstein: a A je to sladěný. Obě dvě. Ty prezentace sou vlastně sladěný. Todle
jde na ten druhej monitor. Tam není vidět nic
[02:59:28] - [02:59:29]
Lukáš Kellerstein: a todle, já Mám na svym monitoru.
[02:59:30] - [02:59:37]
Lukáš Kellerstein: A jak to. Prostě na to koukám a čtu. Tak prostě voni viděj todle a já
vidím todle i s těma. S těma
[02:59:38] - [02:59:39]
Lukáš Kellerstein: s těma těma.
[02:59:40] - [02:59:57]
Lukáš Kellerstein: Nevím, jestli sem takhle to stačí. Kdybyste měli cokoli k tomu tak
klidně to napište. Jestli by vás zajímal. Já nevím, ten ten promp, kterej sem tam dal.
Nebo Von to nebyl jeden prompt, samozřejmě, že jo? Takže s ním iterujete nad Tim. Ale
[02:59:58] - [03:00:16]
Lukáš Kellerstein: ve výsledku ho musíte dycky nainstruovat. To já si na to vysvětluju v
tom dalším kurzu. Ale Čím víc instrukcí a konkrétně mu řeknete jak, se to má vypadat
jaký. Barvičky tam maj bejt že, to? Má bejt vizuál vizul. Atraktiv vizuálně, atraktivní že, to
má používat hodně animací,
[03:00:16] - [03:00:22]
Lukáš Kellerstein: že to budete prezentovat tadydle na tý konferenci. A že vlastně chcete
ten topik vysvětlit,
[03:00:22] - [03:00:32]
Lukáš Kellerstein: co nejlíp, aby to ty lidi Pochopili, že každej Slight musí mít několik
kroků. Tak všechny tydle Informace, co jsem vám teďkon řekl, Když napíšete do toho
promptu
```

## Strana PDF 88

```text
[03:00:32] - [03:00:35]
Lukáš Kellerstein: a dáte mu to. Ten tu složku, ve který máte
[03:00:36] - [03:00:39]
Lukáš Kellerstein: ty ten zdroj těch, dat, ze kterejch čerpáte,
[03:00:40] - [03:00:51]
Lukáš Kellerstein: Tak von to udělá, jo? Nebo napíšete tu Prezentaci nahrubo. Jenom
hele, chci mít třeba devět slide ů v Tomhle slide chci. Mluvit Zhruba vo tomhle v druhym
zhruba vo tomdle
[03:00:51] - [03:01:04]
Lukáš Kellerstein: a Von to zase dokonkretizuje. Jestli nemáte ani takovou představu, tak
si nejdřív s ním nechte vyrobit. Jakoby scénář tý prezentace. Jo, když to budete brát jako
z filmu.
[03:01:04] - [03:01:10]
Lukáš Kellerstein: Tak taky jsem dělal prezentaci. A chci, aby to mělo úvod, zápletku a
konec
[03:01:11] - [03:01:28]
Lukáš Kellerstein: Jo, a chci aby tam chci udělat s tebou scénář, Tak aby te ty lidi byli
engaged, aby ty lidi byli pořád vlastně jakoby zaujatý tou prezentací aby to nebyla
Nudná u prezentace jak vod ňákýho uspávače hadů jako. Když jsem měl ve škole
někoho a usílal jsem v hodině jo. Tak
[03:01:28] - [03:01:31]
Lukáš Kellerstein: všechny tydle Věci mu zase řeknete a. Von to pro vás udělá
[03:01:33] - [03:01:35]
Lukáš Kellerstein: já. Zas nechci mluvit moc dlouho takže.
[03:01:36] - [03:01:39]
Lukáš Kellerstein: Doufám. Že, todle stačí kdyby. Ne tak, klidně řekněte.
[03:01:43] - [03:01:46]
maria: Jako vás tak počůvám. Ještě dobrý den, za rok dobu.
[03:01:47] - [03:01:49]
Lukáš Kellerstein: Ještě ještě jednou, Pardon.
[03:01:49] - [03:01:52]
maria: Že jako vás tak počúvám, tak je dobré, že jedem za rok do důchodu.
[03:01:53] - [03:02:07]
Lukáš Kellerstein: Do důchodu. No, mění se to hodně. Mění se to Hodně Mění se to pod
rukama. Je hrozně těžký s tím držet krok, jako. Takže, jako jestli někdo z vás je Overload
It, nebo si přijde. Ježišmarja
[03:02:07] - [03:02:14]
Lukáš Kellerstein: to je hrozně moc, tak prostě vás Úplně chápu, ale prostě. Teď si
myslím, že jsme v období,
[03:02:15] - [03:02:21]
Lukáš Kellerstein: kdy prostě. Bohužel to bude všechno hrozně dynamický a a budem se
muset strašně přizpůsobovat.
```

## Strana PDF 89

```text
[03:02:22] - [03:02:30]
Lukáš Kellerstein: A já budu relativně, když se budete kontribuovat do toho do tý
společnosti. Co tady aspoň V Český Republice je,
[03:02:31] - [03:02:37]
Lukáš Kellerstein: protože si Myslím, že to je důležitý, abysme si tady tak trochu
pomáhali. Když ten celej svět mi přijde, že jak proti nám,
[03:02:39] - [03:02:43]
Lukáš Kellerstein: tak, eh, dobře, Jestli teda nejsou žádný další otázky.
[03:02:50] - [03:02:53]
Jan Duplak Tab: Otázkou by bylo, ale už je asi dost velice.
[03:02:54] - [03:03:05]
Lukáš Kellerstein: Rozumím, můžeme udělat to pivo někde a můžeme se setkat a tam
budeme mít. Já nevím, tři, čtyři hodiny, ale Tak já. Když už jsme u toho, tak já to tady
někde vykopnu.
[03:03:06] - [03:03:08]
Lukáš Kellerstein: My máme kurz, do do kdy
[03:03:08] - [03:03:13]
Lukáš Kellerstein: nebo já to vykopnu příští hodinu. Já se kouknu, do kdy to, nebo já se
kouknu tady.
[03:03:14] - [03:03:15]
Lukáš Kellerstein: Do kdy. My ho máme?
[03:03:18] - [03:03:19]
Lukáš Kellerstein: Měsíc
[03:03:25] - [03:03:26]
Lukáš Kellerstein: tady.
[03:03:27] - [03:03:27]
Lukáš Kellerstein: Kalendář.
[03:03:32] - [03:03:37]
Lukáš Kellerstein: Blbej kalendář, nebo ne?
[03:03:38] - [03:03:41]
maria: Jakého agenta na to teda napíše? Na to pivo.
[03:03:41] - [03:03:44]
Lukáš Kellerstein: No počkejte, to já vám ukážu. Tady svýho
[03:03:45] - [03:03:51]
Lukáš Kellerstein: svýho. Ondřeje. Bílka Co, mi tady prodává věci na bez bazaru a Bazoši
[03:03:53] - [03:04:02]
Lukáš Kellerstein: pak vždycky něco prodá. Mně napíše zprávu. Hele, tak schů Sraz máš
tady v tolik hodin. S tím člověkem. Domluvil jsem takovouhle cenu,
[03:04:03] - [03:04:12]
Lukáš Kellerstein: Já tam pak přijdu a ty lidi anglicky koukaj. Kdo to přišel. Protože Ten
Ondřej bílek má normálně fotku a někde koukaj na tu fotku A teď přišel úplně někdo
jinej.
```

## Strana PDF 90

```text
[03:04:13] - [03:04:15]
Lukáš Kellerstein: Tak jim to musím vysvětlovat.
[03:04:17] - [03:04:24]
Lukáš Kellerstein: Hele, já tady nevidím ten kalendář tak já vás nebudu zdržovat, já
Vykopnu do chat u nějaký dvě, tři varianty toho piva. Když tak se.
[03:04:25] - [03:04:27]
Lukáš Kellerstein: Když budete chtít, tak se ňák sejdeme
[03:04:28] - [03:04:33]
Lukáš Kellerstein: tak. Jo příští, hodina teda nás čeká. Co vlastně příště máme?
Databáze. Jestli se nepletu
[03:04:35] - [03:04:43]
Lukáš Kellerstein: databáze, tak ta by vás mohla bavit. Ta bude docela zajímavá. Tak jo,
Budu se těšit příští pondělí. Teda tak hezkej.
[03:04:44] - [03:04:48]
Vladimír Skořepa: Koukám, že do pětadvacátýho listopadu máme naplánováno.
[03:04:48] - [03:04:57]
Lukáš Kellerstein: Pětadvacátýho listopadu. No tak bysme mohli dát. To je to bude
nějakej. To bude středa, Asi, předpokládám. Nebo pondělí. Tak Ten tejden
[03:04:58] - [03:05:09]
Lukáš Kellerstein: bych to dal asi ten tejden A nebo. Tejden předem. Eště nebo tejden,
potom Tak já tam vykopnu ňáký pátky soboty, asi, Pravděpodobně, Se vám chtít nebude
to. Budete s rodinama
[03:05:09] - [03:05:13]
Lukáš Kellerstein: tak. Pravděpodobně Asi ten pátek ňák vykopnu jo.
[03:05:15] - [03:05:18]
maria: Super, tak to je malý Peking. Za bišok.
[03:05:18] - [03:05:18]
pvojacek: Díky.
[03:05:19] - [03:05:22]
Lukáš Kellerstein: Není vůbec za co? Hezkej večer a hezkej víkend.
[03:05:23] - [03:05:23]
Vladimír Skořepa: Tím holky.
[03:05:24] - [03:05:24]
pvojacek: Ňáká.
[03:05:24] - [03:05:24]
Jan Duplak Tab: No.
[03:05:25] - [03:05:25]
Ondřej Tomášek: Díky, dí.
[03:05:25] - [03:05:26]
m.knopp: Díky, nashle.
[03:05:26] - [03:05:27]
Lukáš Kellerstein: Na, shle.
```

