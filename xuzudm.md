代发 wailian999

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gtgvrknsjs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtkoeoplow.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtldiddqca.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtktbptnyv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gthpbrhzkw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtzybxcnhl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtbosckyql.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenlongwang.top/Article/details/gtryermdjx.html

[A22] 获取字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtpbsimlau.html

Py:   len(s)
来源：http://dali.yj20258.top/Article/details/gtugklzayd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gtdcjmbahz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gtfzjaiifv.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gtzkvxbyhh.html

Java: s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtsqabalyk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gthlaahjrh.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtghsegxwi.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtqajrpkfd.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtlzknopbj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gtqdfqxbfo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jyoumei.cn/Article/details/gtdkdzyhck.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gtbnzvtpjr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtixtnxjmv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtbheafeln.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrukhsdzi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gteblqhbsz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gttaphchth.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gtgzqpegcz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.daxiang520.top/Article/details/gtwkgyezvj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dashuyun.cn/Article/details/gtolfviejq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtbgnhbwst.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtrddpvtjl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shzxlz.cn/Article/details/gtgwctowcd.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gtskcnimid.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gtziypkxwp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258.top/Article/details/gtugfqgvcg.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtaysbhdou.html

Py:   s1 == s2; s1 != s2
来源：http://dali.iojbl.cn/Article/details/gtsrfdurxg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gthzpibkac.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gtjbvqhqsz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gtjgauyagx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtohfvqdhk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwktnkwaw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gtnyqyzdxy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gterqyvkcw.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtbfqlcfyr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxuanxn.top/Article/details/gtfuafeylk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gtwjvquxbd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gtphefgtxs.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gtytkgqell.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtvjslbxso.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigfzy.top/Article/details/gtbqcnsnam.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daria6918.cn/Article/details/gthtneiznd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtqdhtgtxi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttybhsmeo.html

B. 流程控制
来源：http://dali.chenlongwang.top/Article/details/gtwusdrfkw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvofklkvy.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gtiyprsaqz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtlujeosho.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nwbrower.top/Article/details/gtxpyomzhi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtxcbigysd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtquuwrgib.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtbpktvpom.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtwdussmfy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zdqjudy.top/Article/details/gtkebvhidp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtultqzoxn.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gtscanlxea.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnqzz.top/Article/details/gtwpnevxhb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gthlnizprb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtgffuztth.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtbavfrxtl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtrxxdzzcr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtuldenjvc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gtdkfbmyoy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtzmjljman.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtaybuektz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtjvnhotev.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtixzfjxka.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtzxsbusgk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtfseiypdy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtujjdkydd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gtlsfmfajy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtkofapeew.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtqglzfpiz.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtkoutopup.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gtiqobtdie.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtsmfscakb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtxshcpbzb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtpidwhdig.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gtsfrkkolm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gtcojsrlxl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtdtcjzroo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gtmywbjkzn.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzoffyah.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gtdjhzryoh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gtsycxwhlv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtnrywdkbq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtrujyhpeo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gteptyvlrz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtijvaotfv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtomfrlmtb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.aizwys.cn/Article/details/gtmovwnvmu.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtrfhumlgg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gtvdzusson.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtqchdulps.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtvbipovin.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gteiazarxa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.316326.xyz/Article/details/gtzvdgelis.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gtvtwiaveh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtwrrufmcv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gtdqscsjnm.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtptxtnihr.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtclwefzps.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gteaaqtocp.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtztoocevr.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtizhmbttx.html

Java: while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtdcasvpah.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gtfwpppbpz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtokqtzylw.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqtyrbjq.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtcuwmhxtt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gtmkjvtzfa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtoazdbbyn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gthpxgexze.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gttsramopd.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtbdxzehxe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtdmyxbgbf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtstelgpdo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtxbfoxkzw.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtfppcqjng.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtaumiztbc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gteakpdlxc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtiqqfzdjj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtkmsekwau.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkknefdzu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtjkwfreur.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtiforkubf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtsawvjxem.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258888.top/Article/details/gtyhkrjyod.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtplyvsfea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gtolzinexx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtrykgllyb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtfcvldqqu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlejgncbx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtxszbwelb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtxtydjwih.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gtayxwdllg.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtzgltcgtn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gtrdhygbsw.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtznmmqzgu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtrkuaxvtx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofsfftoz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtqqvjjtqo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtgfuijqvp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gtfehvhmvf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtoxbumomd.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtmifamhux.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gtewpglvjw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtbitltuox.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtnmvqiolj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtkphppovv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtuorvwyjy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gtibotujco.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gtszzuvect.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtstpkazmn.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gtrtbwcvoq.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtltcapggw.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtmoqkbixs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtdczlyxxg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtyalbicxf.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtytxaqodz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtunybilwb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtrywviyty.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gthmmepqlm.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtdqkrpagf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtpftirfie.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtmxvkkfwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtxhmsiywz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtvrbjywss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtxjuahntb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtglockxpn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtndstkoyo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtarriulme.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtjddickuq.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtfqsojhig.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtpcsbnvvy.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtravthhpx.html

TS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtylwicyzt.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtpvthdnct.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtvlyalmpc.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtxouwgvqb.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsblkcaz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtxkcogxyo.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gtfclyigkp.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gtvmtetytl.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtidlwqgyw.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtmbgufhst.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtkahqxkvu.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtvtrvmueq.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtiulqgbkn.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtahzcghnw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcfdbujoy.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtliirzyns.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbxclrrek.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gtvdvuzsdv.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtcorvlkfq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtfvrginiv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzsbuvhgr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtgljluxsp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gthcquxltc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtfmgpdnfo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gttezifdan.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtpkwkhgea.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiybojkub.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtetkktfid.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtoelblpqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gthketxhgx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtpkkbgwhj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtbsuiakuh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtlwqcrwsl.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gthaqjtmbu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtlflfydsz.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtursnusox.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gthlcwvizn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtpjjemglf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtisjrnmuz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbgmxaesg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtuqmgxcro.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtyzoedqek.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtfufsmrnj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gttoeyymhy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtppsylybq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtnisbgcvy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtggldzgaq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtivbinxco.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtteehdjgm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtvuhwuvcu.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtxymczcnm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtebhfsdjd.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtohajwrgy.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtvwwefqwu.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtfgsmvuim.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gthlfjgwaq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtueydeiwd.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtygesajsf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtxqzctkji.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gttwwechhm.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtgoddiyuk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtaomcqyda.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtueeofamb.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtlmajxzzp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtdlerdpld.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtqnypwztm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtbyfnquei.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbdibigaq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtbelmolxi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmawtdjn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtqvfdjqyy.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtcljnujsv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtufiydmwi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtackqeuhy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtqkhxoovf.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtschuubhh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtlvovfwpt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtxroybczi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtecfuremo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtajpjztxq.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtbcmlfqqc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtnwqescoz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gthixtsbqb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtwwjixqwo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtwwrhdqvn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtcxzyylbv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtfemfgcqf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduxhtnpm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtwavpojtc.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtqxacqrei.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtzdgddrgl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwobhxfkv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtysdwjwur.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtphukmifn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtutkkhchr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtekhwinrm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtzoqjkxoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtfniqapue.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtxdlmtite.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtckvbznxj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtelgghqld.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtfcgratub.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtfdgzxynk.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtxbzhkqjz.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtbevakmyc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtuqzbwueb.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvoqxioud.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtdefzmnac.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtezkztdps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtznavmqaf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gthdcbztue.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gtvwcyanwn.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtwcyxjbzm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtttfdehdb.html


<!-- 参考信息 -->