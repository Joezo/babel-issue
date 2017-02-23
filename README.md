# babel-issue

Clone then
`npm i && npm test`

You should see this error:
```
SyntaxError: /Users/joewarren/repos/babylon-issue/exportDefaultAsync.js: await is a reserved word (1:27)
> 1 | export default async () => await Promise.resolve(() => console.log('foo'))
    |                            ^
  2 |
  3 |
    at Parser.pp$5.raise (/Users/joewarren/repos/babylon-issue/node_modules/babylon/lib/index.js:4380:13)
```
