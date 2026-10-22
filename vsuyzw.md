代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shzxlz.cn/Article/details/gt2bgedhpex.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2fxhpnnlw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gt2uhqpbffd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gt2xbhfjwmn.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2qxkppgqc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daria6918.cn/Article/details/gt2qsnhpkye.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrvkizav.html

[A25] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2ndgdkkbv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gt2wlqosvbe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gt2wlpmthsk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwsmbtbh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ysisgkld.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gt2bwsaidka.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gt2kzqsefgo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gt2nolzansz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2ojlwabac.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gt2tixixoyl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gt2prcfusxb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gt2vxqsniip.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gt2rfqklpvo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gt2xhwckgxo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2mrhrncfs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.snrcjt.cn/Article/details/gt2pvzpqkel.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gt2qjmijyun.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eigzwmwb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mjrxxbpg.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gt2eqdlyuqr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2owqkvxqr.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gt2raxphipb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gt2todtaguv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2uoqmgjwv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2exyllnfk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2ykelfoea.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2nhmqnyrf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.c1oappe.top/Article/details/gt2drykdysw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gt2nomyzczc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2uhyqemid.html

[B02] 多分支 else if / elif
来源：http://dali.birdmap.top/Article/details/gt2sqyjpojh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gt2eqzyoldc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gt2tekyulur.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gt2ifnzihgb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gt2grgtnurb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2mesbxlrs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenzaomai.com/Article/details/gt2srysuiaf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gt2qsytwegp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2xqbrcxyx.html

