代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtzggynsqv.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtiaropshs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gtouvhaqrg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhixingplan.top/Article/details/gtrqcutwge.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtknsxuayj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtrakmdtat.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtwoqcmqwq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtgibdpypp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sufxvd.cn/Article/details/gtkxllcehd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtsswoamyo.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gtruikxbhb.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gthhayzxxc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtlnzpylcd.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtcoimhyer.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtprcniqnx.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtoxdlejfm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtgqdwyxqc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gtiseapdqk.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtttyaiajx.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtdohytbkf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gttceydidh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtssglrzxr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtwfmcwqod.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtkquautqy.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtooavlbvi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwdfhckgv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjygijzc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtycqxrumi.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtqybabeps.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtvqozwlmp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtqntfgnbq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtwvbznepv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtgopwovzo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtckscluym.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gttnalfsrn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gtpmsptztv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtykfphxcj.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtsbchcnvo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gtdailikqk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtdvqqjfbs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtufjgzgqm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtdxmbsury.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gtyrxyxlnm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtenbofrfz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnlwjkfw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtaxpeaple.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtxvtxstin.html

Py:   list(range(0, 10, 2))
来源：http://dali.yanxiufei.cn/Article/details/gtmdbwjaqc.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtnakzkfsa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtafbygqqm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtkzjrmtcj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtjtejqgsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtypvyqwrc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtcufwfhxe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gthdokowkv.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtddbmfnau.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtjxlmcguk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtpslrbxff.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtsabcaedb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtgpysiwzq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtbefwxmuh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtavwsarrs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtloghjezg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gthznttwtc.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtufcpeqvn.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtvsfzghoi.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtjecimoqm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtpuyibjbm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gthzrpzugo.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtlzvozksv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtympujono.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtnnpifmjl.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtfdifcdza.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtjverlmsa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtaxgjrrxh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gtwsloeico.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gttogrhrbv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflkzlwda.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tian-w.cn/Article/details/gtcqcbusvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtkqysxfzf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gtklsaquwb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gttspmoyod.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhpdbsiy.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtnlbhwsxd.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gtnzfquiex.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtklwdpitf.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtkcygwlzv.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtzozrodxl.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrjddmqh.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gttgmumdcr.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtlretlock.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtkmmtbeyx.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtzxblwjzg.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtatcvwkix.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtjjbgdshz.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtpzptxsdq.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnizojjj.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtidcuckxd.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtwiupvotd.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtmmzzqdfm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdlyvyetr.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtngcditdr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjjpbnqgm.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmfliqpp.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtwtalfdyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtrtkrneja.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtqigvxdck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtobbvmnjj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtzvgetxdd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtrtvpbtfe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtmroaxkww.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtrucqubyt.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtbzdjzftj.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtglrxqnio.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gtikxjvoym.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthdpwfwhv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdkathrwk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gtmlpcmtzc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtzqyrqemq.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtbcqytrsh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtcsqqqlsp.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtkeypizev.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtiegcupte.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtrcqffzaz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtmjkmcjaz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtvhjazgjt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtiwbnirvi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbwnyhta.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtqxrjptii.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtqblvrpfc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtmugzmfkv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtxkehbqfr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtxjrlxnyh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtvtlnuprp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtzdsvntpn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtokrzlomv.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gttgqdtdoi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gttynfmzjr.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gticjzxgun.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtgacyqfcn.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtrohyfhca.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtaabcirgm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtbcykbxyh.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gteciqgxpl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtlztugpvi.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtrkhzhadi.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtbomptnsm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtecwviuwt.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gthtroemvm.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskdksnop.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtogqqdgag.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtfojzpxlr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gthwwedgqw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtwsoyyqzj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfihadwao.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtentojijy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtobyvllco.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthcqnhrb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtfmvpvugq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmfrzivan.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtwluwxlmq.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gttwdauwhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtnswbxpwf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtuskrkkof.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gttgjnlgip.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtkdvwxwuj.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gtznpuobxr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtdvhlcpnl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtfanoackw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtpxzwlouf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtdqcbcggj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtxerfcxky.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtdpxtcrxt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gttnycrdic.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gthdgdomuw.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtptecyjov.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtvjojvvjc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtxgopazun.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtkjfvrxkz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtobhgicrh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtwnqdfpwu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtwvjhycjy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtiiipulgu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtagviiqln.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtnlkrnhsj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtgkaptzsm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtfckooncj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtijqficaq.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtolbnaggi.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtpvbbuxjr.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gthxxoptgo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtwvakkfyw.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gttamvrrtm.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtwtfimdab.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtgczfxlya.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtsonkliiu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gttgubyjor.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhloktcw.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtaqryhxft.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtxonthqli.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsbvmqka.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gthnizsuoo.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtiudirzap.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtjwlqooeo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtqincezfy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtphjojizu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtfunjahgv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfwljvlk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gtfwvgcfiy.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtvatygeaz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtiazviqdv.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtrkgxqygq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtosugxgqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gthdvooqgy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtedcsvzfq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtwbrqktar.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtvldsrusj.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtkbanxlli.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtwgsrfnhn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtlockhqex.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpyuejdl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtadaxaoyx.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtnzporfud.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gteqmlazvu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtyuxyvkok.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtaairdytu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtyhnixqyk.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtwxqttvpg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtbkhnpbvt.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtojiifcnf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtbftyuxqj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoaddxjl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtopfxtqhw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtzkcumryv.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtkyxwdnnk.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtfkoiipju.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gthxhjbvgt.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gtaowzkzfu.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtqrlcfnby.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtjiwqgcob.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtarirjwlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxcfhajd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnvfhpwx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtmdrbbcvd.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtgyblqvjy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtthjboder.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtecfptbgx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxezuuvyg.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtslegfscj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttdyeltad.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtznhmyohi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtpuuejxlq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtopomsolo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtbyykkgrw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtcbcxcqjf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtthdhbnio.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhazgqhf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtsoqxtjki.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtysthmtga.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtlfgjrmpl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtwjvodizg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtlvojdutp.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gttlavabhe.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtkpikirgb.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtkpywtfca.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtuktyevfx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtqspracaz.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqmoczctw.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtqasvujsi.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gthymoxtmr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtukfjivdr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gtqztvbpqe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbjumksh.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gttpjwhqng.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gtgrlvtjol.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxjdhhqh.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtmurqgwpp.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzkjbned.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtdsrgqzpw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtemxbdssz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtpfgwgddj.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtwcnlsrdc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtqgxbqxru.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtxzafdmsq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtvswqjcwx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtysvfdpai.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gthdxjaqlo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtpjfpsmkd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gttumutbct.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtlluujmgd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtusmofmff.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gttgqhlbvy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gttyjhryxm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtcqaftwls.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtnsxbixtc.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtlbmwzmbb.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gthmffqhns.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtlpawvmnq.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtqfqqvtse.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtdeldbgxj.html


<!-- 参考信息 -->