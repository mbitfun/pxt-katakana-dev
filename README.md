# pxt-katakana
---
This library make it possible to show characters of Katakana, alphabet and some symbols.

## Basic Usage
---

```
katakana.showString(string, integer)
```

- string: characters to show
- integer: speed of scrolling

the first argument is the characters to show. The default is blank. And the second argument is the speed of scrolling, the unit is ms. The default is 500ms. The second argument can be omitted.

You can use the letters below.

 !#$%&'()*+,-./0123456789:;<=>?@ABCDEFGHIJKLMNOPQRSTUVWXYZ[\\]^_`abcdefghijklmnopqrstuvwxyz{|}~¥｡｢｣､･ｦｧｨｩｪｫｬｭｮｯｰｱｲｳｴｵｶｷｸｹｺｻｼｽｾｿﾀﾁﾂﾃﾄﾅﾆﾇﾈﾉﾊﾋﾌﾍﾎﾏﾐﾑﾒﾓﾔﾕﾖﾗﾘﾙﾚﾛﾜﾝﾞﾟ
## Example
---

```
katakana.showString("カタカナ")

katakana.showString("カタカナ",1000)
```


## License
MIT

## Supported targets

* for PXT/microbit
