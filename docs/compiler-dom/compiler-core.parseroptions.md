<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) < [@vue/compiler-core](./compiler-core.md) < [ParserOptions](./compiler-core.parseroptions.md)

## ParserOptions interface

<b>Signature:</b>

```typescript
export interface ParserOptions 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [decodeEntities](./compiler-core.parseroptions.decodeentities.md) | (rawText: string, asAttr: boolean) =< string | Only needed for DOM compilers |
|  [delimiters](./compiler-core.parseroptions.delimiters.md) | \[string, string\] |   |
|  [getNamespace](./compiler-core.parseroptions.getnamespace.md) | (tag: string, parent: [ElementNode](./compiler-core.elementnode.md) \| undefined) =< [Namespace](./compiler-core.namespace.md) | Get tag namespace |
|  [getTextMode](./compiler-core.parseroptions.gettextmode.md) | (node: [ElementNode](./compiler-core.elementnode.md)<!-- -->, parent: [ElementNode](./compiler-core.elementnode.md) \| undefined) =< [TextModes](./compiler-core.textmodes.md) | Get text parsing mode for this element |
|  [isBuiltInComponent](./compiler-core.parseroptions.isbuiltincomponent.md) | (tag: string) =< symbol \| void | Platform-specific built-in components e.g. <Transition> |
|  [isCustomElement](./compiler-core.parseroptions.iscustomelement.md) | (tag: string) =< boolean | Separate option for end users to extend the native elements list |
|  [isNativeTag](./compiler-core.parseroptions.isnativetag.md) | (tag: string) =< boolean | e.g. platform native elements, e.g. <div> for browsers |
|  [isPreTag](./compiler-core.parseroptions.ispretag.md) | (tag: string) =< boolean | e.g. elements that should preserve whitespace inside, e.g. <pre> |
|  [isVoidTag](./compiler-core.parseroptions.isvoidtag.md) | (tag: string) =< boolean | e.g. native elements that can self-close, e.g. <img>, <br>, <hr> |
|  [onError](./compiler-core.parseroptions.onerror.md) | (error: [CompilerError](./compiler-core.compilererror.md)<!-- -->) =< void |  |
