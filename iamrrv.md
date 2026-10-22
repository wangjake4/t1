代发 wailian999

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjjrequ.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmcuhcr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbhlycb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnonixde.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsemmdfv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsckmzhp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfotkvl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryybxszf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2owubpkyt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gt2xawkqslb.html

[A24] 去除首尾空白
来源：http://dali.zhijiandao.cn/Article/details/gt2gclvdlph.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhbhkkx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqnztqn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwanitwm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2akboyqic.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gt2aghsntqy.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeyzocz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvgiolw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvryumt.html

[A25] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lidlaxwu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwsvdqi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwzkhpf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeayshl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rplefubq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvhtxwp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzmqlzz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrvryhf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyrdbhe.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2snfnjsbo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdwlmhc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgumztb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbunjiqw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gt2bstvilre.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2nllivzfh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrxmptu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ofalomfv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcydmpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkygpui.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2svikoziw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzynkssp.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbqfwgq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2khvpvuga.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkmkoh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxcnzkp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpucqelv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2srnvnfsm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cevxtrcn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrlxrjr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2amhtuqva.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gt2thhtbtio.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2eputdody.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwafftwm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwbefmh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjedhoja.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqboypwj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrmbgcp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2lovevsbz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzndgze.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhkpiix.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwwqciv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzudymng.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqncqwny.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwacrgb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oafwybnu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvoujcu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gt2skifqbmg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbairiyz.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqwdwgc.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbrmekw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwsyhir.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thlusdap.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giboljfy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtwydya.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjddwpo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikavunwn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptcezsv.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcowfro.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvskyqom.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbvfafj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofarykgj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxyfdb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxibrgri.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrwihhk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffozkwf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrxawbq.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuzijds.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizsyznr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhbnsao.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlafcdog.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vksmgkod.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwoiqsb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2figxvuwr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlbsohk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvldydq.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdbkxlm.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyjtanl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtuyyxo.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjolkbj.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kduygoba.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwsxray.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2piocobiy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoxsexv.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhaatxy.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwehvnnh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2oihbwtfl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhbwntm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2htnahhfx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjcspak.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaffueda.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqybic.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyutsnl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsdbddh.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2rtenwjen.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xhifegdh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqtrhe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpofiyc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrmnmpf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkiurpx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrlqaii.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abxchqgt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2katsjoud.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ffibwqam.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowjfost.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxowqrx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2idcsyxyl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2imtwttur.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhuhjtf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umuqwdis.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2remrkeld.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2payvnsfo.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2nyltnynw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kngcqgiq.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xisoqjab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgllqaz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmfciiq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyjlwgd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyqtvvn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtdlbmm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexxpjkj.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhfehd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2fedotxlg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoxvlzt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeveowi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyjwbes.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsavfvy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esybbpsv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xopwglaw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhizdvm.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdynne.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2urgxyros.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcmniav.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnidxav.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvtisos.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2leixbqwh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmtkkob.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkizsak.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2zocdkfid.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtjlepo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2olvablpn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aransblp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazmgccv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqiqkn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsyfgww.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmwjszr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2poaqylzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxdqvt.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfamrbg.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ryscckum.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2bupnyxsb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfqpspc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pciegtxk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxbrdvb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iznozsxb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gzokutvf.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfcgxf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgzpjgq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaouszg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgeupwo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zktoflay.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzeopwc.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhcnxbf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2byczeeyg.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmbmqqt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2oapwljhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjfsdtk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcoqzfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfbeeur.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrgjzbc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaacipq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpqgzgr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ithgnhto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpwodhw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuvzzdh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyovebus.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2albtfzut.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlywcotf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vffbacdm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dujffqbw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnprjin.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sawuntkv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzujxti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bscuomgy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omtqrrio.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbmoxtc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kardblzp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bybochuk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2scghdddr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jotczgvw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdevqlgf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhnhuan.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aseqhwmk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipunxyam.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqgsrzg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2itxjwzjb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzorzv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oceebnnb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njtlbztv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piixfzwx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wfccqevd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcecplu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qibhfdac.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyfkkec.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2maunsuat.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhbgdcu.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzujdgu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nreebtqx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgspzirj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnvpxgy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurwrod.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhncgzm.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttemmyma.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2djnqnjnt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2legfhuvr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjzalma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdudgka.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iixpitjp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhtmvvg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljekzijo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfxflpq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jomzvmov.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorvuwnd.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2evusnttu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvwjrob.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbsvody.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkobytmw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdakceg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eojflfpm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2shlkvmxf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaoturf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2urrukqja.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bultgxtg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrgdhjl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecanudtn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaddtea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdqtdzo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ytymixtw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcutoiji.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjnnnlr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjpyzne.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2alcazkxn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlxzyzy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frrdlcsn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrhvwga.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2manudwyo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2daffbopc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsvjnyx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrykptp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2agaijmtq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbpndtz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlvtzri.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2joiwvisa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpsitvf.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpqkfjj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxzuquw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mfolfgtr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hshpvept.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2obnjwkph.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwkyek.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjecchm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntwkhjn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2btlaohae.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2npotblro.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonkomnu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2msyklavv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2btwrkpzq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvckoxbn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vcamipab.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgucazal.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2frqqylud.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2huscurpc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2likwspjs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqmgcou.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiabjfqz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2twzgsssk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tphroito.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdxekzw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2szofhabh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjppcek.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2crtfxfzq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grahjxhx.html


<!-- 参考信息 -->