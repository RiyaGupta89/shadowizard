# This is a custom npm package

## What does it do?

Well, get perfect shadows every time for the non-designer.

# Installation

`npm i shadowizard --save`

Then ...

```
import {shadowizard} from "shadowizard";

shadowizard({
    shadow_type :"soft",
    padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Default to soft)
* *padding* - _boolean_ (Default to false)