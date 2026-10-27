# LINQ to XML

## Overview

LINQ to XML allows you to read, query, and manipulate XML documents using LINQ.

## Example

```csharp
XDocument doc = XDocument.Load("products.xml");
var products = doc.Descendants("Product")
    .Where(p => (string)p.Element("Category") == "Computer")
    .ToList();
```

## Typical operations

- read XML
- filter nodes
- create new XML data
- update elements
- delete elements

## School use

This is useful when the exercise requires data stored in XML files to be searched and modified.
