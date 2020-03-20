# What is this?

Get perfect shadows every time for the non-designer.

# [NPM PACKAGE](https://www.npmjs.com/package/shadowizardtesting)

#Installation

`npm i shadowizardtesting --save`

Then...
In your JS file include this code 

```
import {shadowizardtest} from 'shadowizardtesting';

shadowizardtest({
    shadow_type:'soft';
    padding:false
});
```

Then....

Add add css class `shadowizard` to html:

`<img src="" class="shadowizard" >`


## Options

Shadowizardtest supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (defaults to soft)
* *padding* - _boolean_ (defaults to false)
