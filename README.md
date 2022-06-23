# svelte-babel-simple
A simple repo intended to demonstrate import failure with `proskomma-tools`

## Contents
- svelte skeleton project
- imported `proskomma-tools` npm package

index.svelte:
```svelte
<script>
    import {queries} from 'proskomma-tools';

</script>

<pre>test successful</pre>
```

error message:
```
exports is not defined in ES module scope
This file is being treated as an ES module because it has a '.js' file extension and 'svelte-babel-simple\node_modules\proskomma-tools\package.json' contains "type": "module". To treat it as a CommonJS script, rename it to use the '.cjs' file extension.
```