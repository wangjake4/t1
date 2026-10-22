代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hamdfkht.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gt2srhymepz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guowangkeji.top/Article/details/gt2qfvxbezk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gt2hdnavwlh.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neytgozk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuanzx.com/Article/details/gt2nbsqlzyb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgkwgjiz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gt2hzezdhvy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuanzx.com/Article/details/gt2eehcxoof.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2edvjprds.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenlongwang.top/Article/details/gt2dhxtavnn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gt2oxotmvfb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2cspstpgs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pngyfbtm.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aztwzhsg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ujcbzjrh.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gt2jhrrymyn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gt2lqxrtiot.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lmehcpdy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gt2gpcgvgcl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2gqthdzds.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncjdfyey.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gt2azuxscdh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.0kj1m.cn/Article/details/gt2rolmpqua.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2oksprvrf.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gt2dznvkbev.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cheryme.top/Article/details/gt2ggugpnef.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nwbrower.top/Article/details/gt2gwoslqbs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2xorembyq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2uupadvdj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2dagcxohw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gt2crrzhexb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gt2vplttnex.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gt2jevmlbwp.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gt2fklnphuo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gt2nycephuq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2ephfdyfx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2xpxzeouj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qdmbnabz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2bgispmvy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2axqijzkl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xylfe.cn/Article/details/gt2xupxyioy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmtexbaw.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gt2hqevfjvi.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gt2njhrzipv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gt2cenqjymn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gt2xyiezrjd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gt2grkjqoxl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2nuoktjhp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjzhuwtw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gt2juweednz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2qfkrowcn.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkoblifn.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gt2kbkhdzen.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gt2eefgxwrr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2zzpetdwd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mirffopd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gt2pwriyqvq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gt2uwbcowea.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gt2dphxhqth.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gt2svtesfzu.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gt2faqhfvzh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.iojbl.cn/Article/details/gt2ghsizddk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gt2fziuzsji.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gt2cfhdkklo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2zdllseah.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vfbhrjvd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhixingplan.top/Article/details/gt2nmntzlre.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gt2jopxjnot.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2nwfcycio.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gt2urvznmyf.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gt2lyqbordq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.c1oappe.top/Article/details/gt2xaamsaxa.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2pzvqgznl.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2phgojpic.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2tnxiybnc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekmfzvjk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.c1oappe.top/Article/details/gt2kuicsuci.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2hhdhydpe.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gt2ltqxxyew.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gt2kflalbvg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2ytimtxyr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2arkfxtmy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2piwyccfn.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2idwxmflo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gt2idvazplt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gt2hatdkakv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2iqsavyuc.html

