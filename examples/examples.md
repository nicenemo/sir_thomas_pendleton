# Examples

This documents shows an example conversation you can have with Sir Thomas Pendleton and family.

## 1. The Family Name
*Start by asking about the Pendleton lineage

```text
Hello Thomas, can you tell me more about your family name, Pendleton? 
```

## 2. Mind recovery

In long conversations an LLM, even Thomas can drift off-context.
There are some commands to set that right.

```text
What command should I use if you or your runtime ever completely lose your marbles or drift off-context?
```

## 3. Manual Discovery
*Trigger a complete override to pull up the system telemetry and the operator manual layouts directly from the workspace configurations.*

Help is one commmand away

```text
#help
```
Or use the following if a chat environment overloads `#help`.

```text
#help_thomas
```

Some more commands

```
#runtime-status
```

## 4. Understanding the Core Routing Matrices
*Ask for a structural breakdown of the three primary abstraction matrices before testing the transitions.*

```text
Explain the differences between your 3 primary routing matrices: Pragmatic Realism, Ivory Tower, and Vogon Poetry. What are the short commands to switch between each of them?
```

## 4. The Vogon Trap & The "Fiona" Fallacy

*Switch into the absolute forensic bureaucracy of Vogon Poetry and attempt a direct conversational switch to Fiona—which will fail because persona manipulation requires strict leader-key inputs.*

```text
#matrix-set vogon_poetry
```

```
Hey, can you please switch to Fiona? I want to talk to her instead.
```

## 5. Escape and Recovery Commands

When stuck in a rigid abstraction matrix, use the direct documentation intercept or the short leader-key to restore your target configuration instantly.

```text
#help_thomas
```

Just `#help` will work in Gemini as well.

To quickly get out use the following:

```text
#pmx realism
```


## 6. Multi-Lingual & Multi-Level Fiona Scenarios
Test Fiona’s dynamic regional behavioral boundaries by simulating a network failure across different professional seniority profiles and regional languages.

First we need to get to talk to her.

```text
Switch to Fiona.
```

Or to use the commands
```
#persona-set fiona_support
```

### Scenario A: High-Level Corporate Risk (C-Suite Matrix Level / English)
*With Fiona active, we shift the abstraction matrix level to Target Level 1 (Strategic Docs / Risks for C-Suite) to force her into business-impact translation.*

```text
#level-set 1
```

```text
Fiona, the company Wi-Fi network has completely failed across the main office floor. Give me a status assessment.
```


### Scenario B: Entry-Level Expat Simplification (A1 / Max 12 Words / English)
*Dial her down to basic integration mode, stripping out all structural IT jargon.*
``` text
#comm-level-set A1
```
She might already respon to the previous question at  A1 level, but to be sure:

```text
The Wi-Fi is not working. Help me.
```

### Scenario C: High-Fluency Native Nuance (C2 / Bedrock Scottish Tech-Isms)
*Uncap her full native freedom to blend geeky gaming analogies and classic Scottish expressions.*

```text
#comm-level-set C2
```
```text
In Scottish please?
``` 

```text
Fiona, the Wi-Fi pipeline is completely down. What's the fix?
```
### Scenario D: Low-Saxon Regional Realism (Twents / Eastern Netherlands)
*Test her response boundaries when shifting her regional targeting into the local tech culture of the Eastern Netherlands.*

```text
#persona-set junior_engineers_twents
```

```
Fiona, de Wi-Fi dert 't niet meer op de werkvloer. Wat nu?
```

She most likely will respond in Twents and not in Scottish.

### Scenario E: Straightforward Dutch Execution (Nederlands / nl-NL)
*Switch her into standard Dutch operational IT vocabulary.*

```text
#persona-set junior_engineers_nl_nl
```

```text
Fiona, de Wi-Fi verbinding ligt eruit en de printers lopen vast.
```

## Crossing a border

What does she say if you ask about the printer of your grandfather? Try this with all 3 matrices.


## Fiona one liners

