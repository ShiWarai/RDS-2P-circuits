# RDS-2P Circuits

Электрические схемы для робота [RDS-2P](https://github.com/ShiWarai/RDS-2P), разработанные для лабораторного или домашнего химического травления с использованием бытовой химии.


<table>
<tr>
<td align="center" valign="middle"><img src="https://github.com/user-attachments/assets/cc7b5c0c-264d-45e4-b962-a0f591341660" width="360" alt="Платы RDS-2P, общий вид"/></td>
<td align="center" valign="middle"><img src="https://github.com/user-attachments/assets/e447e853-4c74-4822-a034-ce947024281d" width="200" alt="Платы RDS-2P, вертикальный кадр"/></td>
</tr>
</table>

## Описание плат

- **Плата питания для RDS-2P** устанавливается в заднем отсеке робота и **питает** узлы робота.
- **Плата коммутации двигателей для RDS-2P** выполняет распределительную (силовую коммутационную) функцию и **сокращает количество** проводов.

## Компоненты

Ниже — посадочные места с PCB (разъёмы и клеммники) и типовые модули питания для сборки. Дополнительные детали — в `rds-2p-electrics.json`.

Превью в колонке «Изображение» — заглушки в `assets/bom/*.svg`; при желании замените их на фотографии деталей (или поменяйте ссылки на свои файлы).

### Плата питания для RDS-2P

| Имя | Кол-во | Изображение | Примечание |
|-----|--------|-------------|------------|
| Amass XT30UPB-M (вилка, силовой разъём) | 6 | <img src="assets/bom/xt30.svg" width="72" height="72" alt="XT30" /> | U1–U6, корпус `CONN-TH_XT30UPB-M`; LCSC — по каталогу в EasyEDA |
| XINLAIYA XY301V-A-5.0-2P (клеммник 2P, шаг 5,0 mm) | 3 | <img src="assets/bom/xy301.svg" width="72" height="72" alt="XY301" /> | U7–U9, LCSC C557651 |
| BMS 2S 20A, защита Li-ion с балансировкой | 1 | <img src="assets/bom/bms2s.svg" width="72" height="72" alt="BMS 2S" /> | Не на PCB; <a href="https://www.ozon.ru/product/bms-2s-20a-plata-zashchity-s-balansirovkoy-1sht-kontroller-zaryada-li-ion-batarey-s-balansirovkoy-1929224672/">Ozon</a> |
| DC-DC понижающий LM2596S, 8–40 V → 5 V | 2 | <img src="assets/bom/lm2596.svg" width="72" height="72" alt="LM2596" /> | Не на PCB; комплект 2 шт.; <a href="https://www.ozon.ru/product/ponizhayushchiy-preobrazovatel-dc-dc-8-40v-na-5v-lm2596s-stabilizator-5v-2sht-2024449951/">Ozon</a> |

### Плата коммутации двигателей для RDS-2P

| Имя | Кол-во | Изображение | Примечание |
|-----|--------|-------------|------------|
| BOOMELE 5264-3AW (клеммник / вывод, 3 контакта) | 4 | <img src="assets/bom/5264-3aw.svg" width="72" height="72" alt="5264-3AW" /> | U10–U13, LCSC C48374 |
| Amass XT30UPB-M (вилка, силовой разъём) | 1 | <img src="assets/bom/xt30.svg" width="72" height="72" alt="XT30" /> | U4, корпус `CONN-TH_XT30UPB-M` |
| XINLAIYA XY301V-A-5.0-2P (клеммник 2P, шаг 5,0 mm) | 1 | <img src="assets/bom/xy301.svg" width="72" height="72" alt="XY301" /> | U7, LCSC C557651 |