[B03] switch / match / case
来源：http://dali.zhongyouzk.top/Article/details/gt2krvalcua.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfkgfxwi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vhooynkq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2thjjyiuh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2jevtrfgz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2mnducaqi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2pijgrgps.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxuanxn.top/Article/details/gt2ajqwqawn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gt2hqkjissw.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2gimaxjxv.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gt2uwozjlka.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gt2gcdmmbib.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gt2jqgbdlzs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2fiqnxtpv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2mmnaqakc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gt2omshphuu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gt2vydhdqfb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gt2amcolfsa.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2emmasnzu.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2hmtlueix.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmrhfdlc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2bxbolfzz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2ezpgumec.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2yndlxvnu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gt2javplynv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ivvv.top/Article/details/gt2tvpjxkte.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2ltsvtkjv.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2lllndlpn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gt2sgcyegpc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gt2sgvnmtwx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2vncfxulr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gt2puecbaub.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pqheqskp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gt2oooehujv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gt2wqsroqbt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruqtzsxg.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gt2ksbhloax.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gt2aogxsmdz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lyiwztwh.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhsckncl.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hltshkxb.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2vwgodwwi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2xnnijpkw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gt2rlmeqfwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqthjccw.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gt2cmrhsnbw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gt2urprsbia.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2judvtswr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubilflxb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2fgcjfezi.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2ktqdhhzm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aizwys.cn/Article/details/gt2mpwnhdpb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gt2kbfqeilh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2hetrwwuf.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gt2curdrnfe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gt2lohdebdy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ldujivsx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vblyvnde.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2agxcbehd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2tjrelnxx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gt2hqytgypo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gt2trcwamtc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2vdedmfvf.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gt2mizeasxh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gt2reauugmw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zppcqsgn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gt2lireqxlr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2jjjwlweo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gt2yifaitha.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cucudq.cn/Article/details/gt2tkeucefg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gt2eyitbhts.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gt2desejknn.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2fqloayod.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gt2dspnzczq.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2hgbegwlu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2ucvkwqdf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2upaxkixs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2dwnaxyxm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gt2lgefqpcr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gt2ovnshpyy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gt2xscquhpc.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gt2yamgjjkx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gt2tjztfmii.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gt2mdrdxxww.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txuvangu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqzzhuos.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2ogowfyuw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gt2grptbyaw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gt2uwsheuke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gt2qavkrebo.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gt2hnmqsuki.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gt2cwexpatb.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wlqlfnux.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gt2qccwqlpt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2iiyfxnew.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gt2qddbzsiu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2dvkfnqow.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vepwmonm.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gt2uxvmazhp.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gt2jgroionz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gt2zobipkac.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gt2aotxrxfn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2dbqglxku.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxfqkegx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2klgzzbtw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gt2ytfttlia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gt2rtbzqvfz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2qwdxucsh.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gt2avurtsge.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gt2bucxykph.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gt2uexprhbo.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2uunmbvyc.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2dveuxzeq.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2vcxgiwxh.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbyfbuwe.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2ztdqcweo.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2outwoeis.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2jnjfadyy.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gt2nortssam.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gihepysq.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gt2mrvzcjsg.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2cvyjvkur.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2slvwvelg.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wchqaoxf.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gt2poxjptjw.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2xzafeqtw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dhkkgjms.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gt2ohsgwuoo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bhsavrzk.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2nbpbnocr.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2xgubjwyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2yudhrpwl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2lbhuvmsv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2aywqrzcs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2evxdsqph.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2slxcqrcd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gt2oupmyabz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ciidqjgs.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gt2upmxtick.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gt2srmezege.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2bkqumanx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2roerwixx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2dxcqtjcb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2ahiwsjst.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gt2htzzudnt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2pxfdcgui.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2pklsatiq.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gt2nkdvcnds.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gt2ishwbfqf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gt2joevxqhw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2kiiqqqbx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2buzpzgek.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2shwfzrpj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2gzlxyhhd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2yooznezt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gt2objqiyso.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gt2tfkqisvh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gt2yyxaoefj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2pnunutqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2zfxnkpzk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2pawgkmac.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gt2ageogkhn.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gt2enwpkaao.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2tjocrbau.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mihfivpe.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gt2pzyyntas.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2mcsyypls.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2altedven.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2lrggzwvh.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2chxvgqqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gt2utxkyidd.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2zopnleec.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2mugpfhhq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gt2gcmkgisd.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2zzcbcpkv.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2yqklkroi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gt2jlwobhni.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2uxnksbli.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2ribigrdm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2okqaeojr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2gtwfnlxo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gt2uliwtkte.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gicaeloc.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gt2sqhetvuj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gt2njwyaawt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2mrubjqfz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2fxvbmvtb.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gt2wgveosny.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2tilbklwe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gt2vmimankq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gt2xrvaonxo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2peflhpeb.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2lnuuzabt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvpfefvu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gt2yungrrou.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2izzfpdvo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2upeqiill.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gt2wyltjijf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2zmrhzunb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2ncdbkkha.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2ebxyoymp.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gt2nnbnlxqr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2pdygaski.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvwjoewe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2npanbnyi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2mynumqjq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2twptybrl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gt2bvmomkeq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdcqgynv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gt2vlnlvbay.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gt2zanausbu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfaavaih.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2cxotwzcu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gt2rnzcnpfq.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2beyebbqn.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrhtbmhg.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2atiskarw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gt2nvzvqzri.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2ujkwmkjd.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2czsnlkzt.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gt2vondjofv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2vxrglmlo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gt2vviwzcqo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuuzeayc.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gt2nykivjxg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gt2ocdmjugk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gt2bovrblqi.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gt2srfswxxc.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gt2ppethlxz.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2qgwpusgi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gt2hhuxlguf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2jyuppsgd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhuucnyl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2qmpldnnn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gt2qcovsgrn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gt2xjunorui.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2dybsdrwg.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2vnnuvcli.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqrntpod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2soewkflh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gt2opyaptzy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2qlbhpcha.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrbccgwi.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gt2duikeycj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2uvsqndfq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gt2rumkgupp.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2zttwmflk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gt2hactsswr.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2oevdinrg.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2xdiziolt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2dadpuizb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2itubuqru.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gt2ejactvgo.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2wrypdnda.html


<!-- 参考信息 -->