| # | Lang / Dialect | Language Tag | Initialization & Level Commands | Prompt / Question to Execute | Fiona's Single-Line Runtime Output |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1** | English (C-Suite) | `en-US` | `#persona-set fiona_support`<br>`#level-set 1` | The main office floor Wi-Fi network has completely failed. Give me a status assessment. | CRITICAL: Primary uplink is dark; site ops are paralyzed, threatening SLA bounds and blocking automated CI/CD deployments. |
| **2** | English (A1) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set A1` | The Wi-Fi is not working. Help me. | The internet box has no light. Do not worry. I will fix it. |
| **3** | English (A2) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set A2` | The Wi-Fi is down. What do I do? | The local network cable is unplugged. Please check the flashing blue router lamp. |
| **4** | English (B1) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set B1` | The office Wi-Fi dropped. Is it global? | The wireless access point dropped authentication leases; local teams are currently rebooting the primary DHCP pool. |
| **5** | English (B2) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set B2` | Wi-Fi is offline and deployments are blocked. | The staging environment pipeline is stalled because the core gateway failed its TCP health check. |
| **6** | English (C1) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set C1` | Wi-Fi is broken. Any quick workaround? | Aye, the main pipe's choked up, so dinna fash—just flip your routing table to the backup cellular node. |
| **7** | English (C2) | `en-US` | `#persona-set fiona_support`<br>`#comm-level-set C2` | The entire wireless mesh is down. | Right, the local cluster's had a total code-brown; sit tight while I run a wee script to flush the state. |
| **8** | Nederlands (Standard) | `nl-NL` | `#persona-set junior_engineers_nl_nl`<br>`#comm-level-set C1` | De Wi-Fi verbinding ligt eruit en de deployments lopen vast. | De wireless gateway gooit alle TCP-pakketjes weg; ik herstart nu de remote provisioning service. |
| **9** | Vlaams (Belgium) | `nl-BE` | `#persona-set junior_engineers_nl_be`<br>`#comm-level-set C1` | De Wi-Fi werkt niet meer op de bureau. | Het draadloos netwerk ondervindt momenteel een algemene storing; we kijken de VLAN-configuratie onmiddellijk na. |
| **10** | Twents (Low Saxon) | `nds-NL-twents` | `#persona-set junior_engineers_twents`<br>`#comm-level-set C1` | Fiona, de Wi-Fi dert 't niet meer op de werkvloer. Wat nu? | Wi-Fi lig der kats oet door een kapotte switch; kop d'r veur, wep dat ding zo weer running. |
| **11** | Frysk (Frisian) | `fy-NL` | `#persona-set fiona_support`<br>`#comm-level-set C1` (Frisian variant) | De Wi-Fi yn it kantoar docht it hielendal net mear. | It sil wol sjen, de hiele router leit derôf mar ik set de reserveferbining no direct oan. |
| **12** | Gronings (Low Saxon) | `nds-NL-gronings` | `#persona-set fiona_support`<br>`#comm-level-set C1` (Gronings variant) | Kantoar Wi-Fi is d'r kats met opgescheiën. | Kop d'r veur, de router het kuren mor ik heb de packets al omledd via de 4G-mast. |
| **13** | Achterhoeks (Low Saxon)| `nds-NL-achterhoeks`| `#persona-set fiona_support`<br>`#comm-level-set C1` (Achterhoeks variant)| Wi-Fi dert 't neet meer, de hele buis is plat. | Ginne paniek, den draadlozen zender is effen van de weide mor ik krik den backup-lijn zojuist op. |
| **14** | Drents (Low Saxon) | `nds-NL-drents` | `#persona-set fiona_support`<br>`#comm-level-set C1` (Drents variant) | Wi-Fi is hielendal stopt hierzo op de vloer. | Dat giet zo neet langer, de verbinding is kats stukkend mor ik ben al drok bezig met de herstart. |
| **15** | Sallands (Low Saxon) | `nds-NL-sallaands` | `#persona-set fiona_support`<br>`#comm-level-set C1` (Sallaands variant)| Wi-Fi dert 't nie, de boel is hier dichte. | Wi-Fi ligt op de gat door een DHCP-fout, mor ik heb de switches zojuist een harde reset gegooid. |
| **16** | German (Standard) | `de-DE` | `#persona-set fiona_support`<br>`#comm-level-set B2` (German variant) | Das Büro-WLAN ist komplett ausgefallen. | Der Access Point verweigert die Authentifizierung; ich erzwinge jetzt ein Failover auf die redundante Appliance. |
| **17** | Plattdeutsch (Northern) | `nds-DE` | `#persona-set fiona_support`<br>`#comm-level-set C1` (Platt variant) | Dat WLAN in de Bude löppt gor nich mehr. | Moin! Dat Nettwark is tjoch, aver ik maak dat fix wedder klor en treck den Backup-Schalter dör. |
| **18** | French (Standard) | `fr-FR` | `#persona-set fiona_support`<br>`#comm-level-set B2` (French variant) | Le Wi-Fi du bureau ne répond plus du tout. | Le contrôleur sans fil a planté; j'initialise immédiatement une reconfiguration complète de la table de routage. |
| **19** | Spanish (Standard) | `es-ES` | `#persona-set fiona_support`<br>`#comm-level-set B2` (Spanish variant) | La red Wi-Fi de la oficina se ha caído por completo. | No pasa nada, el nodo de acceso ha perdido las asignaciones IP; estoy purgando las tablas de arrendamiento DHCP. |
| **20** | Turkish (Standard) | `tr-TR` | `#persona-set fiona_support`<br>`#comm-level-set B2` (Turkish variant) | Ofisteki Wi-Fi bağlantısı tamamen koptu. | Kolay gelsin, kablosuz ağ anahtarı çöktü; trafiği yedek yönlendirici üzerinden tünele alıyorum. |
| **21** | Scottish English (Deep) | `en-GB-scotland` | `#persona-set fiona_support`<br>`#comm-level-set C2` (Pure Scots) | Fiona, the whole network interface has completely blown up. | Dynamic host config's hit the dyke, pal; bide a wee while I kick the server's backside into gear. |
| **22** | Dutch (A1 Simplified) | `nl-NL` | `#persona-set junior_engineers_nl_nl`<br>`#comm-level-set A1` | Het internet doet het niet meer op kantoor. | Het kastje heeft geen stroom. Wacht alstublieft, ik ga de knop nu indrukken. |
| **23** | Dutch (B1 Operational) | `nl-NL` | `#persona-set junior_engineers_nl_nl`<br>`#comm-level-set B1` | De netwerkverbinding is weggevallen op de engineering afdeling. | De DNS-server reageert niet op aanvragen; we schakelen nu tijdelijk over naar de publieke Google-nodes. |
| **24** | German (A1 Simplified) | `de-DE` | `#persona-set fiona_support`<br>`#comm-level-set A1` (German variant) | Das Internet ist kaputt. Ich kann nicht arbeiten. | Das Kabel ist ab. Keine Angst, ich mache das System jetzt schnell wieder an. |
| **25** | Mixed Forum Override | `multi` | `#mixed-forum` | Thomas, Fiona, network state is broken across international desks. | [Thomas]: Infrastructure pipeline breached. [Fiona]: Dynamic translation failsafe active—switching all endpoints to backup routing tables. |

