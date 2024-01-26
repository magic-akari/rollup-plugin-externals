# rollup-plugin-externals

This is a Rollup plugin that provides functionality similar to webpack's externals.

## Installation

```bash
pnpm i -D rollup-plugin-externals
```

## Configuration

```JavaScript
import { defineConfig } from "rollup";
import { external } from "rollup-plugin-externals";

export default defineConfig({
    plugins:[
        external({
            "react": "React",
            "react-dom": "ReactDOM",
        })
    ]
});
```
