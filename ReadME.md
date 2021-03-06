# vue-minrich-editor
A minimalistic text editor inspired by Medium.com and Telegra.ph.
- Mobile support
- Image drag'n'drop and paste support  
- Automatic YouTube and Vimeo embedding

![Screenshot](https://i.imgur.com/xGxmdO7.jpg)
[DEMO](https://lover-drive.github.io/vue-minrich-editor/) 

## Installation
#### NPM
````
npm i vue-minrich-editor --save-dev
````
#### CommonJS
````
var VueRichEditor = require('vue-rich-editor');
  
new Vue({
  components: {
    'vue-rich-editor': VueRichEditor
  }
})
````

#### ES6
````
import Vue from 'vue'
import VueRichEditor from 'vue-rich-editor'
  
Vue.use(VueRichEditor)

new Vue({
  components: {
    VueRichEditor
  }
})
````
## Props
**placeholder**: String - a placeholder for your text editor.

## License
[MIT](https://opensource.org/licenses/MIT)
