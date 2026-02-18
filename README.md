<a href="https://gagik.co"><center><img src="https://gagik.co/radio.gif" width="300px" /></center></a>
```ts
type Url = `https://${string}.${string}`;
const MongoDB: Url = "https://github.com/gagik?org=mongodb-js";
const developerTools: string = ["mongosh", "MongoDB MCP server", "VSCode extension", "Compass"].join(", ");
const tetrify: Url = "https://tetrify.com/"

console.log(`
I work on ${developerTools} at ${MongoDB}.
I'm also building ${tetrify}, a texting-based productivity & automation system.
`)
```
