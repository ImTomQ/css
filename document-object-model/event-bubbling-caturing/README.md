## Deep dive into JavaScript event bubbling and caturing.

If an element and it's parent have an event handler for the same event, which element will work first when triggered?

Let's start with an example:
This handler is assigned to `<div>`, but also runs if click any nested tag like `<em>` or `<code>`:

```
<div onclick="alert('The handler!')">
  <em>If you click on <code>EM</code>, the handler on <code>DIV</code> runs.</em>
</div>
```

### Reference

- https://blog.logrocket.com/deep-dive-into-event-bubbling-and-capturing/
