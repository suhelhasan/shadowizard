# What is this?

Get perfect shadows every time for the non-designer.

#Installation

`npm i shadowizardtesting --save`

Then...

```
import {shadowizardtest} from 'shadowizardtest';

shadowizardtest({
    shadow_type:'soft';
    padding:false
});
```
## Options

Shadowizardtest supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (defaults to soft)
* *padding* - _boolean_ (defaults to false)
