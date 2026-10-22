代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xoebcstp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnzmwia.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfizzqx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoxvrxp.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnbncoy.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2arvuiotc.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblhdpg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgugietk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwujegv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjjidnm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gblhpmix.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2asgdvfkf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2drneerbr.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qustzctf.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzrkszg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xveaqpla.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkermvv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pzridqwm.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsuogm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbxjfjk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyptjsg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbzekpi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhulyokp.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dkarpjgb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsaxmds.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfuchkn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rxchiphs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2crwyagxv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcxntze.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2geprnfdn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cictaixr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zymblmav.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bebtygle.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjjhecm.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhybsbuo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcyrcht.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2luaddkks.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwvvjgp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2twdfjlqt.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2grjbuoby.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gt2srxfxznz.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tesgzsuc.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjytcdk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtndzrx.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2njqzlinf.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2friyccml.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2hymkiwig.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrdfmra.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2xbomnmog.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmkduf.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tydpgvef.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrleobs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmnsgrv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2yarpbxrk.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2onlsqjky.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjkoas.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2qysrhhpm.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2wzueqfbd.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmjkwsn.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wkghwvdd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omtnubqq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwtxpvf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liklsaoz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcsvvoi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2nftlsuhs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2domzwqnv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjclguug.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dklgtfzj.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrwqnrh.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmkfpfz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2hogtqnla.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gt2bdovxvhu.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nteyljwv.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxkgrz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxkwmaw.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lexqrgaw.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oppwjpjv.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqfjchv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2apbhtfgs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsnggwy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxlrgsh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2frskmfog.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2neuquich.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiiabhf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrletrv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2njdgocxt.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2qjunvffx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgvmdtm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsajwgij.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpzwbom.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhurpdv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2tqevubki.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fexmtojt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2mczxthaz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsbmjvr.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2brzersvx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrhxgif.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxdpizu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2joldlkdt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbujfiu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdyxddv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagcdsac.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2qftfyydn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cskxdthi.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2cctpaghp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2bivilhgf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2vouftgeh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmwfwbb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2fuilxdgj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2stngmhik.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vubhmowo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdweuez.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvsivci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzqhthe.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lfowjglj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwqahsk.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoqekuh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sghwjqec.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2furentph.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2omupwokn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbunwfru.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2balfdtsm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2foqaosha.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuanhxj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkkwafy.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2lefdkhtv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxlooql.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzblduo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdrxpxb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2jftwvbds.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxllaru.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyzsphq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaripmx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2iytaejve.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2lirjrykq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2itiygdrg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkjplfg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtyidyn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jseqxigd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuyamty.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbossnfq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2tezpuzgp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aotduqqf.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpawhkvd.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2utzunneq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jldvdqdu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pstoaain.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpdnjcs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qphwouml.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ippruren.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2yimjlrel.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznelrgf.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrhccer.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2pperguhj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfafgdd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjnutjk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvsukbe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqamnem.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmgjyvp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvribbfu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcsdmir.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2merrjkvd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyirpwxx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wismnfzq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udeolfta.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqmqgir.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kangykih.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyubxdm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiubkszo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgofqzs.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wbklmavt.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpexhhxf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbcsiqm.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgyvrvy.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrvvnsa.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxeiiqb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnbtfum.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obffalss.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qziyasxr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpvekbs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2paaofloe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2prdduwyy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmynjdy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjxqml.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqlwbah.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pingrezw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwgudzi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2onaghnqz.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhzwzvs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bpngidfz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bckfkdrd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjszpjk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cglihxco.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnzoghf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgcuxrm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2befmzfrt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmddpgay.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lefgydkm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmhqcqt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laobzeol.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2trsgdphh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2efkyzyhw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aplgehfn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eizmsgtg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvqmirp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjuwegn.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2skloekig.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhubuavg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpxouue.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fanpkwyu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ampnwxsz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgyxyvn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2grmqtglt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sehjftpb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqjvvzx.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iweraypb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2uztkawup.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kegqywrt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhwpbqs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwvrdnx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicdqhzb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkokoub.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oexxgwce.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnezlb.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2geqagjpg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2achbwody.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrbbmfd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfvamlo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtcfoim.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfybodb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2xewurnpa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxzujlw.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2omgxzieh.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpcbofy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzndore.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfjnauo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcojczim.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzalyjq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafhwxar.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmiihym.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnndlkbe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clkazidr.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2alhlevph.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2janyngul.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2inwboydi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmfqejy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2znvapbfi.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fafidroz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlfivpg.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fauggugp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qrstflom.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrordlq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hbspjhqg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2johujnhe.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvxxxmo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdgujdb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxnqavt.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhzowqp.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2skvkpcjw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbbhtaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmpmzzr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jsscungy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrmhxo.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thpkzhli.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwyormx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqlaftv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfleoser.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aadqkjad.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcspvwzn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkkuncz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydicfibz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdaoqq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2naekownj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ttksurhy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbmrzkj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxqvwni.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacpesn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwsjaae.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uywhhwlj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lciylkjl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rruwbsnx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoqpthp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjlnqqv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msgmkync.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epimebym.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqdljlw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpnajjz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccnstu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxosklfz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksausnjd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxklfly.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrphztw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alrytnov.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlmsbds.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hjumnjqf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfaxfk.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaewxrv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djryzrlm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpezteyv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzcgakt.html


<!-- 参考信息 -->