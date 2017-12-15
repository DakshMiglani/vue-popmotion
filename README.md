# vue-popmotion
A small wrapper for integrating popmotion to Vuejs

## How to install:
### CommonJS:
```
npm install --save lodash vue-popmotion
```

And in your entry file:
```
import Vue from 'vue'
import popmotion from 'popmotion'
import VuePopmotion from 'vue-popmotion'

Vue.use(VuePomotion, popmotion)
```

### Script:
Just add 3 scripts in order: `vue`, `popmotion` and `vue-popmotion` to your `document`.

## Usage:
This wrapper bind `popmotion` to `Vue` or `this` if you're using single file component.

You can `popmotion` like this:
```
Vue.popmotion

Vue.pm

this.popmotion

this.pm
```