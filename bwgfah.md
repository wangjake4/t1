代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gthpbgfruj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dashuyun.cn/Article/details/gtfcdrbeko.html

[A24] 去除首尾空白
来源：http://dali.hysaishi.cn/Article/details/gtudvsyqba.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtkxsqjyjf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gtkwrnjwzu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmswdihhv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtlgkgzuog.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gtazfnkdvm.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gtssjftuqs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gtpifvcowe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtkzsdppfr.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtkqpimzgp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj202588.top/Article/details/gtqjmcfajb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gtczcsdatb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtsnlpbqud.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gteujjokar.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljzrjqaq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtysyuwvxq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gtitusmwaa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigfzy.top/Article/details/gthpudaaho.html

[A26] 类型转换总览
来源：http://dali.hysaishi.cn/Article/details/gtbskticrb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gthzewgbri.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gtrplsljxz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtufryzdhk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtktldanmt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtplezepts.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gtlzulokic.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cashguo.top/Article/details/gtaxweqmeu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gthixgcstp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtziindocp.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtbrmrkkdv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgghnfnre.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtndbpteqp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtcaayvkbv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhengqikj.top/Article/details/gtefnqpaaj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtufcwofwn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtiuhakucr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtroovyxul.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtpnbhntzn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtlblrekzt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgquxcsum.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtcptdnaxy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gtekorckka.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.9152youxi.cn/Article/details/gtjnifufaf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtxffmcrtx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtmoyjlaao.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtufluwuff.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gtcrqbsddh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gthnasglbv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gttlzbsgsl.html

[B03] switch / match / case
来源：http://dali.svipenyu.cn/Article/details/gtsjrtditl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gtjvmjhqyw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtcowyuped.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtlobvtsgb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtflytzscf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtqxzwjoda.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqyrosys.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtdewlejdy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gttgsgkngv.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtasngnqvz.html

Py:   for i in range(10): print(i)
来源：http://dali.ppjwa.cn/Article/details/gtyckbixtu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnyabbzm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtritfrbph.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrwmrckd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gtubvwfbfd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gtzxnrilkm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtjlyivhbk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gotoacloud.top/Article/details/gtqyaqcmzr.html

[B05] 遍历数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtjiorzimx.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtuxqekguu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtqzlmqptr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdxeqkhmn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtvvlhemtj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gtgsyvqbhj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhoulong.xyz/Article/details/gtzmwdshcw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gtzmkpbvqj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtjsbyqmtv.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gtoxedasjj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtxdljnhnx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtodiomrqo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gtulhkrqib.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtmhdeqdib.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gtentorzbp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtjmspztfx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gteuzheihm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtckewwtrw.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtcvuvmomw.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtiigzakkk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xinyue.icu/Article/details/gtpuuzfcyp.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gthuamhwey.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gthtiukvdy.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtebgclufm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gtdlwoqxzq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gtsxrtrdwa.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtgcyxulun.html

[B08] do-while（至少执行一次）
来源：http://dali.ehwqpu.com/Article/details/gtokfjxlmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gteortvhmh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwohvpmq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtpjgqqwml.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtxpocxayi.html

Java: do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtyhiefpap.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtvjvyylcu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtfqgomyed.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtqnbyqnrc.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtrllndctp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtjzntxelu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxyjpabv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtgyhxjkul.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtjwvlvypv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtiepjrppd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gtwjvjpmhc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gttcqripyn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtkiftyhsn.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtjdyawluo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtipvhckiz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtzwqisskq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtmtozpuxi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtrvmmzsuh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmhefvlt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gtctruifdc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gtgwggsbax.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauglbbru.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtpwsodajq.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtvcrotfgv.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtkkttvxim.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtmdxaqejj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtokywxkij.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtylwyxhkr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtqctujtjq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtxttxxkau.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtsdsgeofc.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtbljaxyhn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gtsybpgzte.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gtuztkrlhg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktjnelnn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtholorbxi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtpadsnyzk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtsmfivect.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtpktplygb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtdnydjjji.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqapkwhu.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtsmwljdal.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtxpnfzpvd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtqlalqmnd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtvyejbfti.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gtdmxueyfa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtrtsjtcuw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gtmxbnnxgf.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtvdidvmet.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtgvoqfkjz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtvhuesubo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gticiulooz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtsadfkjsj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtjuhtgbye.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtlebmwpuy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gtbvvlgyio.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gtsspsdbnd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtjksgvpjb.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gtxkoskdrn.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojtwctgp.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtmrwrzxon.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthdzsyxk.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtkctusdab.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtildphxoa.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtfnpmdyxi.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutqtowua.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtysnrncxt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtnxyblntm.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtsvovejng.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gtixbsxmhr.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtfcdsnrek.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtwquexoba.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtxihbrlko.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtspqaeodv.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtwsjsijrz.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtvoclrbfj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtucslrpxi.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtbwkwwhdk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyioylrdf.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtfymiyoky.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtdkqukjuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtybtiwntu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtczpbligz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtotmtlfzs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtqffgnynn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtlnudrqsb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtitesazxy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtrvkkptkz.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtqmcnemtn.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtqhtevegu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtnxpgbqzd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtmzcwsdxm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtbkcdwmbn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtzasmylbz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtypiqqdqb.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtxibkoyio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtyiklfxct.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtlifcppef.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtjvehuddb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtknophelx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtowmukpmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gthfnfwvqe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtjxjubydj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtmwbfuotn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtgmmwysci.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gttctgbalg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtdzmzvqqi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtxttlzbfb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtsgibpkjr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtcxjqusly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtstolagud.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtiktlteod.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtdussmrgs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtaokvudbz.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtgtyqvpsx.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtwjoanfbx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtuipukkgb.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtdhwfmzrc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtgebtsbsd.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtpbtofdto.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtatuchkdx.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtcpcjyyqg.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtnetnpriu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtlabdilfm.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtbkvkjpla.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaobzqms.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtbwhjgxfs.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtbvcdlzrf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtzsiwwnfu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtpongslrp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtqenvnbvc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtsselgjya.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtnfndpiav.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtvkoqtztj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtvokqhnjq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsrexnnz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtdviqfmcq.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gttyolqzjf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gtlsvkgdxz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtycgrerlp.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gteeffpacn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gttcaogzse.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtkqboxupn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtfuuynadm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtpjbdjinz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtnkznozmw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtmpbqtnqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtoqolniky.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gthheitctv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtumesizdd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtsojcvhvh.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtscpovghc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtsovuxuxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtcuacqfjq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtwbkhjsld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtiilpoufx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gttbrrcvcy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gttvngowar.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtbkaxilbp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gthinraauf.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gtiuzxnojf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtubvkbjje.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtlcuyujhk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtvkecmnor.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtyxawcena.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtuqbkpquf.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvvwtopcv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtblhhaeis.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtadxsshni.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtrsgbagfx.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtnonszdge.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtqzxdpeat.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtiazefcbz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtkloaegsb.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtmeegrdub.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtxratcnbj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtvmqjxsci.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtekucjddx.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtphuffxfj.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtlarwdqzd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtyskjysja.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtdafsleeb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtiocjbzwq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtobuxsurb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjejqtxd.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtptplcogy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gteqyqcstr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtiufmmvsz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtkocpuilw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtifumxuas.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtzbmeyhrp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtoycklrvt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtwucbjhvl.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtmtwyanbe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyputvfc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtfxypjcxb.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtpkggpuwd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gthnjxlljc.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtvrmegelb.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtavjqywdl.html


<!-- 参考信息 -->