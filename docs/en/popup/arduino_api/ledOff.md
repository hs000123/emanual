---
layout: popup
---

# ledOff

## Description

This function turns off the led of DYNAMIXEL.

## Syntax

- ledOff(id)

## Parameters

- **id** : ID of a specific DYNAMIXEL. Data type : unsigned int8

## Returns

- True(1) on success.
- False(0) on failure.

## Example

```c++
  const int DXL_DIR_PIN = 2;
  Dynamixel2Arduino dxl(Serial1, DXL_DIR_PIN);
  dxl.ledOff(1);
```
