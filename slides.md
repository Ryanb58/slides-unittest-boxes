title: Unittest Boxes
author:
    name: Taylor Brazelton
    url: https://taylorbrazelton.com

output: index.html

--
# The Two Unittest Boxes
## Whitebox vs Blackbox

--
### WhiteBox Unittesting

Tests that know and make assertions on the internals of a box.

--
### WhiteBox Testing

Tests that touch anything they want.

Characteristics:
 * The component being tested is not clear.
 * Makes assertions on multiple layers.

--
### BlackBox Unittesting

The tests do not know the internals of the box being tested.

--
### BlackBox Testing

Tests that touch only a single layer.

Characteristics: 
 * Only ever touches a single layer.
 * Makes assertions throught the later it is testing.

--

# What is a Layer?

---

A layer is a specific component of the application.

#### Example Components:
 * API
 * File System
 * ORM Model
 * ORM Manager
 * 
