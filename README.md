# Hardware: Squish Ball Controller 🎮
A Figma plugin that simplifies renaming layers and components by streamlining your refactoring process. While designing in Figma, clean up your layers by renaming duplicates and variations of a component within the same layer all at once! For example, rename all `buttons` within a parent component in one go while excluding nodes of different types such as `text`, `spacers`, and `images`. 

https://github.com/debbieyuen/figma-plugin-renaming-layers/assets/31296177/41a4e166-0164-477c-a638-39d9c651f469

## Requirements
* **Software:**
  * [Unity 2018+](https://www.figma.com/downloads/)
  * [Arduino IDE 2.2.1](https://www.arduino.cc/en/software)
  * [Arduino AVR Boards Package](https://docs.arduino.cc/software/ide-v1/tutorials/getting-started/cores/arduino-avr)
  * [Adafruit Circuit Playground Library](https://github.com/adafruit/Adafruit_CircuitPlayground)
  * [I2C Device Library](https://github.com/jrowberg/i2cdevlib)
  * [Ardity](https://github.com/dwilches/Ardity)

* **Hardware:**
  * [Arduino UNO R3](https://store.arduino.cc/products/arduino-uno-rev3)
  * [L298N Motor Driver](https://www.amazon.com/Controller-H-Bridge-Stepper-Mega2560-Duemilanove/dp/B01CC8XI60/ref=asc_df_B01CC8XI60/?tag=hyprod-20&linkCode=df0&hvadid=194019628201&hvpos=&hvnetw=g&hvrand=14605263582876560199&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9030933&hvtargid=pla-393630496463&psc=1&mcid=62ba8665c9c13d1c98faff44092a5130&gclid=CjwKCAiA1MCrBhAoEiwAC2d64arqv3HuWUA3K6FWShvaC3py3jIzQ8bQxCCfcPNEbaEdLYKcg-EsERoC1ZgQAvD_BwE)
  * [Air Pump](https://www.adafruit.com/product/4699)
  * [Circuit Playground Classic](https://www.adafruit.com/product/3000)
  * [+12V Power Supply]()
  * [Muca: Multi Touch Boards](https://github.com/muca-board/Muca)

## Set Up

Clone the repository
```bash
$ git clone https://github.com/debbieyuen/squishball
```

Install dependencies with `npm`.
```bash
$ npm install --save-dev @figma/plugin-typings
$ npm install figma-plugin-ds 
```

## Credits and References
* [Marc Teyssier: Uduino](https://marcteyssier.com/uduino/tutorials)
* [Figma Plugin React](https://github.com/nirsky/figma-plugin-react-template)
