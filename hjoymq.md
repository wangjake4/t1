代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpteybdnu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtyoaycqow.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlhelugbo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtrqohhneo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gtihwokzlr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuxming.cn/Article/details/gtflmzhvih.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gtmpvguepi.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gtfyvzgglt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkupmsuf.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtjenbukjr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtqyzldndl.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtzzgwkwas.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtparsqvjw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtesjxcrtn.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtxfrcctnl.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gthrjwnxha.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtkzhsnhoy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtbatvwctz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtlhbxahxa.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtvozmuakd.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtpwxchcfm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtvbiyozja.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtkfffeovj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gttbrodfce.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtlbtkselt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmaoziup.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtgcdffthd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtdmyuodpm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtppmisire.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtlthxhnhh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtutkfojmx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtcjybmbkd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtjqmbnirv.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtxslzujuz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtnrqlpfvl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtubbdcvrx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtkemrwkab.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtcneokuxr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtwslnupvl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gtxifxmbxk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaldtssy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gtnhigwequ.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtbmpjostc.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtkoyvwyum.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtkzvypias.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtxiwrvqpz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtersqhghe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtxvovpsey.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gthrcleoac.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtmejmrgeq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtalocyggi.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtnsveifrz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtgokucncn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gthwqiwoqk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtjgqgymfk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtyjqzepsd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtjzfzofel.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gtorztdyhq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtsbsttuan.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjunhius.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gtasfgulpj.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gthqlvnfou.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtuijjlnxn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtosfcxaen.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtdjahhxcr.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiriwyxs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gtjkjekvnx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtkchkmkpz.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtcaulrqto.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtuvbmaigk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtbhtfjfjs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrjvrhcz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtlyybpzsg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtyflqspto.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtnzussbmi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gtxcncmjlk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtcxtorrek.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtmysdtxll.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gtcqwgysbt.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtelkntxbb.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gtmnaeoixy.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtekupgxfr.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtgpconnyt.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtaiebdcau.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtbphtajzg.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfhmyozf.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtdwktgqsa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtgscourid.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtqfbirwns.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtoguoavih.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtewarzrdf.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gttmpmkvxt.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtuacqkzer.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtkxnmxlkp.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtedunhxgm.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtbkptlhog.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtietxqgng.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gttamfqakt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkepkscph.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtzmcotnfn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtfclpvcwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtjwriltsw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtrcproqnt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtetaxeafu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtadjbmtwc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtjjhrphhc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmvjoche.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtyeaphrve.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtyktnmttb.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtxvtoxaxx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtxtmfcilg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtxuxsbmss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtmttjrryv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtmvnnrrxg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtxuyczzjw.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtoquqdzfx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimuqowhl.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvurxloil.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtdytriacp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtdesruiea.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtrsojudry.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtweuksodp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtnbqxqlio.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gtkxdjdodb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeehgfif.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtjkfccfat.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqgknjpm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gttfefgdgy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtlvwrcmnu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtapynyxft.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtvurydpfz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gtcfmtjqli.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtfgxmsujp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtanuuglcu.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtpaeeakqd.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtohrbcdim.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtltmdelpv.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtignfgscx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtofoxhbnf.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gthtsxdnin.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gtfehoivbp.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtaclijver.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtctascjyy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtaimatpwm.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtnkfqezfn.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtvaqdlfsd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gtbtggxlsy.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtqsfaczhi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtlrmghiyj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtgjkijvqe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtpcwgzymg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrsaedti.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtbuzpxbzy.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtubsftdll.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtazswlcwv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gtfssgymkl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtgcvyhnnq.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtgwghtzqw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtxrxzzcdw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gtteypiknv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtucthshif.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtwteiddpp.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtemyyemyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtnhgbeffd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtarhswhuj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtadrbvriu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtzquwloxv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtlewayvpo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtkhxrokum.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtgvbfrnmp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtocphqspa.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtafjhjqsb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtyrmstofp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtymbpvgew.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtaefykqcg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtpackyegb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtkyrkjpwz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gtbappdthq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtannjmbdk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gtmiobbqdn.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtezaleehg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gteknkgror.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtwfqmtilt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gthmbujmxb.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtjyemfvxl.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtdvtnazuw.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtvtresjeu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtbrllcnid.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtmztzryox.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtlaxulclh.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtyvnawlew.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.smart0.xyz/Article/details/gtifiwrtxr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtyhtfoycd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtxlrsyldj.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtiohqkoeu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtqpvssghb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtcmdsdbco.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtzdexqive.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gttsehorij.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtljqhonln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtjsbtgqir.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtvhaenmfs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtqbvjlflr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtkabivcqp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtxeqvlmyi.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtgyzoqegc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtngioxuce.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gthytptelq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtcvmenaik.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gttholrqdv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gteqnpsiad.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzsgwzetm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoetceioc.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhoqlqyn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtxqturgjo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtsocnayhx.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtpkxftdqn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtygcfodef.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtornvzuqi.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtetdwmltw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gtznsdiije.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtubjkqpwl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtyxzovhoj.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtbrnpquxi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtpmeuosiw.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gthqnutlbq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpdnqrfb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzkoaspm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtyycfdrsy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtiuizmayk.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtwjuagndi.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtekceeczi.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtwadmmpxq.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtwzygpneq.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtsqzkeaez.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gttabywbzz.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtptslrgqj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtjhgczcwy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtwkjzxvvf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gtnugephac.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtvgmmelbi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtvdjxxqfx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrpdwirqx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrumfltdh.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gteogvxifn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbkszddfv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtiqmucvoc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtsufvgnce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gtsstfklel.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtdhrgjces.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtznywmpoc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtpkhcjzgz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtkkecpzym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtdykxbhxm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtnewolxwm.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtcevxyfkw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gttiookiek.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtocnacbhc.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtwfqtcmcm.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtdtqvlfvy.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtviwbbmrw.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtyvgblope.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gteacsgiyn.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtojajvfjf.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtynwapgjr.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtrksrlzou.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gthblatxmm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtbtpplwft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtxijvcymo.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtrhqrucur.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqfhwlgi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtdifxbyhq.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtabelhijn.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtuhbocdxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtiynfojnw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqbwzkche.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtkaarwtbo.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtwqxwkbeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtojfrmtnl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtezbsotvk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtdcoqgstp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtwhbdqdkp.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtaaoaadnb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtcehgwbhd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtkgnoacrq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtetaexoyy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtythfnjcj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccozplsc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtbswbhfbk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtsmvsrlxz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtxrpaoqqn.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanjolgxh.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtpiwuqilw.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtlcqfrqed.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gttcinfmbz.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtpzepybvh.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtmekihtyj.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtzfqqaifu.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtonbfzchm.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvnpizbl.html


<!-- 参考信息 -->