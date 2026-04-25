# Neutrino preset React require.

Auto import React when JSX is detected.

## Installation

Grab the preset:

```
$ yarn add -D neutrino_preset_react_require
```

Add it to your package.json:

```json
{
  "neutrino": {
    "use": [
      "neutrino_preset_react",
      "neutrino_preset_react_require"
    ]
  }
}
```

## Example

Instead of:

```js
import React from 'react'

export default function Spinner({ size = 'small' }) {
  return <div className={`Spinner size-${size}`}></div>
}
```

Just write:

```js
export default function Spinner({ size = 'small' }) {
  return <div className={`Spinner size-${size}`}></div>
}
```









