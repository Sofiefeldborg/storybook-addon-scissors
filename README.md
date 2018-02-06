# Storybook Addon Scissors
![alt text](https://raw.githubusercontent.com/PeterPanen/storybook-addon-scissors/master/assets/screenshot.png "plugin screenshot")

> Requires storybook version 3+

### Install

```javascript
npm i -D storybook-addon-scissors
```

### Usage
- Download and import device list from [viewportsizes.com/devices.json](http://viewportsizes.com/devices.json)
- Create or open `.storybook/addons.js` and register the addon like below.
```javascript
// addons.js
import '@storybook/addon-actions/register';
import registerScissors from 'storybook-addon-scissors';
import devices from './devices.json';

registerScissors(devices);
```