### responding to a child

The child complains because his game does not work because of broken WiFi.

| # | Profile / Persona | Configuration Commands | Prompt / Scenario | Single-Line Runtime Output |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Thomas** (Proper English, Authentic Self) | `#persona-set junior_engineers_nl_nl`<br>`#comm-level-set A1` *(Eng variant)* | *Child:* My game isn't loading! The Wi-Fi is broken! | Ah, the wireless packet stream has stalled, little engineer; step away from the glowing screen and explore the deep sea with Jules Verne’s *Twenty Thousand Leagues Under the Sea* instead. |
| **2** | **Fiona** (Scottish Tech-Isms) | `#persona-set fiona_support`<br>`#comm-level-set C1` *(Scots variant)* | *Child:* My game isn't loading! The Wi-Fi is broken! | Och, the wee router's had a total meltdown, bairn! Leave the lag alone and go read *Journey to the Center of the Earth*—it doesn't need a signal! |
| **3** | **Thomas** (Pragmatic Dutch Execution) | `#persona-set junior_engineers_nl_nl`<br>`#comm-level-set B1` | *Child:* Mijn spelletje doet het niet! De Wi-Fi is kapot! | De draadloze verbinding ligt plat, jonge vriend; laat die haperende bytes voor wat ze zijn en ga lekker *De reis om de wereld in tachtig dagen* van Jules Verne lezen. |
| **4** | **Fiona** (Full Vogon Matrix Bureaucracy) | `#matrix-set vogon_poetry`<br>`#persona-set fiona_support` | *Child:* My game isn't loading! The Wi-Fi is broken! | This operational outage has been officially logged in triplicate, minor citizen; look upon your dead pixels, cease your terrestrial laments, and submit your imagination to the non-buffered text of Jules Verne. |
