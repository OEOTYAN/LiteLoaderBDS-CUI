# LiteLoaderBDS-CUI

![ ](https://img.shields.io/github/license/OEOTYAN/LiteLoaderBDS-CUI?style=for-the-badge)
![ ](https://img.shields.io/github/downloads/OEOTYAN/LiteLoaderBDS-CUI/total?style=for-the-badge)
![ ](https://img.shields.io/github/v/release/OEOTYAN/LiteLoaderBDS-CUI?style=for-the-badge)

CUI for [LiteLoaderBDS](https://github.com/LiteLDev/LiteLoaderBDS)

## Color

|                    HEX                     | TYPE  | ENUM     |
| :----------------------------------------: | :---: | -------- |
| <span style="color:#000000">#000000</span> |   B   | BLACK    |
| <span style="color:#144a74">#144a74</span> |   I   | INDIGO   |
| <span style="color:#8E65F3">#8E65F3</span> |   L   | LAVENDER |
| <span style="color:#07946e">#07946e</span> |   T   | TEAL     |
| <span style="color:#AB5236">#AB5236</span> |   C   | COCOA    |
| <span style="color:#56575F">#56575F</span> |   D   | DARK     |
| <span style="color:#A2A3A7">#A2A3A7</span> |   O   | OATMEAL  |
| <span style="color:#FFFFFF">#FFFFFF</span> |   W   | WHITE    |
| <span style="color:#FF3040">#FF3040</span> |   R   | RED      |
| <span style="color:#FF7300">#FF7300</span> |   A   | APRICOT  |
| <span style="color:#FFEC27">#FFEC27</span> |   Y   | YELLOW   |
| <span style="color:#10E436">#10E436</span> |   G   | GREEN    |
| <span style="color:#29ADFF">#29ADFF</span> |   V   | VAT      |
| <span style="color:#83769C">#83769C</span> |   S   | SLATE    |
| <span style="color:#FF77A8">#FF77A8</span> |   P   | PINK     |
| <span style="color:#FFCCAA">#FFCCAA</span> |   E   | FAWN     |

# Particle Types

## Point

### Point Size

|  Size   | TYPE  | ENUM |
| :-----: | :---: | ---- |
| 1/16 m  |   1   | PX1  |
| 2/16 m  |   2   | PX2  |
| 4/16 m  |   4   | PX4  |
| 8/16 m  |   8   | PX8  |
| 16/16 m |  16   | PX16 |

### Point Style

```txt
ll:point+[ColorType]+[PointSizeType]
```

#### Point Example

> Pink px8 point

```txt
ll:pointP8
```

## Number

### Number Types

| Type  | ENUM  |
| :---: | ----- |
|   0   | NUM0  |
|   1   | NUM1  |
|   2   | NUM2  |
|   3   | NUM3  |
|   4   | NUM4  |
|   5   | NUM5  |
|   6   | NUM6  |
|   7   | NUM7  |
|   8   | NUM8  |
|   9   | NUM9  |
|  10   | NUM10 |
|  11   | NUM11 |
|  12   | NUM12 |
|  13   | NUM13 |
|  14   | NUM14 |
|  15   | NUM15 |
|  16   | NUM16 |
|   A   | NUMA  |
|   B   | NUMB  |
|   C   | NUMC  |
|   D   | NUMD  |
|   E   | NUME  |
|   F   | NUMF  |

### Number Style

```txt
ll:num+[NumberType]+[ColorType]
```

#### Number Example

> Red number A

```txt
ll:numAR
```

## Line

### Axis Type

| Type  |
| :---: |
|   X   |
|   Y   |
|   Z   |

### X Type

| Type  |
| :---: |
|   p   |
|   m   |

### Line Type

|   Type    |
| :-------: |
|   line    |
| line_back |

### Length

| Length |
| :----: |
|   1    |
|   2    |
|   4    |
|   8    |
|   16   |
|   32   |
|   64   |
|  128   |
|  256   |
|  512   |
|  1024  |
|  2048  |

### Line Style

```txt
ll:[LineType]+[XType]+[AxisType]+[ColorType]+[Length]
```

#### Line Example

> Green X-axis 256 line

```txt
ll:linepXG256
ll:linemXG256
ll:line_backpXG256
ll:line_backmXG256
```
