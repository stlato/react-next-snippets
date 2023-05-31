# VS Code react-next-snippets

React/Next.js snippets App Router Ready

Installation
[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=stlato.react-next-snippets)

## Supported languages (file extensions)

- TypeScript(.ts)
- TypeScript React(.tsx)

## Usage

1. Type `cfc` in .tsx(or .ts) File
2. VS Code will suggest "clientFunctionComponent"
3. Hit enter

Then, VS Code generate boilerplate code of your component like this:

```tsx
"use client";

type Props = {};

export const FileName = (props: Props) => {
  return <div></div>;
};
```

## Snippets

|  Trigger | Content                                  |
| -------: | ---------------------------------------- |
|    `fc→` | function component                       |
|  `fcfr→` | function component forwarded ref         |
|   `cfc→` | client function component                |
| `cfcfr→` | client function component forwarded ref  |
|   `efc→` | emotion function component               |
| `efcfr→` | emotion function component forwarded ref |
# react-next-snippets
