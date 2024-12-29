# Cpt.0/1: Core Concepts
`Cpt.0/1` is the **Collection `IT.7/1`** of **Concepts `IT.0/1`** upon
which the `IT.inf` is built.

In accordance with **Information Tagging Syntax `IT.2/1`**,
each section title within this document is inherently treated as
an **Information Tag `IT.1/1`**.

Cpt.1/1: Information Tagging
----------------------------
**Information Tagging `IT.1/1`** is a core **Concept `IT.0/1`** of
the `IT.inf`.
This section illustrates the **Information Tagging Syntax `IT.2/1`**,
and defines the **Completeness of Tag `IT.3/1`** crucial for defining
level of specification of the **Tags `IT.1/1`** within `IT.inf`.

### IT.2/1: Information Tagging Syntax
Each **Information Tag `IT.1/1`** is a **Concept `IT.0/1`** consisting
of at least the following **Attributes `IT.14/1`**.

+ **Type `Atr.1/1`** refers to a category of **Tags `IT.1/1`**.
+ **Identifier `Atr.2/1`** denotes a unique identifier
  that distinguishes each **Tag `IT.1/1`** from others of
  the same **Type `Atr.0/1`**.
+ **Representation Identifier `Atr.3/1`** refers to an alternate
  **Representation `IT.15/1`** of the underlying **Concept `IT.0/1`**.
+ **Name `Atr.4/1`** refers to the term associated with **Tag `IT.1/1`**.
+ **Value `Atr.5/1`** refers to the underlying **Concept `IT.0/1`**
  associated with the **Tag `IT.1/1`**.

### IT.3/1: Completeness of Tag
The **Completeness of Tag `IT.3/1`** is determined by
**Tag Value `Atr.5/1`** and can be classified into the following:

+ **Fully-defined `IT.4/1`**, represents a **Concept `IT.0/1`** that is
  closed in terms of its definition and has all necessary
  **Attributes `IT.14/1`** explicitly defined.
+ **Eventually-defined `IT.5/1`**, represents a **Concept `IT.0/1`** that
  is expected to be **Fully-defined `IT.4/1`** when the underlying
  **Concepts `IT.0/1`** are expected to be **Fully-defined `IT.4/1`**
  but lacks clarity otherwise.
+ **Undefined `IT.6/1`**, represents a **Concept `IT.0/1`** that
  completely lacks clarity unless explicitly modified.

> **Information Tagging `IT.1/1`** is not about naming what you see;
> Its about marking what you notice.

Cpt.2/1: Fundamental Concepts
-----------------------------
This section defines the core **Concepts `IT.0/1`** that form the
foundation of the `IT.inf`.

+ **Concept `IT.0/1`**: The base type for representing anything that can
  be defined or processed within the `IT.inf`.
+ **Collection `IT.7/1`**: Aggregation of related **Concepts `IT.0/1`**
  and/or **Attributes `IT.14/1`**.
+ **Data `IT.8/1`**: inherently useless in its raw form.
+ **Information `IT.9/1`**: A **Concept `IT.0/1`** that represents the
  **Data `IT.8/1`** in a may, making it useful.
+ **Knowledge `IT.10/1`**: A type of **Concept `IT.0/1`** that represents
  the ability to transform **Data `IT.8/1`** into **Information `IT.9/1`**
  through some process.
+ **Inference `IT.11/1`**: The process of transformation which is
  described by the **Knowledge `IT.10/1`**.
+ **Inference Engine `IT.12/1`**: The facilitator of **Inference `IT.11/1`**.
+ **Spirit `IT.13/1`**: The facilitator of **Knowledge `IT.10/1`**.

### IT.14/1: Attribute
**Attributes `IT.14/1`** are intrinsic properties of a **Concept `IT.0/1`**
that define its characteristics or qualities.
These **Attributes `IT.14/1`** can also be passed as inputs to the
**Inference Engine `IT.12/1`**, making them a **Concept `IT.0/1`** in
themselves, subject to transformation and processing.

### IT.15/1: Representation
**Representation ``IT.15/1``** refers to the transformation of the same
**Concept ``IT.0/1``** by varying **Attributes ``IT.14/1``**, while
retaining the underlying meaning.
