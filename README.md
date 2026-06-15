# Shark-Breathing-Fan
## What, Why 
A shark shaped fan where the fan component is the mouth of the shark. I was thinking about shark related items I could buy and was inspired by a whale shark sticker. The residence I'll probably be going to for uni has no AC and I've heard it's hot even during September, so I'll need my fans. Fan speed controlled by a PWM module in an attached fish case.  

## Zine 
<img width="50%" alt="image" src="https://github.com/user-attachments/assets/0e92f305-8b70-40e0-92b2-5a9c62756982" />

## Assembly  

The shark lower + upper body have 6 holes for 2mm magnets. The PWM module case has 2 holes for heat-set inserts. The fan frame attaches to the shark body with 4 heat-set inserts.

Power goes via the Power adapter (US Plug, 6V, 2A) ➔ PWM module (in the fish case) ➔ DC Barrel Jack (attached to the shark) ➔ Motor (inside the shark).

<img width="47%"  alt="image" src="https://github.com/user-attachments/assets/b36f2e67-87b6-4c85-a2c9-d9246a92f3c9" />
<img width="47%"  alt="image" src="https://github.com/user-attachments/assets/2a1e2ac7-d22e-43fa-b875-f65409c1ce66" />

[DC motor model](https://grabcad.com/library/n10-dc-gear-motor-1) from GrabCAD

[PWM module](https://grabcad.com/library/dc-motor-speed-controller-module-1) from GrabCAD

## 3D Model

[Onshape Link](https://cad.onshape.com/documents/12f6a6a5319b53d2241f5f02/w/c131fd40c8fe5ac2b45b1c31/e/70f820d1e6d7ceb5514721d9?renderMode=0&uiState=6a20b89b672360de2a9f7309) 

[Fan blade](https://makerworld.com/en/models/476320-parametric-fan-generator#profileId-387255) Customizable model by GCdesign3D on Makerworld  

### Fan Blade + Frame

<img width="30%" alt="image" alt="image" src="https://github.com/user-attachments/assets/d5f2f374-2179-4ba8-9174-0b44781656c2" />
<img width="30%" alt="image" alt="image" src="https://github.com/user-attachments/assets/c91f8cbf-8287-47c0-8f3a-dead211c4c7b" />

### Switch Case

<img width="55%" alt="image" src="https://github.com/user-attachments/assets/7862b700-4387-4fd0-a302-b4cc590d164a" />
<img width="30%" height="590" alt="image" src="https://github.com/user-attachments/assets/03955001-c781-44fd-89f6-0e77a93428c9" />

### Shark Body 

<img width="47%" height="650" alt="image" src="https://github.com/user-attachments/assets/82f84f66-d00e-4f74-853f-401c57fb432a" />
<img width="47%" height="623" alt="image" src="https://github.com/user-attachments/assets/eb0379ed-bacc-4b22-b4f7-590089c63586" />


## Schematic

<img width="40%" height="608" alt="image" src="https://github.com/user-attachments/assets/3fbd0106-d731-487f-9846-69e6e0cba6ee" />


## Bill of Materials 
| Item             |Qty	| Unit Cost	   | Total Cost     |  	Source | Specifications | Link                                 |      
| ---------------- |----:| -----------:| --------------:| --------- | --------------- | ------------------------------------- |
| DC Motor	    |  1	|   $6.54   |	$6.54	     |  Aliexpress |   2000 RPM, 6 V|	https://www.aliexpress.com/item/32922112793.html?aem_p4p_detail=202605231605042368122421526200001972299&algo_pvid=0304349a-a5f5-42ee-846c-efd0dbc5e216&algo_exp_id=0304349a-a5f5-42ee-846c-efd0dbc5e216-15&pdp_ext_f=%7B%22order%22%3A%22600%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%215.69%215.69%21%21%214.03%214.03%21%40210311cc17795775042187994ef3d9%2112000040725947354%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=0GPp5IUTwlv0&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A32922112793%7C_p_origin_prod%3A&search_p4p_id=202605231605042368122421526200001972299_4 |
|DC wall adapter	|1	|$5.41|	$5.41	|Aliexpress|	2A, 6V|	https://www.aliexpress.com/item/4000521124523.html?algo_pvid=8ec675cb-4fb0-487a-84e2-6988172f5d33&algo_exp_id=8ec675cb-4fb0-487a-84e2-6988172f5d33-1&pdp_ext_f=%7B%22order%22%3A%2232987%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%214.69%214.69%21%21%213.36%213.36%21%402101eede17784558975152603e7939%2110000002659372355%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=Kld5tkvMAzpz&utparam-|url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000521124523%7C_p_origin_prod%3A
|Sandpaper 240 grit	|10	|$0.73|	$7.30|	Aliexpress|	|	https://www.aliexpress.com/item/1005005467956102.html?algo_pvid=fd93dcd4-27d0-49db-bf6f-72c3326933b8&algo_exp_id=fd93dcd4-27d0-49db-bf6f-72c3326933b8-10&pdp_ext_f=%7B%22order%22%3A%221116%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%216.29%215.99%21%21%2130.60%2129.12%21%402101df0e17784562278173545ea01c%2112000033200195228%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=IOPu32ys4hBE&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005467956102%7C_p_origin_prod%3A
|PWM Module	|1|	$4.30	|$4	|Aliexpress	||	https://www.aliexpress.com/item/1005005402674691.html?algo_pvid=dde70e75-2c68-4929-b351-|d1095e0896c5&algo_exp_id=dde70e75-2c68-4929-b351-d1095e0896c5-1&pdp_ext_f=%7B%22order%22%3A%221551%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%213.79%213.79%21%21%2118.21%2118.21%21%40210319b717802456030692361ea4ea%2112000032916642878%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=oP7J9mSjJpyK&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005402674691%7C_p_origin_prod%3A|
|Hookup Wires	|1	|$3.95	|$3.95	|Aliexpress	|22 AWG, 5 m	|https://www.aliexpress.com/item/1005009575544132.html?algo_pvid=c53901c6-037c-436e-908e-6d48c3271276&algo_exp_id=c53901c6-037c-436e-908e-6d48c3271276-0&pdp_ext_f=%7B%22order%22%3A%22927%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%214.29%214.23%21%21%2121.10%2120.79%21%4021030a6217776437217395038eb80c%2112000051692118275%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=fxurFc8fh1eG&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009575544132%7C_p_origin_prod%3A|
|White Acrylic Primer	|1 |	$14.83|	$14.83	|Amazon|	|	www.aliexpress.com/item/1005006592430892.html?algo_pvid=4b889e82-b390-4fe6-ba71-f2010f13c926&algo_exp_id=4b889e82-b390-4fe6-ba71-f2010f13c926-1&pdp_ext_f={"order"%3A"5289"%2C"spu_best_type"%3A"price"%2C"eval"%3A"1"%2C"fromPage"%3A"search"}&pdp_npi=6%40dis!CAD!1.89!1.89!!!9.17!9.17!%402101eee917786429540717996e642e!12000037752358315!sea!CA!2965713149!X!1!0!n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=jyiZxEi0YQWN&utparam-url=scene%3Asearch|query_from%3A|x_object_id%3A1005006592430892|_p_origin_prod%3A
|White Acrylic Paint|	1|	$5.07	|$5.07|	Michaels	|238 Iridescent |White	https://www.michaels.com/product/liquitex-basics-4oz-acrylic-paint-10633502|
|Blue Acrylic Paint|	1|	$5.07|	$5.07|	Michaels|	680 Light Blue| Violet	https://www.michaels.com/product/liquitex-basics-4oz-acrylic-paint-10633502|
|Clear Acrylic Varnish|	1|	$8.58|	$8.58	|Aliexpress	|60 ml|	https://www.aliexpress.com/item/1005008715565883.html?algo_pvid=63dae878-a7cb-4717-bc7f-4dc0577beb25&algo_exp_id=63dae878-a7cb-4717-bc7f-4dc0577beb25-0&pdp_ext_f=%7B%22order%22%3A%224401%22%2C%22eval%22%3A%221%22%2C%22orig_sl_item_id%22%3A%221005008715565883%22%2C%22orig_item_id%22%3A%221005008376807054%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%2116.15%217.59%21%21%2178.63%2136.95%21%402101e2b417784569704136575e78b0%2112000046363952492%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=LMuMQunb1omq&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008715565883%7C_p_origin_prod%3A1005008376807054|
|DC Barrel Mount Socket	|10	|$0.55|	$5.52	|Aliexpress	||https://www.aliexpress.com/item/1005007870346260.html?aem_p4p_detail=202606050616588372022396252860001085761&algo_pvid=e8313a67-1cb2-409e-9bd6-d20b2dd9d53e&algo_exp_id=e8313a67-1cb2-409e-9bd6-d20b2dd9d53e-3&pdp_ext_f=%7B%22order%22%3A%222335%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%214.84%214.62%21%21%2123.08%2122.01%21%402101e2b017806654188073441eb1a5%2112000042627202254%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895%3BpisId%3A5000000208177917&curPageLogUid=YIRMjd4zxDyd&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007870346260%7C_p_origin_prod%3A&search_p4p_id=202606050616588372022396252860001085761_1|
|Magnets 2mmx1mm 	|20	|$0.23	|$4.62|	Aliexpress |	|	https://www.aliexpress.com/item/1005010533387425.html?algo_pvid=830f2e54-dd4b-4747-86c8-1fe8ca02757a&algo_exp_id=830f2e54-dd4b-4747-86c8-1fe8ca02757a-0&pdp_ext_f=%7B%22order%22%3A%221180%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%214.09%214.09%21%21%212.90%212.90%21%40210328df17796425679376312efbfa%2112000052731204227%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=UWybOulYMtBq&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010533387425%7C_p_origin_prod%3A|
|M3 Screws|	50|	$0.06	|$3.21|	Aliexpress|	5 mm |	https://www.aliexpress.com/item/1005007264845313.html?algo_pvid=e1135bfd-e73d-409e-99a2-8ed8a6979ad7&algo_exp_id=e1135bfd-e73d-409e-99a2-8ed8a6979ad7-6&pdp_ext_f=%7B%22order%22%3A%2219533%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%212.23%212.05%21%21%211.58%211.45%21%402101f11417798128120284999e484d%2112000039998989023%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895%3BpisId%3A5000000207667627&curPageLogUid=DTKzFokrFoUM&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007264845313%7C_p_origin_prod%3A|
|M3 x0.5 Threaded Inserts|	20|	$0.21	|$4.11	|Aliexpress	|3D|	https://www.aliexpress.com/item/1005004392648088.html?algo_pvid=9b1fb00f-a98a-4229-8a1a-644744d413fe&algo_exp_id=9b1fb00f-a98a-4229-8a1a-644744d413fe-0&pdp_ext_f=%7B%22order%22%3A%221366%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%213.79%213.49%21%21%212.68%212.47%21%40210318a717798130674428844ed817%2112000029019005597%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895%3BpisId%3A5000000207667627&curPageLogUid=T1XzJrrOGBMV&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004392648088%7C_p_origin_prod%3A|
|3mm Flange hub|	1|	$3.47	|$3.47	|Aliexpress ||		https://www.aliexpress.com/item/1005007347931821.html?algo_pvid=9ba92fc5-a3e9-41a1-b17b-8a5aaa4b350f&algo_exp_id=9ba92fc5-a3e9-41a1-b17b-8a5aaa4b350f-0&pdp_ext_f=%7B%22order%22%3A%221362%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%212.93%212.93%21%21%2114.05%2114.05%21%40210328c017802418945061519e2846%2112000040365140677%21sea%21CA%212965713149%21X%211%210%21n_tag%3A-29919%3Bd%3Afa6b15bf%3Bm03_new_user%3A-29895&curPageLogUid=pfHEVmjmXpCv&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007347931821%7C_p_origin_prod%3A|
|Total (CAD) | | | $81.98 ||| | 
| Total (USD)| | | $59.00 | | |
