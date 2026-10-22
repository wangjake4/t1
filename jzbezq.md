代发 wailian999

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gt2qsvtunmv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2eoykmwub.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gt2ojftxkil.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zdqjudy.top/Article/details/gt2zpozuktb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2iitntgru.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.316326.xyz/Article/details/gt2fsmzfwzp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2vkfhwqdk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gt2dubjbyvr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gt2udiwlcdc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2oijhfvvi.html

B. 流程控制
来源：http://dali.meibo888.top/Article/details/gt2yyvvsgll.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rdtbqkrs.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gt2lpgfdlep.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gt2ytgmttdk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2asgoqixf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2kkjgbkrl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2qsttvodr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2rzfjvisj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taodamgb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gt2mehsarll.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gt2nvxepbgb.html

[B02] 多分支 else if / elif
来源：http://dali.sysykeji.top/Article/details/gt2swuldoby.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gt2hznetzmp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ppjwa.cn/Article/details/gt2jugwabvk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2fliumepo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2ctdaxdss.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2twcwycwo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gt2qafqkyai.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avlppavi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2gmzrodme.html

[B03] switch / match / case
来源：http://dali.gogol.net.cn/Article/details/gt2oxdswkmi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gt2eesmotpq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jrspreyq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rhjfsddv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gt2jxfxytei.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2pxiuevvi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgzujgtw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gt2ciljmoie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2mbhsxslq.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2uymwmfkc.html

