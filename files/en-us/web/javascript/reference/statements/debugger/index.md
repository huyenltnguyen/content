---
title: debugger
slug: Web/JavaScript/Reference/Statements/debugger
tags:
  - JavaScript
  - Language feature
  - Statement
browser-compat: javascript.statements.debugger
---
{{jsSidebar("Statements")}}

The **`debugger` statement** invokes any available debugging functionality, such
as setting a breakpoint. If no debugging functionality is available, this
statement has no effect.

## Syntax

```js
debugger;
```

## Examples

### Using the debugger statement

The following example shows code where a `debugger` statement has been inserted,
to invoke a debugger (if one exists) when the function is called.

```js
function potentiallyBuggyCode() {
    debugger;
    // do potentially buggy stuff to examine, step through, etc.
}
```

When the debugger is invoked, execution is paused at the `debugger` statement.
It is like a breakpoint in the script source.

[![Paused at a debugger statement.](screen_shot\_2014-02-07\_at\_9.14.35\_am.png)](https://mdn.mozillademos.org/files/6963/Screen%20Shot%202014-02-07%20at%209.14.35%20AM.png)

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

*   [Debugging JavaScript](/en-US/docs/Mozilla/Debugging/Debugging_JavaScript)
*   [The Debugger in the Firefox Developer Tools](/en-US/docs/Tools/Debugger)
