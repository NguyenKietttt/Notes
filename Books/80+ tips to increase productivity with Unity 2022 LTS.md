## Focused Inspector window

Always displays the properties of the item you opened, even if you select something else.

**How to use:** Right-click on a GameObject/Component -> choose Properties.

## Use binary serialization formats for saving data

Binary serialization formats reduce the memory & performance issues rather than text-based ones such as JSON/XML.

Recommended formats from Unity:

- [MessagePack](https://msgpack.org/index.html)
- [Protocol Buffers](https://protobuf.dev/)

## Pause execution with Debug.Break

This is useful if you want to check certain values in the Inspector when the application is difficult to pause manually.