Py:   for i in range(10): print(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibcxltmw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxnuqovd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2obyyeduh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2bqpdobyk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2ofwnvjbn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vftzrzne.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gt2netzbroh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hospvwip.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2bargkbqm.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gt2rsdvcrwo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gt2wfvrdjrt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfuqyxaj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2xyzqbzzp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2ovrnevfg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gt2gnrlsryy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zycfv.cn/Article/details/gt2cpteekgp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gt2hwxldvce.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gt2xcpbieek.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jyoumei.cn/Article/details/gt2ypchqkip.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gt2stqlivbc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gt2rfbphssh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2tyrbmqwa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.havefunace.top/Article/details/gt2fveqjlwg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yangfankeji.com/Article/details/gt2ilshqgpw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmwvibes.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gt2ubmqwagw.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gt2aaeqjvaq.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gt2hqurtcsn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gt2txlbtwcl.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2blcyeual.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2ocregnhv.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2jasdxlqb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gt2bemgcnaw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gt2cdceexhg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pizlrayn.html

[B08] do-while（至少执行一次）
来源：http://dali.sufxvd.cn/Article/details/gt2zmubdymh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gt2ejirhwhu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2gfutmqzz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2qlcfaanb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2elonauqf.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydtwyjsu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2xtfspjsx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unqayize.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2dxtgakul.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gt2kdlqbean.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gt2rchmbzzt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2joezubbl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2hqblcjcg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wckyepio.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2wybwoqgd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gt2negypxwh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gt2itluyyxv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2psbxmeks.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2unmplumi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gt2wkixnayq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gt2zjjtfyca.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gt2tyuixdiy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2umbdrgcp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gt2swvajrpo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.svipenyu.cn/Article/details/gt2vuvwdfnu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gt2ftsqlwyf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjeksvds.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzjaojmk.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gt2ameyinei.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2vqvnoikt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2bravwcxs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gt2zqpbugft.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uoyuaotd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gt2ltcphfkq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gt2mdjfzeph.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gt2jwngpshg.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsugnbcr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gt2pblycxrg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gt2mhncraqe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2ymunlnyy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2ytgdgkjh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sumvhatb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gt2jdzndvfd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gt2tjfytbmi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gt2fcdkxtzl.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gt2icnqubze.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2swukianw.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gt2pouaphdx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2oklcuvcg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2feimjvzq.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gt2reecwvso.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gt2klwpivil.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gt2ldnpkrgu.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gt2venrsahy.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2rzpjcalk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gt2vqxryjsp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2qxxuduii.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2cjwrdfsv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2hgvikqaj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yasbbcum.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gt2dsapvdia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufbcxexu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymcjcops.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gt2byfdnrbq.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gt2bzarjttz.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gt2jxwexdrq.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2pxttrkgq.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2lmbkqroy.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2psorepuv.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2hkgkgvnx.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2gzjosebx.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2rmpuhpkn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gt2nneavfzc.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gt2drahficu.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gt2kuhrvuyg.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lijetsri.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2nzsfcqqo.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2fkoxbjag.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2dlpusakd.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2skgdclpx.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2epefkjxz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubgfnsmf.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2izautvjj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2pomkggdz.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2lvivymqf.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2xyqghoqf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2xdkpqndo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ciwwxzll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2dblvkkoo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2zvpxlldi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2elwoiygs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gt2amtclfex.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2haazzfle.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojiqshou.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gt2crxpptjz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gt2frkcybvu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2ylxzqimn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2captmnrm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gt2srfclruz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2bnxjgzch.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2tbxgizjq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccptzlix.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gt2okrluakn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gt2cwairlyk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hbhmttxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2pslbmmni.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gt2pnsiheth.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258888.top/Article/details/gt2wpkrnjcn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2gjqqtwqx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2rlciuzdn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guowangkeji.top/Article/details/gt2wysbcixv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdnnrrqq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2qivchwxy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gt2vxxioeqc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2raaioupl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2ofprbjxe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2jpjgoiru.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2tudostdt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2evyvxigj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2enkbusfa.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gt2nmynprpv.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2tsrjtupd.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unmmrlup.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldklbruj.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2juxqnkwl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gt2ajamwfuz.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzclldxr.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2nozksizv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2lktziooy.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2humvucfk.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gt2fybthcsj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2cbwdijij.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2oskzdeto.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cebjgskg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2xnlnutoo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gt2cyzjdvxr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2yyyeaubr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2vbnhoime.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2inyhfatv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gt2svqtcyjb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vvfrnlti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2mahsrwgh.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gt2fsjpcbww.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2aoxsdsdw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gt2lrefxqkn.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2zcesgmyu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gt2gmikmmpu.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gt2pdeuiegh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxcojdxm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gt2zssqaktb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2zpkgbkea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2vejvmnhm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxmihten.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2dnhhyvbp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gt2rdtuhybm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efvgbrhy.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gt2cerokujb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zipoadca.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2xpgoipcs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2kgbzlvwk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2oqtyazan.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lesboqfh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gt2szxiiyud.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2papjebpe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gt2uzncrott.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2cwqqwfyj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvhztmfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gt2agmpcqck.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2cyqziqlf.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2doshdyua.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2ggsdjpzw.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gt2moszmyli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gt2auxcpcmo.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2ixbaygbn.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gt2lpduywkc.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzazgnfa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gt2wcgquauo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2xqjhsvie.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gt2gslwdxrh.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvwmmwxb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gt2kdvodbav.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gt2zovfxcgi.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mchrvkcm.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gt2ahmhsjzy.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2tjmztvoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gt2pdltgmcy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2wnabuvoo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2sdajpxhg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2eniahsfv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2sitizumv.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2gypzktnf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gt2ykjuthfe.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gt2ivicxygy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2odkrujxm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2ikrwpbbe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxjnddur.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2sdwbaokz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2gouznndg.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2gmdmfbjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2trnktpiq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2aiwwsqsq.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gt2faallxlg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkgfwfiw.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2wioqjrrr.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2iytdwhwv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfwukwmo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2rofimxsp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldvejudp.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2iqmzlfpc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gt2enxxjjju.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2iieyeamh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gt2leqvkmbr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gt2nwlykdsn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2ppywufwv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tnrhtxzq.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2vvijwsvt.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2litbzhps.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2usmahzni.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydqesuxo.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gt2aosveskh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gt2uvsmzdjw.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gt2ookiodgu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2zrkcgolq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gt2yhprwrhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tsflzjnf.html


<!-- 参考信息 -->