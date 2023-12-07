# Hardware: Squish Ball Controller 🎮
The [*Squish Ball*]() controller has a big, colorful personality. It farts on players when they lose the game and throws a tantrum by shaking – bored due to game time limits. But *Squish Ball* lights with joy when flying around the game and collecting gems. Most of all, it loves to increase video game accessibility to children unable to swipe on a screen or hit buttons. *Squish Ball* functions as a game controller designed to be used in conjunction with the rhythm game, [*Travel the Stars*](). 

*Travel the Stars* (game) and *Squish Ball* (controller) cooperate to integrate a personable toy, children’s fart jokes, and a video game designed for children between the **ages of 2 to 5 years**. 
In *Travel the Stars*, players are invited to fly through outer space to experience the game’s message – to reach for the stars while also enjoying the rocketship ride. 

When we hop onto the rocketship, we are excited and want to keep winning and moving to our destination. *Travel the Stars* shows the value of stopping by the planets to explore and pausing the game to experience the physical world. Can we find meaning in our life adventures? How can we as individuals find and bring positivity and inspiration to the world around us?

*Squish Ball* reinvents the controller experience for children through smell, touch, and other haptic feedback. Children may play *Travel the Stars* without the need for buttons and touch screens by squishing (`squish`), hugging (`hug`), moving (`move`), bouncing (`bounce`), and poking (`poke`). *Squish Ball* adds to the gameplay experience by expressing themselves as an active participant in bringing fun, joy, and jokes. This game controller experience captures children’s imaginations and emotions through playing pretend with the controller and navigating through the gameplay. 

https://github.com/debbieyuen/figma-plugin-renaming-layers/assets/31296177/41a4e166-0164-477c-a638-39d9c651f469

## Requirements
* **Software:**
  * [Unity 2018+](https://www.figma.com/downloads/)
  * [Arduino IDE 2.2.1](https://www.arduino.cc/en/software)
  * [Arduino AVR Boards Package](https://docs.arduino.cc/software/ide-v1/tutorials/getting-started/cores/arduino-avr)
  * [Adafruit Circuit Playground Library](https://github.com/adafruit/Adafruit_CircuitPlayground)
  * [I2C Device Library](https://github.com/jrowberg/i2cdevlib)
  * [Ardity](https://github.com/dwilches/Ardity)
  * [React App to GitHub Pages](https://github.com/gitname/react-gh-pages)

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

Create a React app
```bash
$ npx create-react-app my-app
```

Install React dependencies with `npm`.
```bash
$ npm install
$ npm install react-unity-webgl@8.x
$ npm install gh-pages -save-dev
```

Deploy React App to http://localhost:3000/
```bash
$ npm start
```

In your **package.json**, add a `homepage` property in this format\*: `https://{username}.github.io/{repo-name}`
```diff
 {
   "name": "my-app",
   "version": "0.1.0",
+  "homepage": "https://gitname.github.io/react-gh-pages",
   "private": true,
```

In your **package.json**, add a `predeploy` property and a `deploy` property to the `scripts` object:
```diff
"scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
```

Deploy GitHub Pages
```bash
$ npm run deploy
```

## Credits and References
* [Marc Teyssier: Uduino](https://marcteyssier.com/uduino/tutorials)
* [Figma Plugin React](https://github.com/nirsky/figma-plugin-react-template)
