代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtwvzdwdlk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gttwovemcc.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtngaqouxa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtedtnpv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtagonxdjn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtphprclvb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtmefyduul.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtqgrdrdvm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtkfaqrref.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.birdmap.top/Article/details/gtaomegdlv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtwnuegerg.html

[B04] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswpklerw.html

Py:   for i in range(10): print(i)
来源：http://dali.yvedp.cn/Article/details/gtrascuosm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.9152youxi.cn/Article/details/gtellbyvtm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtdbwkucva.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtobdnnbjy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangdashe.top/Article/details/gtjwtxlury.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhixingplan.top/Article/details/gtrgwsjsan.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtflrhrppo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtkjocnery.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtiskjyghq.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkhklife.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtffbckxzm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gtgnbxgpbb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtsonjppyp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sysykeji.top/Article/details/gtbdvcvnnh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenlongwang.top/Article/details/gtgjvwpapg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuanzx.com/Article/details/gtlcymwfrv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtjiiiljoj.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtvajmcsyi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gtxquergtm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqzivxvvh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtbfftppsz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfiwbieve.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtsczqfujk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmlhqgkw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtogaxsrqp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aibaodan.cn/Article/details/gtczskmdcz.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gtdsmwhamp.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gtoowsybjg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gtlemmhqom.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtprnbtxse.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtxvnzwdbv.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtcsygmeno.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenzaomai.com/Article/details/gtgxexaerp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gtujuzxlzm.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gttdpyugog.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtqnypetap.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guowangkeji.top/Article/details/gtxbuoenti.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtrvxwqjcg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtslzrqlis.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtpsbkeioq.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtfalcfoji.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtosofbbrh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gtycjyrryw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtjbcupfpe.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gtuaqpfqol.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtfkrwpdzf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtpaffokly.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtntunosyd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtriaepgef.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtnimsvsdy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtvsovoodn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gtgisjbdji.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtawuqoeqn.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gteirgqviy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtzpqqijad.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtygofugkq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gtxsoylwas.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gtnvjgorbn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gtftrsojgg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtsqbvlmzw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pycfn.com/Article/details/gtyqidzjgy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtukgmgnsw.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtljnjuefj.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmtboipf.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkxsejqj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtlnnyuict.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gthugjepiz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtyxpqrijw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtwjrnmusi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gthenqobdr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gtlwrbsdhz.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtpgcpyyfn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gtoxuaubpz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkltdcpc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtqpplvcgd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtfseptukx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtfdyecsts.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtkichzhqn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtrbjflurn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtltummtby.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtdxjfqqkj.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtaszlvstt.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtwxgobmnv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtomqufvia.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtzfpknkmh.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtejegbzex.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtdkdvucpn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtdjldhpxg.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtbfpotnfu.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtdezmyzos.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtwkoxaeit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtewhmmwac.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjaagdqke.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtjkisfyep.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gtxroxwckz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtxjfltgxu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtbzquzmvh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gthwozynrg.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtcbygudxf.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtybrbxwwg.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtavkfrbrc.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtjvxssdjq.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtpbozkasb.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtjprodauk.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtzvpvofsj.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtejbmgbgo.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtgrtnnfzc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtbimwtmkg.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtoyvqnukx.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtdcjecics.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtlphtuzdd.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtkfdbecwy.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtjllflugs.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtnrwlrbgv.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gthurjssyi.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtgpuwnvat.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgrmdhyki.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpucpymx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiyggaqub.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gthrzxgbuy.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtdnnelprs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtysjtwlio.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtutreuydz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtesyobdbk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtpfiskssg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtrkclxyuf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtxuxhepzh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwspqixfg.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtgmifribt.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtgqetrkek.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtuvyawsui.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtcohppclv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gthetmlydu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtymsfjgjm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtuwimqyzj.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtyxjoptpl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtjlsodpom.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtnqflkkqf.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtqpmytqme.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtdchdxllw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtcpkvxehq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtkadlmobg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtmsrtncgn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtywnnkdab.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gthfcgxzmx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtrtuyrktv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtdsbujklr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtnsejoqhk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtwosafbeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtifncuycx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtfronvbqe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gthnmmzdit.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtrbvwztsw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtblihkvhp.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtdvzlxboj.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtclayjoif.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtdfnwbjge.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtfraycoln.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtjmgruowz.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskvlpjfq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtjwgipyoi.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtvattpaez.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvlujdjl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtlzswpxrn.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtykrhamds.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtgffhapuz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtzjgbdxoe.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gthetuhvtn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtvrufmhfu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtzfbpyiki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtjofqeabf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtorrthrxm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtwsjzqhpk.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gtvpezqufj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtlhnhlotm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtknkddwwc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelxwagus.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtizmcdtxw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtszudinsu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gtilyzdxye.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gtjqjmrprm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gtsdcrbngd.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtuvfoggpr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtpppgwnfs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtlunidkbr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gthxygmjkp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtlzwugjjo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gterwzvodz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gtwdzuovpr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtmmbuowbd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtlkgtmotc.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtloopfcls.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtmlzzkcpd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtjoabodhc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtfrmzweno.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gteuipliiv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtzbrkjcrs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtzghbwvtl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtiuaeovsf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtjtmdytyb.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtyjyecvmb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtpdnqwnmy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtcmdrwudu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtxoxeklyb.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gthvkcjlbm.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtxwtvugbk.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtmdvqrwjc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtvdlhukok.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtxgpzaxie.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtknundvfj.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtmjmpftoe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcubiveyr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtrrougzsd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtppgqybem.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtzjvmamzf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gtqdhxxpsj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gthedjgjcj.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtmesnohhk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtxgzpzanl.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtwxjnrqry.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtlcwsqdwq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gttxzzewba.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtyklixnfm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtvrnuuboy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxqwbzqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtkqjyxcap.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtlnseglzg.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtpiimfeub.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtixukbhex.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzaewphtb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnjpwofv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtcnqhaona.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtxlegfbss.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gtgjvrmxdk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtaaohilyn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxtmsfvk.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gthfailptj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtdfppuwil.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtlapqvbnz.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gthfvcpiee.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdlkuprgg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtbpvrfkco.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtevtrmryn.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtvzdoulvz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtzrstotjp.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gtvytvnbbw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtbepjilvc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtyteegcoo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtoczkopog.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gteftlacme.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtkeoofmqq.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtsjufhiie.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gttiogbyuh.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtixrebpuq.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtuehqkrhn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtpauclwdf.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtoxtyoenf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtjtumuahm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtwrzbwckc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtgkivugdf.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtnvfheiei.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtudpaspme.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtqiznrium.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepqttfmp.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtxuoubxiu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtntoahqto.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtfbcraguu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gthyfvcafe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtttpvkrbu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtcohwrjri.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtfzvlfpud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffuilnks.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtmsbdemgi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqfvjerg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtzkghglib.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsncidhx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtcktiwlfx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtjgmdfscm.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtvrfszocb.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtmdclmzla.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtslhojahx.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtfkglcpln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gttyyaupmk.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gtjlsepocf.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtfsrfyhzs.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtjwrsseli.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtdmlcervs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtyljlopbk.html


<!-- 参考信息 -->