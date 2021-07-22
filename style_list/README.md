## Preset styles

- [Preset styles](#preset-styles)
  - [`ascii`](#ascii)
  - [`ascii_borderless`](#ascii_borderless)
  - [`ascii_box`](#ascii_box)
  - [`ascii_compact`](#ascii_compact)
  - [`ascii_double`](#ascii_double)
  - [`ascii_minimalist`](#ascii_minimalist)
  - [`ascii_simple`](#ascii_simple)
  - [`borderless`](#borderless)
  - [`double`](#double)
  - [`double_box`](#double_box)
  - [`double_compact`](#double_compact)
  - [`double_thin_compact`](#double_thin_compact)
  - [`markdown`](#markdown)
  - [`minimalist`](#minimalist)
  - [`simple`](#simple)
  - [`thick`](#thick)
  - [`thick_box`](#thick_box)
  - [`thick_compact`](#thick_compact)
  - [`thin`](#thin)
  - [`thin_box`](#thin_box)
  - [`thin_compact`](#thin_compact)
  - [`thin_compact_rounded`](#thin_compact_rounded)
  - [`thin_double`](#thin_double)
  - [`thin_double_rounded`](#thin_double_rounded)
  - [`thin_rounded`](#thin_rounded)
  - [`thin_thick`](#thin_thick)
  - [`thin_thick_rounded`](#thin_thick_rounded)

### `ascii`

```
+-----+-----------------------+
|  #  |  G     H     R     S  |
+-----+-----------------------+
|  1  | 30    40    35    30  |
+-----+-----------------------+
|  2  | 30    40    35    30  |
+-----+-----------------------+
| SUM | 130   140   135   130 |
+-----+-----------------------+

+---+-------------------+
| 1 | 30   40   35   30 |
+---+-------------------+
| 2 | 30   40   35   30 |
+---+-------------------+
```
### `ascii_borderless`

```
   #  |  G     H     R     S   
 ----- ----- ----- ----- ----- 
   1  | 30    40    35    30   
   2  | 30    40    35    30   
 ----- ----- ----- ----- ----- 
  SUM | 130   140   135   130  

  1 | 30   40   35   30  
  2 | 30   40   35   30  
```
### `ascii_box`

```
+-----+-----+-----+-----+-----+
|  #  |  G  |  H  |  R  |  S  |
+-----+-----+-----+-----+-----+
|  1  | 30  | 40  | 35  | 30  |
+-----+-----+-----+-----+-----+
|  2  | 30  | 40  | 35  | 30  |
+-----+-----+-----+-----+-----+
| SUM | 130 | 140 | 135 | 130 |
+-----+-----+-----+-----+-----+

+---+----+----+----+----+
| 1 | 30 | 40 | 35 | 30 |
+---+----+----+----+----+
| 2 | 30 | 40 | 35 | 30 |
+---+----+----+----+----+
```
### `ascii_compact`

```
+-----+-----------------------+
|  #  |  G     H     R     S  |
+-----+-----------------------+
|  1  | 30    40    35    30  |
|  2  | 30    40    35    30  |
+-----+-----------------------+
| SUM | 130   140   135   130 |
+-----+-----------------------+

+---+-------------------+
| 1 | 30   40   35   30 |
| 2 | 30   40   35   30 |
+---+-------------------+
```
### `ascii_double`

```
+-----+-----------------------+
|  #  |  G     H     R     S  |
+=====+=======================+
|  1  | 30    40    35    30  |
+-----+-----------------------+
|  2  | 30    40    35    30  |
+=====+=======================+
| SUM | 130   140   135   130 |
+-----+-----------------------+

+---+-------------------+
| 1 | 30   40   35   30 |
+---+-------------------+
| 2 | 30   40   35   30 |
+---+-------------------+
```
### `ascii_minimalist`

```
 ----------------------------- 
   #  |  G     H     R     S   
 ============================= 
   1  | 30    40    35    30   
 ----------------------------- 
   2  | 30    40    35    30   
 ============================= 
  SUM | 130   140   135   130  
 ----------------------------- 

 ----------------------- 
  1 | 30   40   35   30  
 ----------------------- 
  2 | 30   40   35   30  
 ----------------------- 
```
### `ascii_simple`

```
 ===== ===== ===== ===== ===== 
   #  |  G     H     R     S   
 ===== ===== ===== ===== ===== 
   1  | 30    40    35    30   
   2  | 30    40    35    30   
 ===== ===== ===== ===== ===== 
  SUM | 130   140   135   130  
 ===== ===== ===== ===== ===== 

 === ==== ==== ==== ==== 
  1 | 30   40   35   30  
  2 | 30   40   35   30  
 === ==== ==== ==== ==== 
```
### `borderless`

```
   #  ┃  G     H     R     S   
 ━━━━━ ━━━━━ ━━━━━ ━━━━━ ━━━━━ 
   1  ┃ 30    40    35    30   
   2  ┃ 30    40    35    30   
 ━━━━━ ━━━━━ ━━━━━ ━━━━━ ━━━━━ 
  SUM ┃ 130   140   135   130  

  1 ┃ 30   40   35   30  
  2 ┃ 30   40   35   30  
```
### `double`

```
╔═════╦═══════════════════════╗
║  #  ║  G     H     R     S  ║
╠═════╬═══════════════════════╣
║  1  ║ 30    40    35    30  ║
╠═════╬═══════════════════════╣
║  2  ║ 30    40    35    30  ║
╠═════╬═══════════════════════╣
║ SUM ║ 130   140   135   130 ║
╚═════╩═══════════════════════╝

╔═══╦═══════════════════╗
║ 1 ║ 30   40   35   30 ║
╠═══╬═══════════════════╣
║ 2 ║ 30   40   35   30 ║
╚═══╩═══════════════════╝
```
### `double_box`

```
╔═════╦═════╦═════╦═════╦═════╗
║  #  ║  G  ║  H  ║  R  ║  S  ║
╠═════╬═════╬═════╬═════╬═════╣
║  1  ║ 30  ║ 40  ║ 35  ║ 30  ║
╠═════╬═════╬═════╬═════╬═════╣
║  2  ║ 30  ║ 40  ║ 35  ║ 30  ║
╠═════╬═════╬═════╬═════╬═════╣
║ SUM ║ 130 ║ 140 ║ 135 ║ 130 ║
╚═════╩═════╩═════╩═════╩═════╝

╔═══╦════╦════╦════╦════╗
║ 1 ║ 30 ║ 40 ║ 35 ║ 30 ║
╠═══╬════╬════╬════╬════╣
║ 2 ║ 30 ║ 40 ║ 35 ║ 30 ║
╚═══╩════╩════╩════╩════╝
```
### `double_compact`

```
╔═════╦═══════════════════════╗
║  #  ║  G     H     R     S  ║
╠═════╬═══════════════════════╣
║  1  ║ 30    40    35    30  ║
║  2  ║ 30    40    35    30  ║
╠═════╬═══════════════════════╣
║ SUM ║ 130   140   135   130 ║
╚═════╩═══════════════════════╝

╔═══╦═══════════════════╗
║ 1 ║ 30   40   35   30 ║
║ 2 ║ 30   40   35   30 ║
╚═══╩═══════════════════╝
```
### `double_thin_compact`

```
╔═════╦═══════════════════════╗
║  #  ║  G     H     R     S  ║
╟─────╫───────────────────────╢
║  1  ║ 30    40    35    30  ║
║  2  ║ 30    40    35    30  ║
╟─────╫───────────────────────╢
║ SUM ║ 130   140   135   130 ║
╚═════╩═══════════════════════╝

╔═══╦═══════════════════╗
║ 1 ║ 30   40   35   30 ║
║ 2 ║ 30   40   35   30 ║
╚═══╩═══════════════════╝
```
### `markdown`

```
| #     | G     | H     | R     | S     |
| ----- | ----- | ----- | ----- | ----- |
| 1     | 30    | 40    | 35    | 30    |
| 2     | 30    | 40    | 35    | 30    |
| ----- | ----- | ----- | ----- | ----- |
| SUM   | 130   | 140   | 135   | 130   |

| 1 | 30 | 40 | 35 | 30 |
| 2 | 30 | 40 | 35 | 30 |
```
### `minimalist`

```
 ───────────────────────────── 
   #  │  G     H     R     S   
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 
   1  │ 30    40    35    30   
 ───────────────────────────── 
   2  │ 30    40    35    30   
 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 
  SUM │ 130   140   135   130  
 ───────────────────────────── 

 ─────────────────────── 
  1 │ 30   40   35   30  
 ─────────────────────── 
  2 │ 30   40   35   30  
 ─────────────────────── 
```
### `simple`

```
 ═════ ═════ ═════ ═════ ═════ 
   #  ║  G     H     R     S   
 ═════ ═════ ═════ ═════ ═════ 
   1  ║ 30    40    35    30   
   2  ║ 30    40    35    30   
 ═════ ═════ ═════ ═════ ═════ 
  SUM ║ 130   140   135   130  
 ═════ ═════ ═════ ═════ ═════ 

 ═══ ════ ════ ════ ════ 
  1 ║ 30   40   35   30  
  2 ║ 30   40   35   30  
 ═══ ════ ════ ════ ════ 
```
### `thick`

```
┏━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━┓
┃  #  ┃  G     H     R     S  ┃
┣━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━┫
┃  1  ┃ 30    40    35    30  ┃
┣━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━┫
┃  2  ┃ 30    40    35    30  ┃
┣━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━┫
┃ SUM ┃ 130   140   135   130 ┃
┗━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━┛

┏━━━┳━━━━━━━━━━━━━━━━━━━┓
┃ 1 ┃ 30   40   35   30 ┃
┣━━━╋━━━━━━━━━━━━━━━━━━━┫
┃ 2 ┃ 30   40   35   30 ┃
┗━━━┻━━━━━━━━━━━━━━━━━━━┛
```
### `thick_box`

```
┏━━━━━┳━━━━━┳━━━━━┳━━━━━┳━━━━━┓
┃  #  ┃  G  ┃  H  ┃  R  ┃  S  ┃
┣━━━━━╋━━━━━╋━━━━━╋━━━━━╋━━━━━┫
┃  1  ┃ 30  ┃ 40  ┃ 35  ┃ 30  ┃
┣━━━━━╋━━━━━╋━━━━━╋━━━━━╋━━━━━┫
┃  2  ┃ 30  ┃ 40  ┃ 35  ┃ 30  ┃
┣━━━━━╋━━━━━╋━━━━━╋━━━━━╋━━━━━┫
┃ SUM ┃ 130 ┃ 140 ┃ 135 ┃ 130 ┃
┗━━━━━┻━━━━━┻━━━━━┻━━━━━┻━━━━━┛

┏━━━┳━━━━┳━━━━┳━━━━┳━━━━┓
┃ 1 ┃ 30 ┃ 40 ┃ 35 ┃ 30 ┃
┣━━━╋━━━━╋━━━━╋━━━━╋━━━━┫
┃ 2 ┃ 30 ┃ 40 ┃ 35 ┃ 30 ┃
┗━━━┻━━━━┻━━━━┻━━━━┻━━━━┛
```
### `thick_compact`

```
┏━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━┓
┃  #  ┃  G     H     R     S  ┃
┣━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━┫
┃  1  ┃ 30    40    35    30  ┃
┃  2  ┃ 30    40    35    30  ┃
┣━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━┫
┃ SUM ┃ 130   140   135   130 ┃
┗━━━━━┻━━━━━━━━━━━━━━━━━━━━━━━┛

┏━━━┳━━━━━━━━━━━━━━━━━━━┓
┃ 1 ┃ 30   40   35   30 ┃
┃ 2 ┃ 30   40   35   30 ┃
┗━━━┻━━━━━━━━━━━━━━━━━━━┛
```
### `thin`

```
┌─────┬───────────────────────┐
│  #  │  G     H     R     S  │
├─────┼───────────────────────┤
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
├─────┼───────────────────────┤
│ SUM │ 130   140   135   130 │
└─────┴───────────────────────┘

┌───┬───────────────────┐
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
└───┴───────────────────┘
```
### `thin_box`

```
┌─────┬─────┬─────┬─────┬─────┐
│  #  │  G  │  H  │  R  │  S  │
├─────┼─────┼─────┼─────┼─────┤
│  1  │ 30  │ 40  │ 35  │ 30  │
├─────┼─────┼─────┼─────┼─────┤
│  2  │ 30  │ 40  │ 35  │ 30  │
├─────┼─────┼─────┼─────┼─────┤
│ SUM │ 130 │ 140 │ 135 │ 130 │
└─────┴─────┴─────┴─────┴─────┘

┌───┬────┬────┬────┬────┐
│ 1 │ 30 │ 40 │ 35 │ 30 │
├───┼────┼────┼────┼────┤
│ 2 │ 30 │ 40 │ 35 │ 30 │
└───┴────┴────┴────┴────┘
```
### `thin_compact`

```
┌─────┬───────────────────────┐
│  #  │  G     H     R     S  │
├─────┼───────────────────────┤
│  1  │ 30    40    35    30  │
│  2  │ 30    40    35    30  │
├─────┼───────────────────────┤
│ SUM │ 130   140   135   130 │
└─────┴───────────────────────┘

┌───┬───────────────────┐
│ 1 │ 30   40   35   30 │
│ 2 │ 30   40   35   30 │
└───┴───────────────────┘
```
### `thin_compact_rounded`

```
╭─────┬───────────────────────╮
│  #  │  G     H     R     S  │
├─────┼───────────────────────┤
│  1  │ 30    40    35    30  │
│  2  │ 30    40    35    30  │
├─────┼───────────────────────┤
│ SUM │ 130   140   135   130 │
╰─────┴───────────────────────╯

╭───┬───────────────────╮
│ 1 │ 30   40   35   30 │
│ 2 │ 30   40   35   30 │
╰───┴───────────────────╯
```
### `thin_double`

```
┌─────┬───────────────────────┐
│  #  │  G     H     R     S  │
╞═════╪═══════════════════════╡
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
╞═════╪═══════════════════════╡
│ SUM │ 130   140   135   130 │
└─────┴───────────────────────┘

┌───┬───────────────────┐
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
└───┴───────────────────┘
```
### `thin_double_rounded`

```
╭─────┬───────────────────────╮
│  #  │  G     H     R     S  │
╞═════╪═══════════════════════╡
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
╞═════╪═══════════════════════╡
│ SUM │ 130   140   135   130 │
╰─────┴───────────────────────╯

╭───┬───────────────────╮
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
╰───┴───────────────────╯
```
### `thin_rounded`

```
╭─────┬───────────────────────╮
│  #  │  G     H     R     S  │
├─────┼───────────────────────┤
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
├─────┼───────────────────────┤
│ SUM │ 130   140   135   130 │
╰─────┴───────────────────────╯

╭───┬───────────────────╮
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
╰───┴───────────────────╯
```
### `thin_thick`

```
┌─────┬───────────────────────┐
│  #  │  G     H     R     S  │
┝━━━━━┿━━━━━━━━━━━━━━━━━━━━━━━┥
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
┝━━━━━┿━━━━━━━━━━━━━━━━━━━━━━━┥
│ SUM │ 130   140   135   130 │
└─────┴───────────────────────┘

┌───┬───────────────────┐
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
└───┴───────────────────┘
```
### `thin_thick_rounded`

```
╭─────┬───────────────────────╮
│  #  │  G     H     R     S  │
┝━━━━━┿━━━━━━━━━━━━━━━━━━━━━━━┥
│  1  │ 30    40    35    30  │
├─────┼───────────────────────┤
│  2  │ 30    40    35    30  │
┝━━━━━┿━━━━━━━━━━━━━━━━━━━━━━━┥
│ SUM │ 130   140   135   130 │
╰─────┴───────────────────────╯

╭───┬───────────────────╮
│ 1 │ 30   40   35   30 │
├───┼───────────────────┤
│ 2 │ 30   40   35   30 │
╰───┴───────────────────╯
```