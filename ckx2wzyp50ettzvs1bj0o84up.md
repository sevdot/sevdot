## Html 实体

HTML 文档中有些字符具体特殊含义， 最明显的是 < 和 > 这两个字符，有时需要在文档内容中用到这些字符，但不想他们被当做 HTML 处理。为此应该使用 HTML 实体（entity）。实体是浏览器用来代替特殊字符的一种代码。
​

每一个文本实体由`&`开头，由`;`结束，以下是一些常用的实体：

| 显示结果 | 描述 | 实体名称 | 实体编号 |
| --- | --- | --- | --- |
|   | 空格 | &nbsp; | &#160; |
| < | 小于号 | &lt; | &#60; |
| > | 大于号 | &gt; | &#62; |
| & | 和号 | &amp; | &#38; |
| " | 引号 | &quot; | &#34; |
| ' | 撇号  | &apos; (IE不支持) | &#39; |
| ￠ | 分（cent） | &cent; | &#162; |
| £ | 镑（pound） | &pound; | &#163; |
| ¥ | 元（yen） | &yen; | &#165; |
| € | 欧元（euro） | &euro; | &#8364; |
| § | 小节 | &sect; | &#167; |
| © | 版权（copyright） | &copy; | &#169; |
| ® | 注册商标 | &reg; | &#174; |
| ™ | 商标 | &trade; | &#8482; |
| × | 乘号 | &times; | &#215; |
| ÷ | 除号 | &divide; | &#247; |

每个特殊字符都有一个实体编号，可以用来在文档内容中代表该字符。例如，字符 “&” 的实体编号是 `&#38;`。特别常用的特殊字符还有对应的实体名称。例如，对于浏览器来说，`&#38` 和 `&amp;` 是一回事。
​

更多文本实体参考如下：
​

| 字符 | 编码 | 描述 |
| --- | --- | --- |
| NUL | 00 | null character |
| SOH | 01 | start of header |
| STX | 02 | start of text |
| ETX | 03 | end of text |
| EOT | 04 | end of transmission |
| ENQ | 05 | enquiry |
| ACK | 06 | acknowledge |
| BEL | 07 | bell (ring) |
| BS | 08 | backspace |
| HT | 09 | horizontal tab |
| LF | 10 | line feed |
| VT | 11 | vertical tab |
| FF | 12 | form feed |
| CR | 13 | carriage return |
| SO | 14 | shift out |
| SI | 15 | shift in |
| DLE | 16 | data link escape |
| DC1 | 17 | device control 1 |
| DC2 | 18 | device control 2 |
| DC3 | 19 | device control 3 |
| DC4 | 20 | device control 4 |
| NAK | 21 | negative acknowledge |
| SYN | 22 | synchronize |
| ETB | 23 | end transmission block |
| CAN | 24 | cancel |
| EM | 25 | end of medium |
| SUB | 26 | substitute |
| ESC | 27 | escape |
| FS | 28 | file separator |
| GS | 29 | group separator |
| RS | 30 | record separator |
| US | 31 | unit separator |

