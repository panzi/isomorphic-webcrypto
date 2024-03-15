# isomorphic-webcrypto

Expose the WebCrypto object in browser and NodeJS including types.

All this does is:

```JavaScript
exports.default = crypto;
```

Plus giving it types via:

```TypeScript
import { webcrypto } from 'node:crypto';
export default webcrypto;
```

This way you can use the WebCrypto API the same way in a browser or a NodeJS
based project.
