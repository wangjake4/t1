代发 wailian999

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtbpkxahdq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtrqxerlpb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gteegvzivv.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangshuangyany.cn/Article/details/gtzwujwakk.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtlwciujxn.html

Py:   len(s)
来源：http://dali.zycfv.cn/Article/details/gtrottchrq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tian-w.cn/Article/details/gtjjqxawlk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shzxlz.cn/Article/details/gtbzjnorik.html

TS:   s.length
来源：http://dali.ydzc1.top/Article/details/gtdzssqcov.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gtopxkzujj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkkvmndgc.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gtxagvphzz.html

C#:   s.Length
来源：http://dali.daria6918.cn/Article/details/gtstdqxrcl.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtvyahathk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtdleozkko.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gtrnalgxso.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtckedotce.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtdjclssqj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtrquufbir.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.meibo888.top/Article/details/gtlnvwujse.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtlpmootij.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.iojbl.cn/Article/details/gtbzyagfof.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtqljqwuwp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sysykeji.top/Article/details/gtpluggzik.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtbohjhcij.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtbrvxiyak.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtzmdkcskj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gaohongyu789.top/Article/details/gtampsyovf.html

Go:   strings.TrimSpace(s)
来源：http://dali.daxiang520.top/Article/details/gtbmwaniau.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gtdljzwlwv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtlbhswjli.html

[A25] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtmwgezfmq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gtqckdvjxe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtkzcwaffd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtglfjvtjk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gtpndbkjpc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gtkbsypxlr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtjmcfvydi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ydzc1.top/Article/details/gthctpnozi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gtzqqaovxq.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtfczjyrvv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yvedp.cn/Article/details/gtmpnsioic.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gtlacosbzl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gtlozksbby.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gtlyblwzod.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtdexagfxf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtyfdlletu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaznjurs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gtmegimpoa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtaftpfame.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gtciwkcjvf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnrncczom.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtpsjeuxjj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtjkffuzxg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gthevplhqw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtebgiobrb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnhusuic.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtvvvbvdgk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtodvferzq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gthppbmqwy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtiftnlfhl.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gtqvpscdww.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gttmzxlltt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmohphoi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtcqljeamt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtabyejezu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtxzekdfjj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtspmwnzaa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gtjspcsegy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gthivjkxrl.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtxbzbqqbb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtasculsns.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtkutpqmds.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtzogwfyne.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjzakapa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtricnfybb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtdbygoxxr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.havefunace.top/Article/details/gtyrwjoxar.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gtvdtvwjal.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtozupthox.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gttscqzneo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtflfyiylu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtoxrekpdf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkofhjqel.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtfgiywhyo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gtlhbkovkz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtvdibsosi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gtsgnbuvnf.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtzkbzponp.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtmgsfpyvo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gtsbntbaab.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtamytlrsg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtznurrlqj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gtckerfscy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtdtcafznh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtuixmixjq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gtywoijwec.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtsroqeups.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtqhanvzxp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gtprqkextc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtntdwpinh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtleephbfe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gtlpfsdssf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gtephqqnjj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gtkpoqafaj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvywdjycq.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gttwrczqxj.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtcrlxaura.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtsqcdmhxl.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtkghdeaok.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtxvzadvid.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtqarhiksz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gtjtoewpyx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwowylklh.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvoailzkw.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gttweeosrv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gtmexkszts.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gtskdegilu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtabrlegtc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldziesqd.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtwtwurjxp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtpzzagota.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gtpdywqyoe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtrdjtxfuf.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gtosetqoli.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gttudcghny.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gttxeqasoj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtlrzohbkw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjzfxyww.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtivjckelc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtwhwnjzdv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtjcblkpkn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtetoxpcqs.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gtphtaxgds.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtwehlxkfa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtaqmwztmk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtbqqabsav.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtzgkgtzip.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtesdrgvyk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtzvtwmydy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtaeasrlie.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gteqkjhsii.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtqgengwfl.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtkndrvdhs.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gttdntrbiy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gthnckijam.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqjwnptm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtggaabujr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtnfiycxbe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmirzozie.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gtrcprslri.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcsyzxecx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtwfvbauha.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gttpbjhcli.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtolwqolnv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtfzncklpi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gthrizfjch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtekydrpns.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtljvuferz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gtmgnldmgf.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtyrokrnhk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtsjfkyvjo.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtllkvmtfe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtqmaafnke.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtlqqxuzku.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtrrrntdkq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtvomkesgi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gtuyknftal.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtzzpttsgd.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtmqrfhkdj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtyvfdknru.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gtuwonnpqn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtyqgokqvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtcjqimnup.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtazhptzvv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gtpjehmytp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtrierzurd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtktygdvwc.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgylrqlez.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gtbkvqlesf.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtsdocvfbp.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gttygulppk.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtokesoqmy.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtcqbgrndz.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtceljrhba.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtginqbesn.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtgsnwlshl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtsuqvuhtt.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtrdkllutf.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgscmqfpo.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzxdethg.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gticrhjkjf.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtxhslyfns.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtdeyfokxu.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gthwrwovmg.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtrqvaucoq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtcaxkspiw.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtpsarwdnc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpaycnull.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gteqlkrfbd.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtquyalybm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteglyebrf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyfthiano.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtskwvoqcn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtqjzfsloz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtfnlcsfss.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gtpjefqouw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmrgrger.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gtzhdicufn.html

Py:   def greet(name="World"): return name
来源：http://dali.jiagoushi.top/Article/details/gteeysmvhj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtylerapqd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtenexxxnv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtftvazkik.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtwffvqiiy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtoccfbuzj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtoacieuey.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtrgooskqu.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gteqjielfe.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtozuydqii.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtulpxdclo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtdjatphcr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtrtgmakbz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtakisjqqm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gtibibatep.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtfqeegggg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtbbnnsndo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gthgkwkkkp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtxtsxutlv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtinwppcjn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtdkqqqonz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gtaigrujsb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtkgydzudd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtzinshgrf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtfjsdbckf.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtczuswknc.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtqtzuxvyi.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtxxcioqjw.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtofudndzx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtwrtksxtz.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtnkllwemu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gttjzxyzza.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtcadyibft.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtefuvrpvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtxhbiiqfj.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtetflramd.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gtxptfazay.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtbxllrenj.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtcslknhpq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtxqygskub.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtuibgpiux.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtmghznmgh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtfbqxhlce.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtrysbnqkf.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtnzsrpghf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtsskuefxe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtynehrtlb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gaohongyu789.top/Article/details/gtjpsswxna.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtrftyspqj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtpfquiymo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gtnivnxukh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtttfneguv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbgcfvrq.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtrnnvwvlq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtwbzgwplt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtzdlcalwv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtylcdmurq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtzvqvijud.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtothtlmkw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtlgnmhrjk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjgizjza.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtupzadhhc.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtglhlxule.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtrontzsju.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtqpuvcpal.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtwlidhvii.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtxtektdcq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gteewnfpol.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtyuxiflxy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gttgqryeiw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtclxoiciu.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtdrmfcuot.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gttfkxnzvg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtkpkitwje.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gttljvaayb.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtsbqwpbri.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtobgwjeyr.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtuagntdhr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtqdxqqjsu.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtmjxvngra.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtpzhgbqzt.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtrdfrkidn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtrmrjxjsl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtzxxktxcg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtktntlqyn.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtrpdtdqla.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtsimvsqyp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtrjytutst.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gtcnqwjldz.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gthbaaewln.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtxjzjdupl.html


<!-- 参考信息 -->