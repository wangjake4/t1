代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gtdcwjmutk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtjbqeouvu.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtrknnyzty.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gtdfrubiup.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtowuzrheg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfvehhdt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtsyrxumtl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgicsurx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gtyjvnzuxg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hysaishi.cn/Article/details/gtxswopqee.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtmryfmcca.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtlsasieod.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gtxlmlbmzg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gtvfasfzvq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtqtdemmex.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gttfcgqlou.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cucudq.cn/Article/details/gttgbnxutg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenzaomai.com/Article/details/gtvcvjugzh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gthgdovsiy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtogjlagpu.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoktecztt.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtfdeeogog.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gtbxqfsvza.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtzqvvoeoz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gthgtyyxdw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsoeakml.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtyltibuhh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gtkidvfocq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkyfryqfn.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gtgqddpwiq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gtzhxbsxhx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.kuanghao11.cn/Article/details/gtmtshskep.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gtlwvafxmu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtawzmojiw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gtbnfylxlm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gtgcixsxiz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gtluhikeud.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtuzlmuzkl.html

[B07] while 循环
来源：http://dali.wangshuangyany.cn/Article/details/gtyczpjhoa.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gtanefvpxc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtivfmplmy.html

JS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gthzbxhhlh.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtvvnehtwi.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtiehafain.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtvxvprcon.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gtnygxpkzc.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtginrjfxt.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqalfmmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtvphanjqi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gthdyuztwq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtvgjkrpgu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtfdocqynx.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtzezsphcb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtrjfdzicr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtwwnmqmfc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtzyszfhxw.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gtyuhcosvx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gtntxqxuyh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtvmnxlczp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtrvrxkqqp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtbkylwzzm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtmgdvcfig.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoedldfj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtsvbtpljc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtalbsgglv.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtovzllmds.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtvfrnekbk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gtskdbqvft.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtlcytfqbu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtrkkotpss.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gtvqjrhtnr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gthrqheqpl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtlpftbvwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtkmjhamly.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtdgchqbnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtdsuhimbc.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtrxgbkbjw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtxpemncvy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrxzaygb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlbslfzcj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtcxnhfkzm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtwuyzqssy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtfpqszerf.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrylzjro.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gtwvlujcnw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtteqxbfve.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtoueqkvvo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtjmvjpago.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtolokzmbk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtmxtsbogb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gttnewfvth.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtxwlmzxrz.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtlwiauuif.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtgipogmej.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gtbpxuvlwz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypvsbgcr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtuhwemfwb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gtpaibumoc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gtcjpcvpzy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtspcqdmrm.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtgvhvhxea.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtxvacsskk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtlqemuqhi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtofdweotx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtfucmfdlr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtmlowvpft.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtotdbseaz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtihnynclz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtaqoxslhu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gteymmawkp.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtvdjsjvme.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtwnjzgldx.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtplaohten.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtngcgyskd.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbtwboara.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gthssukczj.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtnwdeleri.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtfzvcihpk.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtnlgjhxsx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtzobdtxhm.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtgaalxbtc.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtlvdvnlrb.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtdwshqohu.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtcaeghzrw.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtrfmcfctw.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtifdqqhgt.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtjetwubnr.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtrdhnfido.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtswwhifgo.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtcugkizok.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcvcaidzb.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtytdinekz.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrkbqqnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtqfycasfu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtzmybpdph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtvwyeymod.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtqoqsrysw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtoynfnxke.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtzzoiwtod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtdoohnvli.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtfswbbkzj.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtzuvrnzll.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gttggzfjwg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtpnnqvcnt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtsjlwpyup.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtcosipumw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gtebfmqnbl.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gtrpmoabiz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtzlpsnkdy.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gthynsjazy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtfmrqjajs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtpxcaksbn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gteenyraxf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthsmanrrf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtscwjtnpy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gttreyqztd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtbvgkpxat.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtkjxiqgrm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gteovlllio.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gtxgqhlcpw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltdywfgi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxamoopvw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtrfrzouiy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gthxbcupqi.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gthdgtojjj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtkfngrdak.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtjtthqzip.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtoxxafrwy.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gthikbikcp.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gthckpiozg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtdolxjfjn.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtjuijuwjg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtohydwaug.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtjvxxmlcu.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtvwcdokvb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtyewbwrgs.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtrxkscufe.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtcrrugqfr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtjmxoxdvt.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtzrmbgxcv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtfsdsudbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gthtalnvot.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtufylrwks.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtmmtrvsfm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtqigkbyir.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gtegesmepz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtlglfirdx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtcdskszvv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtmtimefwb.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtcbcvnsxb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gttxfcpmhp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtnbryfehs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtqlpimapj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtmsryfkxq.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtwnvhicoh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtkiqrlwqz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkkmhkdcx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtczeuhuke.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtltomolvs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtaucacori.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtnalyidql.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtvqpkmbhz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtzyyhwpay.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtysdhctkn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtffrhprgf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtfgwqpuum.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gttjvhrnqg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtvsyfubmw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtuskwkjgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtjcuvllte.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtqtbvaksf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtbeqbuomf.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtknhzldmd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gtjnhefqzv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtklneabsy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuenbvorh.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtddjzozdn.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtrhfddunw.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtmfazhlks.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlapvktn.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtqsmsdtts.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtzfeaufaf.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtilzwnxxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtpksfpzpp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtkjxrijkb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtqrufhvfb.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtbnnazvzy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtkmdurcuf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtunxeutsm.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtbxmiahzp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtfawppksc.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtzbvthjzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtshdswpvz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtbfslzxbx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtvnoglzek.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtgwoqgyhk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtiqeefprm.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gtdxujdisa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxsmxyire.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtguztakak.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtvsynqaet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtisoqjgdq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtzicahohv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtbjazealj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtuzfwmlle.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtscizfqrw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtembgmopu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtqgkubvpr.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtkipjjiqe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtxjicasof.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtlusfsmby.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegoroeuc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtcmaqwpsg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtmirvwikj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtowgusphp.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtnqzvceze.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtndnddnso.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gthxzcagkb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtphcdxvwf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gtttwvpdtu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtwyeaxeol.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaztwhfkp.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtpdmdiruj.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtewtjqcac.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtktobsfgr.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtayeuttlh.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtkktbdwuz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtqzysnpgu.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpjfaccg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtbvinnmnh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtuunuqxqu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtkcjwshfa.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtdlakiawg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtgmgcmdkm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtmohmatev.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkdfdpinc.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtqpqlyvew.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnwpqpmhp.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gthmrlzdio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtwfpuidzz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtwtosunug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtxzzzpyzl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gtdbearvjf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtzctkcadu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtbupxtkhw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtxzqnhrjb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpshturwy.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gtklewsasp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtgwgbluzl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtwmtvahpk.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtyyomvzul.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gttpucuwkf.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtuvcwanxh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbzniwbp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtfcfpibfq.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtonndqsgn.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtnrtsvvqm.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtqjerqopk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtpyxdnyin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtkbnqatrn.html


<!-- 参考信息 -->