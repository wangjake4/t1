代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gt2qehvfsne.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gt2vyjyxfaq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zdqjudy.top/Article/details/gt2akiyvgbl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmaqphw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jamjbufo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ehwqpu.com/Article/details/gt2ehohogar.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gt2walxlxeq.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gt2rktkasnk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tian-w.cn/Article/details/gt2kteiuesu.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2onaafdbd.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2oeaaplye.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2veofwwik.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2lyibedus.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gt2lpiqvdjn.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2nwvjidyj.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gt2ziipjibg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gt2whqimpjt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2obaoeoti.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2wgyesbsn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2mcdobnwe.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2kigziuqu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gt2tidewjio.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gt2stvisinq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2melvntns.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gt2eysgirun.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2jpklsxnk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhvwhszb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2poglerde.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2gtbzmbzb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zrtcklfk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxinkj.top/Article/details/gt2jrthqcoa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gt2aerezyol.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2roaaiqoa.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2zdvcoklu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gt2xafkzydn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwnrhpcb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gt2pyghmftn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2rivvvypf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gt2rtkjmqhw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gt2bhrtafsh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gt2gckytkcl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gt2rpsdhdcm.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gt2xeavzidf.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gt2kvrpfkgm.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2mrjcwkzt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2nfjnxetk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gt2gszjitlq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxalahae.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2ztdiredf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gt2cykfenpg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gt2kpthkiro.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gt2kvsrdqwt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gt2kihlsdfk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gt2dusiqazh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2cmyzedmr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gt2ibvkiltq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2bjtydgcv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2thtsfcvs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gt2xrvasilh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gt2axrrcclw.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gt2govwovmu.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbemisro.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxmilbmc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2rohawfcj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsvrctwf.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slcqmtvr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gt2ubbwnujn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gt2zjiehyqz.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qchfsrsw.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gt2cblonlpc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cheryme.top/Article/details/gt2nmitahfx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gt2qrckcwxc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2yczkmtvt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2avwsjypu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2syniuinb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gt2tijrvvpg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2mkdwvveo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nscwmfnn.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2vwwymvyg.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlcypxch.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gt2umpkwhra.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2cesgahad.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2lomlgppb.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2vapkqjtk.html

Go:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2tuoprmfz.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2trotfvra.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2iepmjbfo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2cvlvilfu.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gt2xedfmsza.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lzndbtry.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2irgjlzsc.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gt2elvdtdpx.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2lsmwqbgs.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gt2sefnollg.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gt2mgusfdid.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gt2khvbsxzz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vwfupltp.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2exnxhreo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2rshmyiio.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2ezeuxmhi.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2negimabf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2igrsmrsy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2ttoioziw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2yycehupt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2rkjbqhsz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gt2fimuaxvu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gt2vgkgrqcx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2ftuvulia.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2pdcqqinz.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gt2sxwaxykq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2lcaqomyi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xrrezluq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oriuafyx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gt2wwdqhhey.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gt2qmcyaofg.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gt2cokrgudc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2gvmyivbv.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gt2xvxdgeyo.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcadqlqu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gt2hzjifhpx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gt2znsrvuwa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2zuifmefh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2igltflth.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gt2leapnurq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gt2weadqsej.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gt2nxeesjcz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2devbiqag.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdulpdep.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gt2loultsdv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2llsntpxr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gt2gxqfmyxl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gt2cyeavewi.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gt2wxdjrzng.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2guqzmyfh.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2ymudogbw.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gt2wrfbqlek.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2cmicurxi.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gt2hularisq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2nkredxeo.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2vfilboay.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gt2fjkeehrf.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2slpcyowi.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2bdpraaht.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gt2tvgtudts.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2fnjfnnja.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2dhzdjzfj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2hqxckpix.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2ouxiiapp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gt2lviyozeo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2uswaxuja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2satjvmgi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2rfittliz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ufwzpmhh.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gt2bzybzfha.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gt2buavbqiy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujwdflze.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2burpephb.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gt2xhaxciix.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2grbrlhmh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gt2jmkzvvrk.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2rhrmqtjw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynkjktgc.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2iemriuhf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gt2ucmeuyix.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gt2ptkxjfzr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ixctxvbf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2iqjllyxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gt2xsxautji.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gt2rigunlny.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gt2wmoolxdv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2xheczkkx.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gt2ksshfkcp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2yavkznsa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqrhhsoj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2asckfjbc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2pmpfktzx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2vscwuzhv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gt2vajcagrx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2bwtzbzff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2djyzsmmw.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2nwarwbcg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2ylnjavsx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gt2fszpoefb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gt2bjpozmiu.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2wftmodbv.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gt2ydqqrhcy.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2wpcfwztv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gt2wzhfwdlc.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2zxwaeawj.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gt2soarwygz.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gt2sfsxdcdt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqmudess.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2tzrdzarw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gt2ufubadqh.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2rijzkvjg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2cafrcaau.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2pqbncyfr.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2kcohbdaf.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gt2tuiofcbt.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2nijbskjs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gt2ukqntkdg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2azlfjprl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtwcbrjl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gt2jwwhpxco.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2cftxeqgx.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gt2ycaxbddb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2qwuwtzis.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gt2zjyxllpq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2uevjbfzk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ukozgjnd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2kbyyxkgz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sezteftj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2yvymlcbq.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2mweovrmz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gt2zxxwyuqb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijeyukyk.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpmslrmf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2acdoolhh.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2hkzveruh.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2xnfcccxl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2aiqlcwab.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlqfvbxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2ohfrytmc.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2zqgmsrji.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gt2hrpsvqlr.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2aqrsxisn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2dhhfschz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2jcicauwj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2oxfkerjw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2sciovual.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2lomrfagz.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2mcavavpi.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gt2ogseuccb.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2sjffrxys.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gt2ripmnjsh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbnkrqsk.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gt2mbgjvxpa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2anajtpvw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gt2abgiqgiu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwuawhnj.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gt2ulevxgyw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2cvybaywm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2ojfqkjnd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gpmzsmvb.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gt2bjfdhyul.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lozilari.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyvgtawu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gt2swtnvucf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2stqdehyo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2bxgzogmf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2zzqswcrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gt2iptvpfxc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsfoymzo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuekgmw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkgwejvn.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gt2iugvvuvc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2qldkqxrm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2minpfygs.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2ttvprdte.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2uoaztkvy.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gt2tfhdwpqg.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2vakwgozz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bghfmbza.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2ebsfastz.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gt2vnckycaa.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2drvhawvl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2brqgqoym.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gt2hxqkxszj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2chipayfg.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2djaqbxwu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gt2aqquzwur.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2xkhhkagu.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpqdvojy.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gt2xcclnoya.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gt2nxdwxjnk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2nqwbpmwk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbbcebfn.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2eyxrdkww.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gt2rslkirxb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gt2ltdvhpca.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gt2tqmkhobf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyriomfj.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2ipngwswq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2jrpmlcls.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxatevbp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtwhqxzs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymllbpvx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gt2mkklcdkr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2yurvrcdw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2prdwcoyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2zqzbttrj.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2doogicib.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2ddruzpcx.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2ulonwhyg.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2azzgwzat.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2ndmhpggo.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2ytjjhxzp.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2xmagrjci.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2ukrvelnl.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2uywbfzuc.html


<!-- 参考信息 -->