# About VOC Tag

![](../.gitbook/assets/_basics_module-overview_voc-tag.png)

The **VOC Tag** is a gas sensor for measuring **volatile organic compounds \(VOC\) concentration**. This is useful for indoor air quality monitoring applications. This module uses a metal-oxide multi pixel sensor SGP30 from Sensirion measuring total VOC level.

| \*\*\*\*[**E-shop**](https://shop.bigclown.com/voc-tag)\*\*\*\* | [**Schematic Drawing**](https://github.com/bigclownlabs/bc-hardware/tree/master/out/bc-tag-voc) | [**SDK Library**](https://sdk.bigclown.com/group__bc__sgp30) | [**Header File**](https://github.com/bigclownlabs/bcf-sdk/blob/master/bcl/inc/bc_sgp30.h) | [**Source File**](https://github.com/bigclownlabs/bcf-sdk/blob/master/bcl/src/bc_sgp30.c) |
| :---: | :---: | :---: | :---: | :---: |


VOC \(Volatile Organic Compounds\) sensor is a great technology for indoor air quality measurement applications. Elevated VOC levels can have a negative impact on well being, comfort, and cognitive abilities. Typacal VOC sources are cosmetics, detergents containing alcohols or aldehydes, carpets and flooring, paints, human and animal occupants. Measuring Total VOC \(TVOC\) level can helps to increase the efficiency of ventilation and air purification, and increases awareness of VOC sources and indoor air pollution.

| Level | TVOC \(ppb\) | Hygienic Rating | Recommendation | Exposure Limit |
| :--- | :--- | :--- | :--- | :--- |
| 5 - Unhealty | 2200 - 5500 | Situation not acceptable | Use only if unavoidable / Intense ventilation necessary | hours |
| 4 - Poor | 660 - 2200 | Major objections | Intensified ventilation / airing necessary, search for sources | &lt; 1 month |
| 3 - Moderate | 220 - 660 | Some objections | Intensified ventilation / airing recommended, search for sources | &lt; 12 months |
| 4 - Good | 65 - 220 | No relevant objections | Ventilation / airing recommended | no limit |
| 5 - Excellent | 0 - 65 | No objections | Target value | no limit |

### Features <a id="features"></a>

* VOC multi pixel gas sensor SGP30 \(Sensirion\)
* Suitable for indoor air quality monitoring applications
* Measurement range of TVOC: 0 to 60 000 ppb \(part per billion\)
* Typical Measurement accuracy of ethanol signals: 15 % of reading
* Typical Measurement accuracy of H₂ signals: 10 % of reading
* Communication using I²C digital bus interface
* Operating current: 48 mA \(power supply using DC adapter is recommended\)
* Operating voltage range: 1.9 V to 6.5 V \(LDO equipped module\)
* Operating temperature range: -45 to 85 °C
* Mechanical dimensions: 16 x 16 mm

### Resources <a id="resources"></a>

* [**Documentation**](about-voc-tag.md)
* [**Schematic drawing**](https://github.com/bigclownlabs/bc-hardware/tree/master/out/bc-tag-voc)
* [**Datasheet**](https://cdn.sos.sk/productdata/1c/f1/b765fb6a/sgp30.pdf)

### Firmware Projects <a id="firmware-projects"></a>

* [**Radio VOC sensor**](https://github.com/bigclownlabs/bcf-radio-voc-sensor)

