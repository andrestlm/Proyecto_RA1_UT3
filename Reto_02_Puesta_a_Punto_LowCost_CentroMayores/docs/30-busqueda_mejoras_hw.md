# 30 — Búsqueda y selección de mejoras de **hardware**

> **Objetivo:** Encontrar las **mejoras mínimas** que conviertan cada PC en **usable** para el centro de mayores, **respetando** S0/S1/S2.
## 1) Piezas candidatas (con enlaces y capturas)

Busca en **tiendas online españolas** (PcComponentes, Amazon ES, Coolmod, Wallapop/segunda mano con precaución) y documenta **al menos 2 opciones por categoría** (cuando aplique):

- **Almacenamiento:** SanDisk SSD 64 GB SATA III / Crucial M4 SSD 64 GB SATA III
- **Memoria RAM:** RAM DDR2 Corsair 4GB / RAM Samsung 4GB DDR3
- **Mantenimiento:** Pasta Térmica Noctua NT-H1 / Ewent Spray de Aire Comprimido 400Ml
- **Otros (si procede):** Adaptador Wifi USB Alfa Network / Altavoces PC

**Tabla almacenamiento:**

| Categoría      | Marca/Modelo            | Capacidad | Precio (€) | Tienda | URL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Captura                                                    |
| :------------- | :---------------------- | --------: | :--------- | :----- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------- |
| Almacenamiento | SanDisk SSD SATA III    |     64 GB | 12,90      | Ebay   | [📎](https://www.ebay.es/itm/304411174497?chn=ps&google_free_listing_action=view_item)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | ![Almacenamiento](../assets/img/30-hw/almacenamiento2.png) |
| Almacenamiento | Crucial M4 SSD SATA III |     64 GB | 12,90      | Ebay   | [📎](https://www.ebay.es/itm/294882327326?_trksid=p2332490.c101196.m2219&itmprp=cksum%3A2948823273266d6ea50e22fd49ca81a514f4d9608405%7Cenc%3AAQALAAABQG%252F4sd0snwJnv81fl8FcciOVkJJKsapzWEBwEzP3T1mKZ9WiaeV2kZNRn45y7sSRHRHm9bWdgirAyBMYxj3wGlazCHsgk9BKHYxXgbiMoQSXnD45RzGhdBj13I7S1l2VUNETe5pSZw1LT7YA1LEwgKmgmp8tAtZp2bKqRahbldvPHjh2MRotHxwDkvb0oMm3UvO7TUKYj2P8LyIJm9DR2EJZAEj7nO0ApF0KvHLToFZuxFMLm3j7wJwMZnB%252BHtFUnL7f%252BFCVbVeTgkoNU5QN3Au3k%252FO10OSjozfaCgASQTD3p6mfAQFSs6uVLj2vG3yIzEzPM3b2AmTZWy4SHLH9zCUDiiwGSAc0OFNm7a5fmdhIkAd8VuezZM8EcUmugMGr9y5sKOPrwN9FqXeaNCXw%252BeJOsQF5gD9BF%252Bk6KZCZKQpx%7Campid%3APL_CLK%7Cclp%3A2332490&itmmeta=01KGYVV7HF582YDW403CZX5GQW) | ![Almacenamiento](../assets/img/30-hw/almacenamiento.png)  |

Tabla RAM:

| Categoría   | Marca/Modelo | Capacidad | Precio (€) | Tienda      | URL                                                                                       | Captura                              |
| :---------- | :----------- | --------: | :--------- | :---------- | :---------------------------------------------------------------------------------------- | :----------------------------------- |
| Memoria RAM | Corsair DDR2 |      4 GB | 5          | MilAnuncios | [📎](https://www.milanuncios.com/memorias-ram/memoria-ram-ddr2-corsair-4gb-531642609.htm) | ![RAM](../assets/img/30-hw/ram.png)  |
| Memoria RAM | Samsung DDR3 |      4 GB | 6          | Walapop     | [📎](https://es.wallapop.com/item/memoria-ram-samsung-4gb-ddr3-1228609279)                | ![RAM](../assets/img/30-hw/ram2.png) |

Tabla mantenimiento:

| Categoría     | Marca/Modelo                      | Precio (€) | Tienda        | URL                                                                           | Captura                                         |
| :------------ | :-------------------------------- | :--------- | :------------ | :---------------------------------------------------------------------------- | :---------------------------------------------- |
| Mantenimiento | Pasta Térmica Noctua NT-H1        | 2          | Walapop       | [📎](https://es.wallapop.com/item/pasta-termica-noctua-nt-h1-3-5g-1221315136) | ![Mantenimiento](../assets/img/30-hw/pasta.png) |
| Mantenimiento | Ewent Spray Aire Comprimido 400ml | 3,48       | PCcomponentes | [📎](https://www.pccomponentes.com/ewent-spray-de-aire-comprimido-400ml)      | ![Mantenimiento](../assets/img/30-hw/aire.png)  |

Tablas otros:

| Categoría | Marca/Modelo                    | Precio (€) | Tienda  | URL                                                                           | Captura                                     |
| :-------- | :------------------------------ | :--------- | :------ | :---------------------------------------------------------------------------- | :------------------------------------------ |
| Otros     | Adaptador Wifi USB Alfa Network | 3          | Walapop | [📎](https://es.wallapop.com/item/adaptador-wifi-usb-alfa-network-1228031796) | ![Otros](../assets/img/30-hw/wifi.png)      |
| Otros     | Altavoces PC                    | 2          | Walapop | [📎](https://es.wallapop.com/item/altavoces-pc-1228461804)                    | ![Otros](../assets/img/30-hw/altavoces.png) |

## 2) Compatibilidad técnica (justifica con datos)

Para **cada pieza** elegida, justifica la **compatibilidad** con tu lote:

- **RAM:** La placa base cuenta con 4 slots y en la mayoria de PCs de la flota solo se usa 1 ranura, entoces hay que encontrar otra opción de slot de RAM que sea compatible con la placa como ya puede ser de ddr2 o ddr3. El de ddr2 nos permite usar el dual channel de la RAM, y por eso es una buena opcion aunque sean solo 4GB en total.
- **SSD:** Aunque la mayoria de PCs tienen HDD, las caracterícese de la placa permiten usar SSD y por ello una opcion barata de SSD sata que no tenga mucha capacidad pero si un bajo precio es una opcion considerable para el bajo presupuesto.
- **Otros:** Para el mantenimiento hay que cambiar la pasta térmica, que no suele ser muy barata. Tambien es conveniente limpiar el polvo con aire comprimido, y una lata pequeña sirve para un PC entero. Aunque si se tuviera una pistola de aire seria mejor. Por ultimo, algunos PCs no tienen conexión por wifi o no tienen antena, entoces un adaptador simple hace su función, aunque no con la mayor velocidad. Al ser ordenadores de sobremesa, probablemente su monitor no tengan altavoces, por ello hay que mirar algunos en cas de no querer usar audífonos.

#### SSD
![Datos SSD](../assets/img/30-hw/datos1.png)

#### RAM
![Datos RAM](../assets/img/30-hw/datos2.png)

#### WiFi
![Datos WiFi](../assets/img/30-hw/datos3.png)

## 3) Mini‑estimación de impacto (sentido común + referencias)

En 3–5 líneas por categoría, explica el **impacto esperado**:

- **De HDD a SSD:** Es una actualización bastante importante, ya que permite que el SO arranque más rapido, pueda acceder mas rapido a los archivos y teniendo menos tirones en el explorador de archivos o al abrir ciertos programas. Haciendo que la fluidez del ordeandor aumente.
- **De 4 GB a 8 GB RAM:** Permite poder cargar las cosas más rapido con la ayuda del SSD que se le ha instalado. Da la posibilidad de hacer multitarea y tener varios programas abiertos a la vez, aunque no sea demasiado. Así tarda menos tiempo en cambiar entre ventanas o entre pestañas del navegador, ya que no tienen que cargar otra vez y se puede guardar en la RAM.
- **Pasta térmica/limpieza:** La pasta térmica permite que el ordenador pueda calentarse más ya que disipa más el calor generado, haciendo que le CPU no sufra de termal throttling y pueda tener un poco más de potencia. La limpieza por otro lado, permite que el ordenador este más limpio y los ventiladores no tengan suciedad que pueda atascarlos, generando menos ruido y más eficiencia en estos.

## 4) Escenario elegido y desglose de gasto (S0/S1/S2)

Completa la tabla con tu **propuesta final** y calcula el **gasto HW** total (sin mano de obra):

| **Escenario** | **Pieza**                  | **Precio Unit. (€)** | **Unidades** | **Total (€)** | **Nota**                        |
| ------------- | -------------------------- | -------------------- | ------------ | ------------- | ------------------------------- |
| S2            | SanDisk SSD SATA III 64 GB | 12,90                | 20           | 258,00        | Más rapido que el HDD.          |
| S2            | RAM Samsung DDR3 4GB       | 6,00                 | 20           | 120,00        | Permite multitarea.             |
| S2            | Pasta Térmica Noctua NT-H1 | 2,00                 | 5            | 20,00         | Necesario para que rinda mejor. |
| S2            | Adaptador Wifi USB Alfa    | 3,00                 | 20           | 60,00         | Conectividad inalambrica.       |
| **TOTAL**     |                            | **23,90 €**          | 80 piezas    | **478,00 €**  | **Cumple S2 (≤ 30€)**           |
Luego traslada el **Total HW** a `75-plan_presupuesto_hw_y_roi.md` para calcular costes y ROI.
