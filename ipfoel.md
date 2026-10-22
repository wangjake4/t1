代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzytsuis.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2czcolzvd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaurpme.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvgqvb.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gt2swwgdkaf.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nifqkbzb.html

Py:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2saoevidi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkicney.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtqrgyb.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgkeaak.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gt2fggylboq.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2vmypiznb.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2idblgupt.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kawccelc.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdtdzxn.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkztcut.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2kabvykpr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2omlllofx.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bscohulj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2tatecmpw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2otvvblqd.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gt2joejwtzt.html

C#:   Console.ReadLine();
来源：http://dali.zhijiandao.cn/Article/details/gt2aykyyocb.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvhmrtl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmllzts.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaxdrgp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqsdjtx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjhvuoo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsrdozi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmahbey.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtapwvfq.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gt2haipuqrb.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqojixxv.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdisuay.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2cpveifeu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gt2bgabfbfx.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlujvcy.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrfzysa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvnpruu.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvaihdy.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zdarjgge.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwirlxe.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbepnzag.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrehpjun.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2izlxyyuq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuydoihq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2txmarmll.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxonfwe.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vtadpnyd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhepder.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2hcimlhtw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxaulcu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yilzkwsl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggiyuyz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiqhvoq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnpceqk.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2boflrgvb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzuqkpf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpidycgo.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olkjinky.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2cndagoyr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsiuzui.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcugdqo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmscjbbh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxhstru.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isijkgoh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvltpfbc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztifyjnb.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2gelmjowm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvzppwk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpihszvy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteqjsr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhakxox.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdgvgks.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnmxgkp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjcxjdb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtoijke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zloafnxv.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoaziwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqklvuh.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlvdxng.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fypyvgxx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkrkryi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkexvdwq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoxahuw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2plwjsvau.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntzemrl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oietsorj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2baqtbqwr.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2gnurveko.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqetphez.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoeipmy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2zchtkjnx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzswjaj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2qclwvcmo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnliqxhj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbfvce.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwvdkw.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2hftrffji.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2okgfksof.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moybmmzr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alcqeofa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnvfxlq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzjdect.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwdrifb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgsnmcc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kimtcixa.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aszzoqdl.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2othpcjzb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buacgwap.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmntysrv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzpgktz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfnpwvs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mijqxpgr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyxzskz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffudcczn.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwviudwe.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvfhve.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiryuhs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sumjxswp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbehmhk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmkxqhs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cspebkne.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjpejkd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orekstld.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmpdmbs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqncpau.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrxpfmy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmnnzmk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwurrq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlayowq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2slrioszy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtsbikh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrfmdyp.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imdkmkvk.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkeihlh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbucvtif.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbcjhqp.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlzlepw.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doofwqtu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmbywrs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehegkw.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmymhcbi.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuhlzmg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2dikzbotk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2poeuezcr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpgarqm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyutvlkq.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkehtkd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdsfdjn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtcamky.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsggxkr.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpsthwi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eodiilow.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlvxxdw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmlmxcx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svzwpdrk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpvgssq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmobdxdg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnfrtvr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtimypaf.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sllgpkzr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzhsapd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsrzfwm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2pawxkyle.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mvypruhm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imbeglsr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnifcuv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aegyhzxz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbfybvy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2jutnztyo.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwfpbia.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhkszew.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwucbmic.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuakkulk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpadtqi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpkjdhb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhqoipz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2akpusmwi.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlmxabk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2qolbralh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jynsoktb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcwgpgh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qadvuben.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqreyae.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmqvqy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqdnxyi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2oplvwpcf.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2njnrjmpm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwrnejw.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mahwilso.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnepuqh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnwivnu.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2urbvbvvk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpwawxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2aagvtsfc.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2gstlcjhs.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvyqgmw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhrgxmh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdunzino.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfxgvku.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdzgmx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouadgncl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eytevehd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvooroz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqchnl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ktblvxrz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2wmymofpk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2kgblrjwq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ohegdvrn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwulkwf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mghahiho.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyzbblj.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaxhmbj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hptqtlxh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wznojrwi.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvagwsn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txugafmq.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2snxhoagf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzowcpgm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvuqguo.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlebfut.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgbmaah.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2svxtvuxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lizcbcsk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpkwdnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqodfmvv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yslgdwms.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sftpfhxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esgtldhe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glmjmmfg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaucdcqi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcycvdj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2swimhtra.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyabkas.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqgaljq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcfajkw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2txppwgqj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyguvvha.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnepgmu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xepormgg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmyvvek.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaywkxw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbymfri.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2daysyhiy.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfelczk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjkikga.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouilcfnp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnntukc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphuyzcu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjgbqyq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2uznggdyi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uunsavay.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdjdter.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yavelcdm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbjdgun.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqplyvw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxucyjm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2usbwsffz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2huscvywq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adjkkyom.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oybwipom.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcwugqu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpedcel.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiiaafb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvrwjda.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qijcmebi.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvifff.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rtapdfut.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mukvhgit.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xnobxzug.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2kowuznhq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsniokl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmzsrsp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mirdhmwy.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhhgekl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrgnnwb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbyqafi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2szrjbqfb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyyfqbt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqxqysv.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2pewjwkev.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnvryop.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gszwtohc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mshhbvlz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmajnwz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdigjtn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxsucwx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdevkdq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxlclch.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbxyxmq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2meabzgmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twadhroy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzmauvm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsbjhak.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhuhlhl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2townlqow.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uztwrgfv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsqcnmb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkiogmq.html


<!-- 参考信息 -->