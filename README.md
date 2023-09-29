# Custom Cards

This Repository gives sample code to make custom cards for HomeAssistant. You will be requiring Custom: Button Card, Mini-Graph Card, my-slider-v2, apex-charts, stack-in-card and Card-mod to be pre-installed to make it work. 

[Card-Mod](https://github.com/thomasloven/lovelace-card-mod)

[Custom:Button-Card](https://github.com/custom-cards/button-card)

[Mini-Graph Card](https://github.com/kalkih/mini-graph-card)

[My-Slider-v2](https://github.com/AnthonMS/my-cards)

[Stack-in-Card](https://github.com/custom-cards/stack-in-card)

[ApexCharts](https://github.com/RomRider/apexcharts-card#main-show-options)

### Custom Icons

* Google Material Icons.
* Some from Flaticons.

#### Install
* Copy the custom_icon.js files to your configuration/www/ folder.
* Under Home Assistant go to setting Dashboards > click three dots on top-right and click on Resources.
* Click Add resource.
* Under url enter: /local/js_file_name.js
* Select JavaScript module and create.
* Then restart Home Assistant

Or to do this manually using YAML, dd following code to lovelace section
```yaml
  resources:
    - url: /local/custom_icon.js
      type: module
  ```

### Person Card

* Information on Person mobile battery and storage
* Indication for Away from Home Zone and network connection at top right corner.

![Person Card](/assets/person_card.jpeg)

### Room Card

* Sensor info under Room name.
* Indication for Active device at top right corner.

![Room Cards](/assets/room_card.jpeg)

### Light Card

* Card Color change on light state change.
* Slider for changing brightness(default). Can be changed to use for temperature, color. 

![Light Card](/assets/light_card.jpeg)

### Media Player Card

* Minimal view card

![Media Player Card](/assets/media_card.png)

### Switch Card

* Shows state info.
* Toggle button to indicate on/off state.

![Switch-Card](/assets/switch_card.jpeg)

### Device Card

* Show device status battery, storagea other sensors.
* Indication and info  of connection type and battery status.

![Device Card](/assets/device_card.jpeg)

### Usage Card

* Weekly graph of usage

![Usage Card](/assets/usage_card.jpeg)

### Utilization Card

* Shows utilization of resources with progress bar.

![Utilization Card](/assets/utilization_card.jpeg)

### Storage Card

* Show Storage with prgress bar.

![Storage Card](/assets/storage_card.jpeg)

### Information Card

#### Style 1

* Shows sensor state information with graph.

![Style 1](/assets/information_card_style_1.jpeg)

#### Style 2

* Shows sensor state information.

![Style 2](/assets/information_card_style_2.jpeg)

#### Style 3

* Shows sensor state information.

![Style 3](/assets/information_card_style_3.jpeg)
