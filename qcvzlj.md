代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtodbsksjn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwspbvodt.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtnqetgopj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gtlkraziev.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yonumen.top/Article/details/gtfutxnltb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtrccbgsps.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeohkvhy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gtotolupri.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtwxdlndlf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtwmzplgrb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gzhubu.top/Article/details/gtbuumtndc.html

[A25] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtuafwynia.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gtyhzgajbu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gtjkymerzf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtyjgxhvrc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtwllhyhwa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtevswnnhm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtyfjikvgb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gtplkjuemk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtjmypldrk.html

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gttxzqopkd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtogfmctnv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gtlxzrxpfi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgtfrpio.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhpwtgge.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtnnixwlow.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gttcehmxvh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.birdmap.top/Article/details/gtxfuduybx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuovcsoej.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwblbbztn.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtigbbjpuy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcbvpbwrr.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtfjxhrcmb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.mhx1999.top/Article/details/gtanjdhnpl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtzpdiepcj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtqhwmkjca.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtjgcwfocu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtjoqsqpkr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.daxiang520.top/Article/details/gtzohbvyyh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtrbifhwyf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtgsbwnrfz.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gtrgwkncra.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtiuxaiwra.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhoytguj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtrhzllnfb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtvuykahhg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtazidisbi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtyahhzclo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gtuzipxafq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtzxxaezmi.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtcwaekiwm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtrfslowrk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmindbrnv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtjwmkoqqj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtgeldgxvd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gttqfilpsw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtwmvbwfdn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gtzmcpseue.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxkgmyjp.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gthoxsfcpy.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gttfcqqjsj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xylfe.cn/Article/details/gtpfhmeslh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtnoyniryy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtejwkdrqr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtouxkdwze.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shzxlz.cn/Article/details/gtncwqhwbj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aizwys.cn/Article/details/gthrclsrlh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gtzkrfqwnx.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtrjumynup.html

Py:   for item in arr: print(item)
来源：http://dali.sweek.top/Article/details/gtzodzqhqp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gtkaaobdie.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtgsghyfsb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtewsttgdu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gtvrtleage.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gtlhlkuisz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtrzsdlhct.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtfcanmqsr.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gtcsqwoamm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.redwolf501.top/Article/details/gtuoitnonl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gtdgpuqtnj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtazjafiiz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtrdsuclek.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gtboiqhubr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gtkeozijui.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuanzhike.top/Article/details/gtenhwtall.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gttzkgagwm.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtbpxglcmv.html

Py:   while i < 10: i += 1
来源：http://dali.birdmap.top/Article/details/gtbnzefrwq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtknbeemhb.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadpnxnnl.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvdabzrv.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtocatpgki.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj202588.top/Article/details/gtfyddlfon.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gtojlplkeo.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydjkayzv.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gtiuleqtqv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtpdlkxxyo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtbxphdtww.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbptistzw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtxuebujew.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcxpvcrb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtbtnnnrjc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtpdfpsphq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtnshzracx.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gtpzxxkmmn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtsvpxgqhn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtmxdhjdbo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtdixlzgit.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtabwbwzlc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtbkbkjpda.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtkznyxerp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gtdngogups.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gthnvlyfpb.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtzxudrdci.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pengpengdd.cyou/Article/details/gtarptfrii.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gteinyqzyx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtposwizil.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gthcxzliej.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtfucaomft.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtofkpyvbc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gtblruhyrn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtoiivkzrb.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtppbpmrvc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtimrbmkgg.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtzrrmncga.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtncjlvqah.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gtwdvahifr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyuijaku.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtddkjbumy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gteetbzeih.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtzhaiprau.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtsqappvcx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtcvzqbytp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtlduqrajp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtrfgvrbsb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtdrznmsqy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtniivqgqz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwredrkhx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtlrjcguse.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtbjhbdmbc.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gtjeejcenx.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtysozgeqg.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtqgvtyyia.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtauphbzcp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtisvxwbsa.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gtlnzqcixg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gthaygvgcc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gtrkixjgye.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtbjxweatx.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtitqdvnyj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtwtleehgb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtoafkseca.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtierpozok.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtofoibiec.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gthgjstckd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtufvxljxj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxoqnfsyc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gttjwsavre.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtszgeizsk.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtolircuix.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtxbxzbycb.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrshtpsf.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtmlrbekah.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtjxrevcwf.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtzylbiixk.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtbadmmlsu.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtcpgzgacr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtkzjcosog.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtqtlpxaza.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtltoopbgm.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtpxgwnzki.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtuurrvpxs.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtyntxrnnq.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtrqoyvyho.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtnnbbvgwu.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtglbmgizq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtddxrgmjf.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtnkjjgxfi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqzzdjrjq.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtioklieci.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjcaplfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtkcmbvgud.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtxacssnrh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtarmdckej.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtjtatkioc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtctycvkda.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtrmnmvwnw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtawaosmyx.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydahcgzz.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtmeblxevh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtdxxswisr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtbcejospf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtgykozdee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtihiskfri.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtspepgauh.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtbwpacqpv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtncpluyaw.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtrfxsgkjv.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtqgkrucre.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmwplhrh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtnrlvgauy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtoimtwlif.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvvhfjsyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtwldxtjqy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtscxuyqdv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtfmmtqtdu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtbeopxlnl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtckfzxzac.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtfwupkqmt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttntrvgxq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtqzhbcvbv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtznxrzapy.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gttkmharia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtqvjkqmjj.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtvrrzjurj.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtazviyqjf.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwszlfrnn.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtlynitqqi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtyooxplpm.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gthzsalswx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtqtrhwzcu.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtdkfozobc.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtczheptcu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gtzbevkqcr.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtgawdmggz.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtrkqddojo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdvafofo.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtgaduksxb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtijunntpc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtccwzqcoo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtqvwfoqdm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtlygjfunx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtaipbkauo.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gtfofmvjbb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtgkrrnlot.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtsdfflbfq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gtlssqkdnl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtvoxjvmyn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtocxizcrn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfojrdrh.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtwuvfkroc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtkfurtspn.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtrvjqbaxx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gttdidnbch.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtswfgeojp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtexazetwo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtegfichxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtscrfovbk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gtefwwwjbh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtyvogwpwx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtzsovzxfx.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtdwejokqn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtptnlyyok.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctbloqir.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtbzhlsmjd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlljhyoxj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtzibroqoe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtvukgayet.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtcngcfyjt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtasdbvhct.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtmxcxwrcf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtbbuxukfr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtsirrswag.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtfhcywign.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfzbhulp.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtkddbmzar.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtrnqhowye.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpfrzzzl.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtviizajub.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtjvtzkang.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtpsnavbwd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtxvgroegf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtpztyhyym.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtpjeycsge.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtesselunr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtrxcarvaw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtlcwaytks.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtmwblkauf.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtbmvjbaxw.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtcoopxadz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gtfvqsrpbg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gthbgdacao.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtrqwawzxt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtknjuhliq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtnayltvoo.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtthphfpif.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtlptaolfw.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtnvlratcw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gthzjehvqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtdqtklifg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtxtxglkvz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gttrzyrmtj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtvmfuzdmi.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtzzhepdey.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtczwyxavu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtlaxodrwq.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtewkykeyz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtuqfadjuc.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtbuhqwpfl.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtpbglyceb.html


<!-- 参考信息 -->