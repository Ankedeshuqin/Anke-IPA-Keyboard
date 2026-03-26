# 安可IPA键盘（Anke IPA Keyboard）

[查看HTML版说明](https://ankedeshuqin.github.io/Anke-IPA-Keyboard/)

## 总述

- 使用Microsoft Keyboard Layout（MSKLC）创建。
- 可输入：
  - 标准与常用非标准或扩展IPA字母；
  - 标准与常用非标准或扩展IPA符号；
  - 常用上标IPA字母；
  - 其他常用拉丁、希腊、西里尔字母；
  - 其他常用符号。
  
  （具体输入方式见后表。）
- 当<kbd>AltGr</kbd>键未按下时，可作为一般的美式键盘使用；而<kbd>AltGr</kbd>+字母键<kbd>a</kbd>\~<kbd>z</kbd>均为dead key，通过按下<kbd>AltGr</kbd>+字母键后再按下第二个键来输入与之相关的其他IPA字母（通常，用作dead key的字母键表示（字理上的）字形来源，而第二个键通常起到描述性的作用，如卷舌鼻音ɳ通过dead key <kbd>AltGr</kbd>+<kbd>n</kbd>与表示卷舌的<kbd>r</kbd>键输入；部分第二个键亦需按住<kbd>Shift</kbd>键来输入）。特别地，dead key <kbd>AltGr</kbd>+<kbd>/</kbd>用于输入喉塞音以及与之相关的IPA字母，<kbd>AltGr</kbd>+<kbd>\\</kbd>用于输入搭嘴音字母。
- 按下<kbd>AltGr</kbd>+字母键（<kbd>q</kbd>除外）后按下空格键可输入其对应的上标字母；部分其他上标IPA字母则通过按下<kbd>AltGr</kbd>+<kbd>Shift</kbd>+字母键后再按下第二个键来输入，此时按下的第二个键与输入对应的非上标IPA字母时的相同。（另外，按下<kbd>AltGr</kbd>+<kbd>Shift</kbd>+字母键后按下空格键也可输入其对应的上标字母。）
- Dead key <kbd>AltGr</kbd>+<kbd>.</kbd>用于输入IPA符号。
- Dead key <kbd>AltGr</kbd>+<kbd>`</kbd>、<kbd>'</kbd>、<kbd>^</kbd>、<kbd>~</kbd>、<kbd>"</kbd>、<kbd>-</kbd>、<kbd>=</kbd>、<kbd>;</kbd>、<kbd>_</kbd>、<kbd>></kbd>、<kbd><</kbd>、<kbd>:</kbd>、<kbd>[</kbd>、<kbd>]</kbd>用于输入常用拉丁、希腊、西里尔字母。
- Dead key <kbd>AltGr</kbd>+<kbd>+</kbd>用于输入其他常用符号。
- 由于MSKLC不支持使用第零平面（基本多文种平面；BMP）以外的字符，所以位于第零平面以外的字母或符号均不可输入。
- 键盘布局（美式键盘；<mark>高亮</mark>的为当<kbd>AltGr</kbd>键按下时的dead key）：
  <table>
    <tr align="center">
      <td colspan="2"><mark>~</mark><br><mark>`</mark></td><td colspan="2">!<br>1</td><td colspan="2">@<br>2</td><td colspan="2">#<br>3</td><td colspan="2">$<br>4</td><td colspan="2">%<br>5</td><td colspan="2"><mark>^</mark><br>6</td><td colspan="2">&amp;<br>7</td><td colspan="2">*<br>8</td><td colspan="2">(<br>9</td><td colspan="2">)<br>0</td><td colspan="2"><mark>_</mark><br><mark>-</mark></td><td colspan="2"><mark>+</mark><br><mark>=</mark></td><td colspan="2" align="right">Backspace</td>
    </tr>
    <tr align="center">
      <td colspan="3" align="left">Tab</td><td colspan="2"><mark>Q</mark><br><mark>q</mark></td><td colspan="2"><mark>W</mark><br><mark>w</mark></td><td colspan="2"><mark>E</mark><br><mark>e</mark></td><td colspan="2"><mark>R</mark><br><mark>r</mark></td><td colspan="2"><mark>T</mark><br><mark>t</mark></td><td colspan="2"><mark>Y</mark><br><mark>y</mark></td><td colspan="2"><mark>U</mark><br><mark>u</mark></td><td colspan="2"><mark>I</mark><br><mark>i</mark></td><td colspan="2"><mark>O</mark><br><mark>o</mark></td><td colspan="2"><mark>P</mark><br><mark>p</mark></td><td colspan="2">{<br><mark>[</mark></td><td colspan="2">}<br><mark>]</mark></td><td colspan="2"><mark>|</mark><br><mark>\</mark></td>
    </tr>
    <tr align="center">
      <td colspan="4" align="left">Caps Lock</td><td colspan="2"><mark>A</mark><br><mark>a</mark></td><td colspan="2"><mark>S</mark><br><mark>s</mark></td><td colspan="2"><mark>D</mark><br><mark>d</mark></td><td colspan="2"><mark>F</mark><br><mark>f</mark></td><td colspan="2"><mark>G</mark><br><mark>g</mark></td><td colspan="2"><mark>H</mark><br><mark>h</mark></td><td colspan="2"><mark>J</mark><br><mark>j</mark></td><td colspan="2"><mark>K</mark><br><mark>k</mark></td><td colspan="2"><mark>L</mark><br><mark>l</mark></td><td colspan="2"><mark>:</mark><br><mark>;</mark></td><td colspan="2"><mark>"</mark><br><mark>'</mark></td><td colspan="2" align="right">Enter</td>
    </tr>
    <tr align="center">
      <td colspan="5" align="left">Shift</td><td colspan="2"><mark>Z</mark><br><mark>z</mark></td><td colspan="2"><mark>X</mark><br><mark>x</mark></td><td colspan="2"><mark>C</mark><br><mark>c</mark></td><td colspan="2"><mark>V</mark><br><mark>v</mark></td><td colspan="2"><mark>B</mark><br><mark>b</mark></td><td colspan="2"><mark>N</mark><br><mark>n</mark></td><td colspan="2"><mark>M</mark><br><mark>m</mark></td><td colspan="2"><mark><</mark><br>,</td><td colspan="2"><mark>></mark><br><mark>.</mark></td><td colspan="2"><mark>?</mark><br><mark>/</mark></td><td colspan="3" align="right">Shift</td>
    </tr>
  </table>
  
- 压缩包“ankeipa.zip”内为MSKLC生成的安装程序。解压并运行“setup.exe”安装后，从输入法列表中选择“Anke IPA Keyboard”就可以使用了。

## IPA字母

- 对于需要通过dead key输入的IPA字母，上面一行表示输入方式（按住<kbd>AltGr</kbd>输入第一个字符（dead character），然后输入第二个字符；后同），下面一行表示所输入的字母。
- 标准IPA字母：
  
  **辅音（肺部气流）**

  <table>
    <tr align="center">
      <th></th><th colspan="2">双唇</th><th colspan="2">唇齿</th><th colspan="2">齿</th><th colspan="2">齿龈</th><th colspan="2">龈后</th><th colspan="2">卷舌</th><th colspan="2">硬腭</th><th colspan="2">软腭</th><th colspan="2">小舌</th><th colspan="2">咽</th><th colspan="2">喉</th>
    </tr>
    <tr align="center">
      <th align="left">塞音</td><td><br>p</td><td><br>b</td><td colspan="2"></td><td colspan="2"></td><td><br>t</td><td><br>d</td><td colspan="2"></td><td>tr<br>ʈ</td><td>dr<br>ɖ</td><td><br>c</td><td>jj<br>ɟ</td><td><br>k</td><td>gg<br>ɡ</td><td><br>q</td><td>gq<br>ɢ</td><td></td><td>-</td><td>//<br>ʔ</td><td>-</td>
    </tr>
    <tr align="center">
      <th align="left">鼻音</td><td></td><td><br>m</td><td></td><td>mv<br>ɱ</td><td colspan="2"></td><td></td><td><br>n</td><td colspan="2"></td><td></td><td>nr<br>ɳ</td><td></td><td>nj<br>ɲ</td><td></td><td>ng<br>ŋ</td><td></td><td>nq<br>ɴ</td><td colspan="2">-</td><td colspan="2">-</td>
    </tr>
    <tr align="center">
      <th align="left">颤音</td><td></td><td>br<br>ʙ</td><td colspan="2"></td><td colspan="2"></td><td></td><td><br>r</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2">-</td><td></td><td>rq<br>ʀ</td><td colspan="2"></td><td colspan="2">-</td>
    </tr>
    <tr align="center">
      <th align="left">拍&zwj;音&zwj;或&zwj;闪&zwj;音</td><td colspan="2"></td><td></td><td>vb<br>ⱱ</td><td colspan="2"></td><td></td><td>rd<br>ɾ</td><td colspan="2"></td><td></td><td>rD<br>ɽ</td><td colspan="2"></td><td colspan="2">-</td><td colspan="2"></td><td colspan="2"></td><td colspan="2">-</td>
    </tr>
    <tr align="center">
      <th align="left">擦音</td><td>ph<br>ɸ</td><td>bh<br>β</td><td><br>f</td><td><br>v</td><td>th<br>θ</td><td>dh<br>ð</td><td><br>s</td><td><br>z</td><td>ss<br>ʃ</td><td>zz<br>ʒ</td><td>sr<br>ʂ</td><td>zr<br>ʐ</td><td>ch<br>ç</td><td>jh<br>ʝ</td><td><br>x</td><td>gh<br>ɣ</td><td>xq<br>χ</td><td>rh<br>ʁ</td><td>h/<br>ħ</td><td>/h<br>ʕ</td><td><br>h</td><td>hh<br>ɦ</td>
    </tr>
    <tr align="center">
      <th align="left">边擦音</td><td colspan="2">-</td><td colspan="2">-</td><td colspan="2"></td><td>ls<br>ɬ</td><td>lz<br>ɮ</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2">-</td><td colspan="2">-</td>
    </tr>
    <tr align="center">
      <th align="left">近音</td><td colspan="2"></td><td></td><td>vv<br>ʋ</td><td colspan="2"></td><td></td><td>rr<br>ɹ</td><td colspan="2"></td><td></td><td>rR<br>ɻ</td><td></td><td><br>j</td><td></td><td>wj<br>ɰ</td><td colspan="2"></td><td colspan="2"></td><td colspan="2">-</td>
    </tr>
    <tr align="center">
      <th align="left">边近音</td><td colspan="2">-</td><td colspan="2">-</td><td colspan="2"></td><td></td><td><br>l</td><td colspan="2"></td><td></td><td>lr<br>ɭ</td><td></td><td>lj<br>ʎ</td><td></td><td>lg<br>ʟ</td><td colspan="2"></td><td colspan="2">-</td><td colspan="2">-</td>
    </tr>
  </table>

  **辅音（非肺部气流）**

  <table>
    <tr>
      <th colspan="2">搭嘴音</th><th colspan="2">浊内爆音</th>
    </tr>
    <tr>
      <td align="center">\o<br>ʘ</td><td>双唇音</td><td align="center">b\<br>ɓ</td><td>双唇音</td>
    </tr>
    <tr>
      <td align="center">\\<br>ǀ</td><td>齿音</td><td align="center">d\<br>ɗ</td><td>齿音/龈音</td>
    </tr>
    <tr>
      <td align="center">\!<br>ǃ</td><td>龈（后）音</td><td align="center">d|<br>ᶑ</td><td>卷舌音</td>
    </tr>
    <tr>
      <td align="center">\=<br>ǂ</td><td>腭龈音</td><td align="center">j\<br>ʄ</td><td>硬腭音</td>
    </tr>
    <tr>
      <td align="center">\|<br>ǁ</td><td>龈边音</td><td align="center">g\<br>ɠ</td><td>软腭音</td>
    </tr>
    <tr>
      <td colspan="2"></td><td align="center">g|<br>ʛ</td><td>小舌音</td>
    </tr>
  </table>

  **其他符号**

  <table>
    <tr>
      <td align="center">wh<br>ʍ</td><td>清唇-软腭擦音</td><td align="center">cj<br>ɕ</td><td align="center">zj<br>ʑ</td><td>龈-腭擦音</td>
    </tr>
    <tr>
      <td align="center"><br>w</td><td>浊唇-软腭近音</td><td></td><td align="center">rl<br>ɺ</td><td>浊龈边闪音</td>
    </tr>
    <tr>
      <td align="center">jw<br>ɥ</td><td>浊唇-硬腭近音</td><td align="center">sj<br>ɧ</td><td></td><td>同时发ʃ和x</td>
    </tr>
    <tr>
      <td align="center">h?<br>ʜ</td><td>清会厌擦音</td>
    </tr>
    <tr>
      <td align="center">/H<br>ʢ</td><td>浊会厌擦音</td>
    </tr>
    <tr>
      <td align="center">/?<br>ʡ</td><td>会厌塞音</td>
    </tr>
  </table>

  **元音**

  <table>
    <tr>
      <th></th><th colspan="8">前</th><th colspan="16"></th><th colspan="8">央</th><th colspan="16"></th><th colspan="8">后</th>
    </tr>
    <tr align="center">
      <th align="left">闭</th><td colspan="4"><br>i</td><td colspan="4"><br>y</td><td colspan="16">----</td><td colspan="4">iu<br>ɨ</td><td colspan="4">uy<br>ʉ</td><td colspan="16">----</td><td colspan="4">ui<br>ɯ</td><td colspan="4"><br>u</td>
    </tr>
    <tr align="center">
      <td></td><td colspan="15">\&nbsp;&nbsp;<br>&nbsp;&nbsp;\</td><td colspan="4">ii<br>ɪ</td><td colspan="4">yy<br>ʏ</td><td colspan="14">\&nbsp;<br>&nbsp;\</td><td colspan="4"></td><td colspan="4">uu<br>ʊ</td><td colspan="3"></td><td colspan="8">|<br>|</td>
    </tr>
    <tr align="center">
      <th align="left">半闭</th><td colspan="8"></td><td colspan="4"><br>e</td><td colspan="4">oy<br>ø</td><td colspan="12">----</td><td colspan="4">eU<br>ɘ</td><td colspan="4">oY<br>ɵ</td><td colspan="12">----</td><td colspan="4">eu<br>ɤ</td><td colspan="4"><br>o</td>
    </tr>
    <tr align="center">
      <td></td><td colspan="30">\&nbsp;&nbsp;<br>&nbsp;&nbsp;\</td><td colspan="4">ee<br>ə</td><td colspan="4"></td><td colspan="10"></td><td colspan="8">|<br>|</td>
    </tr>
    <tr align="center">
      <th align="left">半开</th><td colspan="16"></td><td colspan="4">ea<br>ɛ</td><td colspan="4">oe<br>œ</td><td colspan="8">----</td><td colspan="4">eA<br>ɜ</td><td colspan="4">oA<br>ɞ</td><td colspan="8">----</td><td colspan="4">au<br>ʌ</td><td colspan="4">oa<br>ɔ</td>
    </tr>
    <tr align="center">
      <td></td><td colspan="20"></td><td colspan="4">ae<br>æ</td><td colspan="4"></td><td colspan="6"></td><td colspan="4">aE<br>ɐ</td><td colspan="4"></td><td colspan="6"></td><td colspan="8">|<br>|</td>
    </tr>
    <tr align="center">
      <th align="left">开</th><td colspan="24"></td><td colspan="4"><br>a</td><td colspan="4">oE<br>ɶ</td><td colspan="16">----</td><td colspan="4">aa<br>ɑ</td><td colspan="4">ao<br>ɒ</td>
    </tr>
  </table>
- 其他/非标准或扩展IPA字母：
  <table>
    <tr align="center">
      <td><br>g</td><td>er<br>ɚ</td><td>eR<br>ɝ</td><td>ll<br>ɫ</td><td>dJ<br>ȡ</td><td>tJ<br>ȶ</td><td>nJ<br>ȵ</td><td>lJ<br>ȴ</td><td>ir<br>ɿ</td><td>iR<br>ʅ</td><td>yr<br>ʮ</td><td>yR<br>ʯ</td><td>aA<br>ᴀ</td><td>eE<br>ᴇ</td><td>oO<br>ꭥ</td><td>iI<br>ɩ</td><td>ou<br>ɷ</td><td>oU<br>ω</td><td>bb<br>ȸ</td><td>pp<br>ȹ</td><td>iU<br>ᵻ</td><td>uY<br>ᵿ</td><td>p\<br>ƥ</td><td>t\<br>ƭ</td><td>c\<br>ƈ</td><td>k\<br>ƙ</td><td>q\<br>ʠ</td><td>t|<br>ʇ</td><td>c|<br>ʗ</td><td>k|<br>ʞ</td><td>eO<br>ⱻ</td><td>lS<br>ꞎ</td><td>yu<br>ɏ</td><td>rH<br>ɼ</td><td>ts<br>ʦ</td><td>dz<br>ʣ</td><td>tS<br>ʧ</td><td>dZ<br>ʤ</td><td>tc<br>ʨ</td><td>dj<br>ʥ</td><td>fn<br>ʩ</td><td>qq<br>ꞯ</td><td>ww<br>ʬ</td><td>dd<br>ʭ</td>
    </tr>
  </table>

## IPA符号

- 按下dead key<kbd>AltGr</kbd>+<kbd>.</kbd>后，按下键盘上不同的键分别可输入的IPA符号的布局（<mark>高亮</mark>的为非标准或扩展IPA符号）：
  <table>
    <tr align="center">
      <td colspan="2">◌̂<br>◌̌</td><td colspan="2">◌̏<br>˩</td><td colspan="2">◌̀<br>˨</td><td colspan="2">◌̄<br>˧</td><td colspan="2">◌́<br>˦</td><td colspan="2">◌̋<br>˥</td><td colspan="2">◌᷇<br>◌᷄</td><td colspan="2">◌᷆<br>◌᷅</td><td colspan="2">◌᷉<br>◌᷈</td><td colspan="2">◌͑<br>◌̜</td><td colspan="2">◌͗<br>◌̹</td><td colspan="2">◌˗<br>◌̠</td><td colspan="2">◌˖<br>◌̟</td><td colspan="2" align="right">Backspace</td>
    </tr>
    <tr align="center">
      <td colspan="3" align="left">Tab</td><td colspan="2"></td><td colspan="2"><mark>◌͎</mark><br><mark>◌̫</mark></td><td colspan="2"></td><td colspan="2"><mark>◌̢</mark><br>◌˞</td><td colspan="2"><mark>◌͉</mark><br><mark>◌͈</mark></td><td colspan="2"></td><td colspan="2">◌͜<br>◌͡</td><td colspan="2">◌̍<br>◌̩</td><td colspan="2">◌̊<br>◌̥</td><td colspan="2"></td><td colspan="2">◌˕<br>◌̞</td><td colspan="2">◌˔<br>◌̝</td><td colspan="2">‖<br>ʼ</td>
    </tr>
    <tr align="center">
      <td colspan="4" align="left">Caps Lock</td><td colspan="2"><mark>◌͇</mark><br>◌̺</td><td colspan="2">ꜛ<br>ꜜ</td><td colspan="2"><mark>◌͆</mark><br>◌̪</td><td colspan="2"></td><td colspan="2">↘<br>↗</td><td colspan="2"><mark>↑</mark><br><mark>↓</mark></td><td colspan="2">◌̑<br>◌̯</td><td colspan="2"></td><td colspan="2">◌̚<br>◌̻</td><td colspan="2">ː<br>ˑ</td><td colspan="2">◌̈<br>ˈ</td><td colspan="3" align="right">Enter</td>
    </tr>
    <tr align="center">
      <td colspan="5" align="left">Shift</td><td colspan="2"></td><td colspan="2"><br>◌̽</td><td colspan="2"><mark>◌̡</mark><br>◌̰</td><td colspan="2">◌̆<br>◌̬</td><td colspan="2"><br>◌̤</td><td colspan="2"><mark>◌͊</mark><br>◌̃</td><td colspan="2"><mark>◌͍</mark><br>◌̼</td><td colspan="2">◌̘<br>ˌ</td><td colspan="2">◌̙<br>‿</td><td colspan="2"><mark>˭</mark><br>◌̴</td><td colspan="3" align="right">Shift</td>
    </tr>
  </table>

## 其他常用字母

- 拉丁字母
  - 上面一行表示输入方式，下面一行表示所输入的字母。
  - Dead key：<kbd>AltGr</kbd>+<kbd>\`</kbd>（grave）
    <table>
      <tr align="center">
        <td>`A<br>À</td><td>`E<br>È</td><td>`I<br>Ì</td><td>`O<br>Ò</td><td>`U<br>Ù</td><td>`a<br>à</td><td>`e<br>è</td><td>`i<br>ì</td><td>`o<br>ò</td><td>`u<br>ù</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>'</kbd>（acute）
    <table>
      <tr align="center">
        <td>'A<br>Á</td><td>'E<br>É</td><td>'I<br>Í</td><td>'O<br>Ó</td><td>'U<br>Ú</td><td>'Y<br>Ý</td><td>'a<br>á</td><td>'e<br>é</td><td>'i<br>í</td><td>'o<br>ó</td><td>'u<br>ú</td><td>'y<br>ý</td><td>'C<br>Ć</td><td>'c<br>ć</td><td>'L<br>Ĺ</td><td>'l<br>ĺ</td><td>'N<br>Ń</td><td>'n<br>ń</td><td>'R<br>Ŕ</td><td>'r<br>ŕ</td><td>'S<br>Ś</td><td>'s<br>ś</td><td>'Z<br>Ź</td><td>'z<br>ź</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>^</kbd>（circumflex）
    <table>
      <tr align="center">
        <td>^A<br>Â</td><td>^E<br>Ê</td><td>^I<br>Î</td><td>^O<br>Ô</td><td>^U<br>Û</td><td>^a<br>â</td><td>^e<br>ê</td><td>^i<br>î</td><td>^o<br>ô</td><td>^u<br>û</td><td>^C<br>Ĉ</td><td>^c<br>ĉ</td><td>^G<br>Ĝ</td><td>^g<br>ĝ</td><td>^H<br>Ĥ</td><td>^h<br>ĥ</td><td>^J<br>Ĵ</td><td>^j<br>ĵ</td><td>^S<br>Ŝ</td><td>^s<br>ŝ</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>~</kbd>（tilde）
    <table>
      <tr align="center">
        <td>~A<br>Ã</td><td>~N<br>Ñ</td><td>~O<br>Õ</td><td>~a<br>ã</td><td>~n<br>ñ</td><td>~o<br>õ</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>"</kbd>（diaeresis）
    <table>
      <tr align="center">
        <td>"A<br>Ä</td><td>"E<br>Ë</td><td>"I<br>Ï</td><td>"O<br>Ö</td><td>"U<br>Ü</td><td>"a<br>ä</td><td>"e<br>ë</td><td>"i<br>ï</td><td>"o<br>ö</td><td>"u<br>ü</td><td>"y<br>ÿ</td><td>"Y<br>Ÿ</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>-</kbd>（ring、stroke、特殊字母）
    <table>
      <tr align="center">
        <td>-A<br>Å</td><td>-D<br>Ð</td><td>-O<br>Ø</td><td>-T<br>Þ</td><td>-a<br>å</td><td>-d<br>ð</td><td>-o<br>ø</td><td>-t<br>þ</td><td>-L<br>Ł</td><td>-l<br>ł</td><td>-U<br>Ů</td><td>-u<br>ů</td><td>-s<br>ſ</td><td>-Y<br>Ȝ</td><td>-y<br>ȝ</td><td>-W<br>Ƿ</td><td>-w<br>ƿ</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>=</kbd>（合字）
    <table>
      <tr align="center">
        <td>=A<br>Æ</td><td>=s<br>ß</td><td>=a<br>æ</td><td>=O<br>Œ</td><td>=o<br>œ</td><td>=S<br>ẞ</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>;</kbd>（cedilla、breve）
    <table>
      <tr align="center">
        <td>;C<br>Ç</td><td>;c<br>ç</td><td>;A<br>Ă</td><td>;a<br>ă</td><td>;G<br>Ğ</td><td>;g<br>ğ</td><td>;S<br>Ş</td><td>;s<br>ş</td><td>;T<br>Ţ</td><td>;t<br>ţ</td><td>;U<br>Ŭ</td><td>;u<br>ŭ</td>
      </tr>
    </table>
      
  - Dead key：<kbd>AltGr</kbd>+<kbd>_</kbd>（macron）
    <table>
      <tr align="center">
        <td>_A<br>Ā</td><td>_a<br>ā</td><td>_E<br>Ē</td><td>_e<br>ē</td><td>_I<br>Ī</td><td>_i<br>ī</td><td>_O<br>Ō</td><td>_o<br>ō</td><td>_U<br>Ū</td><td>_u<br>ū</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>></kbd>（ogonek、dot）
    <table>
      <tr align="center">
        <td>>A<br>Ą</td><td>>a<br>ą</td><td>>E<br>Ę</td><td>>e<br>ę</td><td>>I<br>İ</td><td>>i<br>ı</td><td>>Z<br>Ż</td><td>>z<br>ż</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd><</kbd>（caron）
    <table>
      <tr align="center">
        <td>&lt;C<br>Č</td><td>&lt;c<br>č</td><td>&lt;D<br>Ď</td><td>&lt;d<br>ď</td><td>&lt;E<br>Ě</td><td>&lt;e<br>ě</td><td>&lt;L<br>Ľ</td><td>&lt;l<br>ľ</td><td>&lt;N<br>Ň</td><td>&lt;n<br>ň</td><td>&lt;R<br>Ř</td><td>&lt;r<br>ř</td><td>&lt;S<br>Š</td><td>&lt;s<br>š</td><td>&lt;T<br>Ť</td><td>&lt;t<br>ť</td><td>&lt;Z<br>Ž</td><td>&lt;z<br>ž</td>
      </tr>
    </table>
  - Dead key：<kbd>AltGr</kbd>+<kbd>:</kbd>（double acute、comma）
    <table>
      <tr align="center">
        <td>:O<br>Ő</td><td>:o<br>ő</td><td>:U<br>Ű</td><td>:u<br>ű</td><td>:S<br>Ș</td><td>:s<br>ș</td><td>:T<br>Ț</td><td>:t<br>ț</td>
      </tr>
    </table>
- 希腊字母
  - 按下dead key <kbd>AltGr</kbd>+<kbd>[</kbd>后，按下键盘上不同的键分别可输入的希腊字母的布局：
    <table>
      <tr align="center">
        <td colspan="2">Ϻ<br>ϻ</td><td colspan="2">Ά<br>ά</td><td colspan="2">Έ<br>έ</td><td colspan="2">Ή<br>ή</td><td colspan="2">Ί<br>ί</td><td colspan="2">Ό<br>ό</td><td colspan="2">Ύ<br>ύ</td><td colspan="2">Ώ<br>ώ</td><td colspan="2">Ϊ<br>ϊ</td><td colspan="2">Ϋ<br>ϋ</td><td colspan="2"><br>ς</td><td colspan="2"><br>ΐ</td><td colspan="2"><br>ΰ</td><td colspan="2" align="right">Backspace</td>
      </tr>
      <tr align="center">
        <td colspan="3" align="left">Tab</td><td colspan="2">Ϙ<br>ϙ</td><td colspan="2">Ϝ<br>ϝ</td><td colspan="2">Ε<br>ε</td><td colspan="2">Ρ<br>ρ</td><td colspan="2">Τ<br>τ</td><td colspan="2">Υ<br>υ</td><td colspan="2">Ω<br>ω</td><td colspan="2">Ι<br>ι</td><td colspan="2">Ο<br>ο</td><td colspan="2">Π<br>π</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td>
      </tr>
      <tr align="center">
        <td colspan="4" align="left">Caps Lock</td><td colspan="2">Α<br>α</td><td colspan="2">Σ<br>σ</td><td colspan="2">Δ<br>δ</td><td colspan="2">Φ<br>φ</td><td colspan="2">Γ<br>γ</td><td colspan="2">Η<br>η</td><td colspan="2">Ψ<br>ψ</td><td colspan="2">Κ<br>κ</td><td colspan="2">Λ<br>λ</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" align="right">Enter</td>
      </tr>
      <tr align="center">
        <td colspan="5" align="left">Shift</td><td colspan="2">Ζ<br>ζ</td><td colspan="2">Ξ<br>ξ</td><td colspan="2">Χ<br>χ</td><td colspan="2">Θ<br>θ</td><td colspan="2">Β<br>β</td><td colspan="2">Ν<br>ν</td><td colspan="2">Μ<br>μ</td><td colspan="2"></td><td colspan="2"></td><td colspan="2">;<br>&nbsp;</td><td colspan="3" align="right">Shift</td>
      </tr>
    </table>
- 西里尔字母
  - 按下dead key <kbd>AltGr</kbd>+<kbd>]</kbd>后，按下键盘上不同的键分别可输入的西里尔字母的布局：
    <table>
      <tr align="center">
        <td colspan="2"></td><td colspan="2">Ш<br>ш</td><td colspan="2">Щ<br>щ</td><td colspan="2">Ъ<br>ъ</td><td colspan="2">Ь<br>ь</td><td colspan="2">Э<br>э</td><td colspan="2">Ю<br>ю</td><td colspan="2">Я<br>я</td><td colspan="2">І<br>і</td><td colspan="2">Ї<br>ї</td><td colspan="2">Ё<br>ё</td><td colspan="2">Є<br>є</td><td colspan="2">Ґ<br>ґ</td><td colspan="2" align="right">Backspace</td>
      </tr>
      <tr align="center">
        <td colspan="3" align="left">Tab</td><td colspan="2">Ч<br>ч</td><td colspan="2">Ў<br>ў</td><td colspan="2">Е<br>е</td><td colspan="2">Р<br>р</td><td colspan="2">Т<br>т</td><td colspan="2">Ы<br>ы</td><td colspan="2">У<br>у</td><td colspan="2">И<br>и</td><td colspan="2">О<br>о</td><td colspan="2">П<br>п</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td>
      </tr>
      <tr align="center">
        <td colspan="4" align="left">Caps Lock</td><td colspan="2">А<br>а</td><td colspan="2">С<br>с</td><td colspan="2">Д<br>д</td><td colspan="2">Ф<br>ф</td><td colspan="2">Г<br>г</td><td colspan="2">Х<br>х</td><td colspan="2">Й<br>й</td><td colspan="2">К<br>к</td><td colspan="2">Л<br>л</td><td colspan="2"></td><td colspan="2"></td><td colspan="2" align="right">Enter</td>
      </tr>
      <tr align="center">
        <td colspan="5" align="left">Shift</td><td colspan="2">З<br>з</td><td colspan="2">Ж<br>ж</td><td colspan="2">Ц<br>ц</td><td colspan="2">В<br>в</td><td colspan="2">Б<br>б</td><td colspan="2">Н<br>н</td><td colspan="2">М<br>м</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="3" align="right">Shift</td>
      </tr>
    </table>

## 其他符号

- 按下dead key <kbd>AltGr</kbd>+<kbd>+</kbd>后，按下键盘上不同的键分别可输入的其他符号的布局：
  <table>
    <tr align="center">
      <td colspan="2">¬<br>·</td><td colspan="2">¡<br>¹</td><td colspan="2">¶<br>²</td><td colspan="2">§<br>³</td><td colspan="2">¤<br>⁴</td><td colspan="2">‰<br>⁵</td><td colspan="2">°<br>⁶</td><td colspan="2">¼<br>⁷</td><td colspan="2">×<br>⁸</td><td colspan="2">½<br>⁹</td><td colspan="2">¾<br>⁰</td><td colspan="2">¯<br>±</td><td colspan="2">≠<br>≈</td><td colspan="2" align="right">Backspace</td>
    </tr>
    <tr align="center">
      <td colspan="3" align="left">Tab</td><td colspan="2"></td><td colspan="2">₩<br>&nbsp;</td><td colspan="2">€<br>&nbsp;</td><td colspan="2">₽<br>®</td><td colspan="2"><br>™</td><td colspan="2">¥<br>&nbsp;</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"><br>º</td><td colspan="2"></td><td colspan="2"><br>⟨</td><td colspan="2"><br>⟩</td><td colspan="2">¦<br>∅</td>
    </tr>
    <tr align="center">
      <td colspan="4" align="left">Caps Lock</td><td colspan="2"><br>ª</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2">£<br>&nbsp;</td><td colspan="2"><br>¸</td><td colspan="2">¨<br>´</td><td colspan="2" align="right">Enter</td>
    </tr>
    <tr align="center">
      <td colspan="5" align="left">Shift</td><td colspan="2"></td><td colspan="2"></td><td colspan="2">¢<br>©</td><td colspan="2"></td><td colspan="2"></td><td colspan="2"></td><td colspan="2"><br>µ</td><td colspan="2">«<br>&nbsp;</td><td colspan="2">»<br>◌</td><td colspan="2">¿<br>÷</td><td colspan="3" align="right">Shift</td>
    </tr>
  </table>
