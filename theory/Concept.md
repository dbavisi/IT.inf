# Core Concepts

A Concept is an acknowledgement of something.

An Attribute is a concept that acknowledges a characteristic of some concept.

> Acknowledgement is an attribute of every concept.

A Comparison is the concept of identification and acknowledgement of some attributes amongst given concepts.

The given concepts are Comparable if the required attributes can be acknowledged, and the required attributes are also comparable.

> Every concept is comparable with itself.

> Comparable is an attribute of the given concepts within the context of the comparison.

The given concepts are Uncomparable if the required attributes cannot be acknowledged, or the required attributes are not comparable.

> Uncomparable is an attribute of the given concepts within the context of the comparison.

The given concepts are the Same if the given concepts are comparable, and all of their attributes are also the same.

> Every concept is the same with itself.

> Same is an attribute of every concept within the context of the comparison with itself.

The given concepts are Different if the given concepts are comparable, but some of their attributes are not comparable.

> Different is an attribute of the given concepts within the context of the comparison.

The given concepts are Similar if the given concepts are comparable, and all of their attributes are also comparable, but some of their attributes are not the same.

> Similar is an attribute of the given concepts within the context of the comparison.

A Representation is a concept that acknowledges only the required attributes of the given concept within the context of the comparison.

> Every representation of a concept is an attribute of the given concept.

> Similar is an attribute of every representation of a concept and the given concept within the context of the comparison.

A Collection is the concept of aggregation of similar concepts.

> Membership to the collection is an attribute of the given concepts within the context of the collection.

# Notations
A Notation is the collection of concepts required for the representation of any concept.

`C` is the notation for the representation of the collection of every concept with the acknowledgement attribute.

`Attr(cpt)` is the notation for the representation of the collection of every attribute of the given concept `cpt`.

`cpt.attr` is the notation for the representation of the given attribute `attr` of the given concept `cpt`.

`cmp(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...`.

`cmp.Comparable(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...` that are comparable.

`cmp.Uncomparable(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...` that are uncomparable.

`cmp.Same(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...` that are the same.

`cmp.Different(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...` that are different.

`cmp.Similar(cpt, ...)` is the notation for the representation of the given comparison `cmp` of the given concept `cpt` with every given concepts `...` that are similar.

`Repr(cpt)` is the notation for the representation of the collection of every representation of the given concept `cpt`.

`member(cpt, cll)` is the notation for the representation of the membership attribute of the given concept `cpt` within the given collection `cll`.

`Cll(cpt)` is the notation for the representation of the collection of every collection that the given concept `cpt` is a member of.

`not(cll)` is the notation for the representation of the collection of every concept that is not a member of the given collection `cll`.

`Union(...)` is the notation for the representation of the collection of every concept that is a member of any of the given collections `...`.

`Inter(...)` is the notation for the representation of the collection of every concept that is a member of every given collections `...`.

```
cmp(cpt, ...) = Union(cmp.Comparable(cpt, ...), cmp.Uncomparable(cpt, ...))
```

```
cmp.Comparable(cpt, ...) = Union(cmp.Same(cpt, ...), cmp.Different(cpt, ...), cmp.Similar(cpt, ...))
```
