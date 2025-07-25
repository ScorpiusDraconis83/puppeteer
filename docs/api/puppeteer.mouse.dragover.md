---
sidebar_label: Mouse.dragOver
---

# Mouse.dragOver() method

Dispatches a `dragover` event.

### Signature

```typescript
class Mouse {
  abstract dragOver(
    target: Point,
    data: Protocol.Input.DragData,
  ): Promise<void>;
}
```

## Parameters

<table><thead><tr><th>

Parameter

</th><th>

Type

</th><th>

Description

</th></tr></thead>
<tbody><tr><td>

target

</td><td>

[Point](./puppeteer.point.md)

</td><td>

point for emitting `dragover` event

</td></tr>
<tr><td>

data

</td><td>

Protocol.Input.DragData

</td><td>

drag data containing items and operations mask

</td></tr>
</tbody></table>

**Returns:**

Promise&lt;void&gt;
