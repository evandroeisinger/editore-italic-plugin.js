# editore.js italic plugin [![npm version](https://badge.fury.io/js/editore-italic-plugin.svg)](http://badge.fury.io/js/editore-link-plugin)

#### install
Available on npm: `npm install editore-italic-plugin` or [directly download](https://github.com/evandroeisinger/editore-italic-plugin.js/raw/master/src/editore-italic-plugin.js)

#### basic usage
It's easy to use! Load [editore.js](https://github.com/evandroeisinger/editore.js) into your application, instantiate it and register the new **edition** plugin.

```javascript
var editore = new Editore(document.getElementById('editor')),
    ItalicPlugin;

// Global
ItalicPlugin = window.EditoreItalicPlugin;
// CommonJS
ItalicPlugin = require('editore-italic-plugin');

// then register!
editore.registerEditionComponent(ItalicPlugin);
```
---
#### support
- chrome: ?
- firefox: ?
- safari: ?
- internet explore: ?


---
#### contribute
Everyone can contribute! Finding bugs, creating issues, improving editor it self or creating components.
Every contribution will be welcomed! :santa: 

**Fork it** -> **Branch it** -> **Test it** -> **Push it** -> **Pull Request it** :gem:  