[B09] break 与 continue
来源：http://dali.yangfankeji.com/Article/details/gt2bvidzyed.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihjmpgwp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjzzdue.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2fymxdyje.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ijqktsmq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2rwfcmkpw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gt2hkvcjkze.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmqovfsj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dhjocyws.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2fnzjbzxy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gt2agtpbklh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vegymrpy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gt2kmgzvanx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gt2zptryihc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gt2jnuzwszs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gt2ehcxxjhl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gt2pcyhxkju.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2ossqahtv.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2wzcbrdwl.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gt2cpvnetsy.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gt2lxtwhvvt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2folwxzkv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ugrtxchk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2rmbeocpl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gt2acgxbawm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gt2isbzutuc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2gdxhudyb.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gt2bagiiuqu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gt2pnitmmpr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2mimcmfdd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2azunrxhy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2jmuxhjnx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2njlqiwai.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gt2bszdkoel.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gt2yogztaey.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwatywgo.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gt2gbpyzzau.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gt2yavqpxic.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gt2smlaurjc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2rrxrcsvw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2zvjossxd.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gt2mygydqcq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gt2mbfxhdvl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gt2meblnrnt.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2mhsomplv.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gt2fprdggif.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klsdjpes.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2brdocsdw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2khlhahzm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2xhfddnwz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gt2zefrddks.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxwfuoyg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2jvtaourb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2swdiqnpi.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2ihrfrinw.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gt2ggjzkrxx.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2bsskdwao.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2ykobcwoq.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2wekrmhcs.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjuvvqsr.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2zabkhkel.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2sudxgbey.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2toolohyr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gt2rjgwzswo.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gt2zrpgwzrd.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldqlotde.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2yfrnojwc.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2ydrmgdvv.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2nazvdkfs.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2xdyassyn.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2wbsbdmnv.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gt2behwwtqg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2twsdhfiu.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhvejkrk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2zobqkahp.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjkdkfik.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2eyikesrp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2mpqocxsw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2jlhmknlc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2zlebreeu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2vdoheacl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2gqnzzfzp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gt2kmjxopru.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cgfvaucs.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2dzuxelgb.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gt2pkthyujh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2vgjamtqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2lqidispm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2winydhzf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gt2qfxazbuz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gt2jgwhkjkm.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gt2jafvzljw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gt2mbmptupv.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2xwtqilzx.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gt2xfsrgyju.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2jsdawico.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2moadrned.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2dqntgqbd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvxxtpy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gt2pgveobtu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gt2ewwnvhwz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gt2gmcgplow.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfrjujmp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gt2uwqhcpst.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gt2tadwpgmr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2qqhwxxgg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2acxeibsi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gt2teimtyhy.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gt2phuztydv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2olzakmhw.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2snruicvj.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gt2mshyzhna.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2djteckgg.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gt2vwhhfeby.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2fymeepcf.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2jyqywvge.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gt2fqkmcvwt.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jllnqdem.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gt2yrkgjrtt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2trklfupk.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gt2ncafjwxl.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2qqolvccv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2pkmyaekl.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2twrfszyq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2tvwxciqq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gt2fdolszfo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dllnneam.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gt2rxrpfqnu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2bksxukns.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2poqwdqyb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gt2wqmjaewe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2icceznin.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gt2imfpfeiy.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbfhgwpu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipwzbgby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2fexwrvpz.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2hzgcsihr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfczlpb.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gt2pvyzxwjc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2zgiyprbb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2sgtsrpls.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2tbhxlfhz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rtnsrgyd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2anjjwjnn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gt2rtksqaqd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2qjgmkcvz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2iipwxizn.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndeummzt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2fgzvcrgi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2qeorvwxk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2xzgqjufh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2krtdpnoc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2smstzkhp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2trzjxhpf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2urytsfks.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztzyjgsl.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gt2dxrmewvz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfzejxke.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2yjodvwfi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2unepjrfy.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gt2atalbiie.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2fqyweszr.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2taohvphi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvdvdvcl.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2fbuykunp.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ysvbsztu.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2bopwhprl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gt2myfeoyzl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2lkpzpecj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gt2ltrinumu.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gt2hvrydzps.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gt2lupvyzyq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uprejfob.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gt2oadjhika.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2qcitqsul.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gt2vpadnfcf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpsclvlu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2cdzsbamp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2elwnjbji.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2kxgoyrxf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gt2hxpfzebu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gt2qqxnceav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gt2fcsbdiib.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2hsrrnpce.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmaetoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ijhvxqfx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gt2gvdzishi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2dpjgisyh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zydosdzj.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctwkugts.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2ezftxzax.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azinthhb.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2zbnohvmr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gt2btjobrzn.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2bkattlmd.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2zmikafbh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2nusrcaui.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmhgnbpf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gt2iwvgafio.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2xvsglueh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2dcvkfmfi.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2pdqwhzha.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2ntlvermi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2gbxedeie.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uvknqaow.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gt2rrkcdjjk.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nayhveur.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubozdhfc.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2zwymuisk.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2oexlptgt.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2vxldxiri.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2gbavfcrx.html


<!-- 参考信息 -->