| 字符 | 数字 | 描述 |
| --- | --- | --- |
|   | 32 | space |
| ! | 33 | exclamation mark |
| " | 34 | quotation mark |
| # | 35 | number sign |
| $ | 36 | dollar sign |
| % | 37 | percent sign |
| & | 38 | ampersand |
| ' | 39 | apostrophe |
| ( | 40 | left parenthesis |
| ) | 41 | right parenthesis |
| * | 42 | asterisk |
| + | 43 | plus sign |
| , | 44 | comma |
| - | 45 | hyphen |
| . | 46 | period |
| / | 47 | slash |
| 0 | 48 | digit 0 |
| 1 | 49 | digit 1 |
| 2 | 50 | digit 2 |
| 3 | 51 | digit 3 |
| 4 | 52 | digit 4 |
| 5 | 53 | digit 5 |
| 6 | 54 | digit 6 |
| 7 | 55 | digit 7 |
| 8 | 56 | digit 8 |
| 9 | 57 | digit 9 |
| : | 58 | colon |
| ; | 59 | semicolon |
| < | 60 | less-than |
| = | 61 | equals-to |
| > | 62 | greater-than |
| ? | 63 | question mark |
| @ | 64 | at sign |
| A | 65 | uppercase A |
| B | 66 | uppercase B |
| C | 67 | uppercase C |
| D | 68 | uppercase D |
| E | 69 | uppercase E |
| F | 70 | uppercase F |
| G | 71 | uppercase G |
| H | 72 | uppercase H |
| I | 73 | uppercase I |
| J | 74 | uppercase J |
| K | 75 | uppercase K |
| L | 76 | uppercase L |
| M | 77 | uppercase M |
| N | 78 | uppercase N |
| O | 79 | uppercase O |
| P | 80 | uppercase P |
| Q | 81 | uppercase Q |
| R | 82 | uppercase R |
| S | 83 | uppercase S |
| T | 84 | uppercase T |
| U | 85 | uppercase U |
| V | 86 | uppercase V |
| W | 87 | uppercase W |
| X | 88 | uppercase X |
| Y | 89 | uppercase Y |
| Z | 90 | uppercase Z |
| [ | 91 | left square bracket |
| \ | 92 | backslash |
| ] | 93 | right square bracket |
| ^ | 94 | caret |
| _ | 95 | underscore |
| ` | 96 | grave accent |
| a | 97 | lowercase a |
| b | 98 | lowercase b |
| c | 99 | lowercase c |
| d | 100 | lowercase d |
| e | 101 | lowercase e |
| f | 102 | lowercase f |
| g | 103 | lowercase g |
| h | 104 | lowercase h |
| i | 105 | lowercase i |
| j | 106 | lowercase j |
| k | 107 | lowercase k |
| l | 108 | lowercase l |
| m | 109 | lowercase m |
| n | 110 | lowercase n |
| o | 111 | lowercase o |
| p | 112 | lowercase p |
| q | 113 | lowercase q |
| r | 114 | lowercase r |
| s | 115 | lowercase s |
| t | 116 | lowercase t |
| u | 117 | lowercase u |
| v | 118 | lowercase v |
| w | 119 | lowercase w |
| x | 120 | lowercase x |
| y | 121 | lowercase y |
| z | 122 | lowercase z |
| { | 123 | left curly brace |
| | | 124 | vertical bar |
| } | 125 | right curly brace |
| ~ | 126 | tilde |

| 字符 | 实体编号 | 实体名称 | 描述 |
| --- | --- | --- | --- |
|   | 127 |   | Control character (see below) |
| € | 128 | &euro; | euro sign |
|   | 129 |   | NOT USED |
| ‚ | 130 | &sbquo; | single low-9 quotation mark |
| ƒ | 131 | &fnof; | Latin small letter f with hook |
| „ | 132 | &bdquo; | double low-9 quotation mark |
| … | 133 | &hellip; | horizontal ellipsis |
| † | 134 | &dagger; | dagger |
| ‡ | 135 | &Dagger; | double dagger |
| ˆ | 136 | &circ; | modifier letter circumflex accent |
| ‰ | 137 | &permil; | per mille sign |
| Š | 138 | &Scaron; | Latin capital letter S with caron |
| ‹ | 139 | &lsaquo; | single left-pointing angle quotation mark |
| Œ | 140 | &OElig; | Latin capital ligature OE |
|   | 141 |   | NOT USED |
| Ž | 142 | &Zcaron; | Latin capital letter Z with caron |
|   | 143 |   | NOT USED |
|   | 144 |   | NOT USED |
| ‘ | 145 | &lsquo; | left single quotation mark |
| ’ | 146 | &rsquo; | right single quotation mark |
| “ | 147 | &ldquo; | left double quotation mark |
| ” | 148 | &rdquo; | right double quotation mark |
| • | 149 | &bull; | bullet |
| – | 150 | &ndash; | en dash |
| — | 151 | &mdash; | em dash |
| ˜ | 152 | &tilde; | small tilde |
| ™ | 153 | &trade; | trade mark sign |
| š | 154 | &scaron; | Latin small letter s with caron |
| › | 155 | &rsaquo; | single right-pointing angle quotation mark |
| œ | 156 | &oelig; | Latin small ligature oe |
|   | 157 |   | NOT USED |
| ž | 158 | &zcaron; | Latin small letter z with caron |
| Ÿ | 159 | &Yuml; | Latin capital letter Y with diaeresis |
|   | 160 | &nbsp; | no-break space |
| ¡ | 161 | &iexcl; | inverted exclamation mark |
| ¢ | 162 | &cent; | cent sign |
| £ | 163 | &pound; | pound sign |
| ¤ | 164 | &curren; | currency sign |
| ¥ | 165 | &yen; | yen sign |
| ¦ | 166 | &brvbar; | broken bar |
| § | 167 | &sect; | section sign |
| ¨ | 168 | &uml; | diaeresis |
| © | 169 | &copy; | copyright sign |
| ª | 170 | &ordf; | feminine ordinal indicator |
| « | 171 | &laquo; | left-pointing double angle quotation mark |
| ¬ | 172 | &not; | not sign |
| �­ | 173 | &shy; | soft hyphen |
| ® | 174 | &reg; | registered sign |
| ¯ | 175 | &macr; | macron |
| ° | 176 | &deg; | degree sign |
| ± | 177 | &plusmn; | plus-minus sign |
| ² | 178 | &sup2; | superscript two |
| ³ | 179 | &sup3; | superscript three |
| ´ | 180 | &acute; | acute accent |
| µ | 181 | &micro; | micro sign |
| ¶ | 182 | &para; | pilcrow sign |
| · | 183 | &middot; | middle dot |
| ¸ | 184 | &cedil; | cedilla |
| ¹ | 185 | &sup1; | superscript one |
| º | 186 | &ordm; | masculine ordinal indicator |
| » | 187 | &raquo; | right-pointing double angle quotation mark |
| ¼ | 188 | &frac14; | vulgar fraction one quarter |
| ½ | 189 | &frac12; | vulgar fraction one half |
| ¾ | 190 | &frac34; | vulgar fraction three quarters |
| ¿ | 191 | &iquest; | inverted question mark |
| À | 192 | &Agrave; | Latin capital letter A with grave |
| Á | 193 | &Aacute; | Latin capital letter A with acute |
| Â | 194 | &Acirc; | Latin capital letter A with circumflex |
| Ã | 195 | &Atilde; | Latin capital letter A with tilde |
| Ä | 196 | &Auml; | Latin capital letter A with diaeresis |
| Å | 197 | &Aring; | Latin capital letter A with ring above |
| Æ | 198 | &AElig; | Latin capital letter AE |
| Ç | 199 | &Ccedil; | Latin capital letter C with cedilla |
| È | 200 | &Egrave; | Latin capital letter E with grave |
| É | 201 | &Eacute; | Latin capital letter E with acute |
| Ê | 202 | &Ecirc; | Latin capital letter E with circumflex |
| Ë | 203 | &Euml; | Latin capital letter E with diaeresis |
| Ì | 204 | &Igrave; | Latin capital letter I with grave |
| Í | 205 | &Iacute; | Latin capital letter I with acute |
| Î | 206 | &Icirc; | Latin capital letter I with circumflex |
| Ï | 207 | &Iuml; | Latin capital letter I with diaeresis |
| Ð | 208 | &ETH; | Latin capital letter Eth |
| Ñ | 209 | &Ntilde; | Latin capital letter N with tilde |
| Ò | 210 | &Ograve; | Latin capital letter O with grave |
| Ó | 211 | &Oacute; | Latin capital letter O with acute |
| Ô | 212 | &Ocirc; | Latin capital letter O with circumflex |
| Õ | 213 | &Otilde; | Latin capital letter O with tilde |
| Ö | 214 | &Ouml; | Latin capital letter O with diaeresis |
| × | 215 | &times; | multiplication sign |
| Ø | 216 | &Oslash; | Latin capital letter O with stroke |
| Ù | 217 | &Ugrave; | Latin capital letter U with grave |
| Ú | 218 | &Uacute; | Latin capital letter U with acute |
| Û | 219 | &Ucirc; | Latin capital letter U with circumflex |
| Ü | 220 | &Uuml; | Latin capital letter U with diaeresis |
| Ý | 221 | &Yacute; | Latin capital letter Y with acute |
| Þ | 222 | &THORN; | Latin capital letter Thorn |
| ß | 223 | &szlig; | Latin small letter sharp s |
| à | 224 | &agrave; | Latin small letter a with grave |
| á | 225 | &aacute; | Latin small letter a with acute |
| â | 226 | &acirc; | Latin small letter a with circumflex |
| ã | 227 | &atilde; | Latin small letter a with tilde |
| ä | 228 | &auml; | Latin small letter a with diaeresis |
| å | 229 | &aring; | Latin small letter a with ring above |
| æ | 230 | &aelig; | Latin small letter ae |
| ç | 231 | &ccedil; | Latin small letter c with cedilla |
| è | 232 | &egrave; | Latin small letter e with grave |
| é | 233 | &eacute; | Latin small letter e with acute |
| ê | 234 | &ecirc; | Latin small letter e with circumflex |
| ë | 235 | &euml; | Latin small letter e with diaeresis |
| ì | 236 | &igrave; | Latin small letter i with grave |
| í | 237 | &iacute; | Latin small letter i with acute |
| î | 238 | &icirc; | Latin small letter i with circumflex |
| ï | 239 | &iuml; | Latin small letter i with diaeresis |
| ð | 240 | &eth; | Latin small letter eth |
| ñ | 241 | &ntilde; | Latin small letter n with tilde |
| ò | 242 | &ograve; | Latin small letter o with grave |
| ó | 243 | &oacute; | Latin small letter o with acute |
| ô | 244 | &ocirc; | Latin small letter o with circumflex |
| õ | 245 | &otilde; | Latin small letter o with tilde |
| ö | 246 | &ouml; | Latin small letter o with diaeresis |
| ÷ | 247 | &divide; | division sign |
| ø | 248 | &oslash; | Latin small letter o with stroke |
| ù | 249 | &ugrave; | Latin small letter u with grave |
| ú | 250 | &uacute; | Latin small letter u with acute |
| û | 251 | &ucirc; | Latin small letter u with circumflex |
| ü | 252 | &uuml; | Latin small letter u with diaeresis |
| ý | 253 | &yacute; | Latin small letter y with acute |
| þ | 254 | &thorn; | Latin small letter thorn |
| ÿ | 255 | &yuml; | Latin small letter y with diaeresis |

