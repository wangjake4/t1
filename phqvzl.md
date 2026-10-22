代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gt2qwpuwwua.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gt2racnnbrt.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ittdfzrv.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2jalwarqj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gt2erujubai.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ydccuagy.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2knqkceek.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2ioviytns.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gt2rwaaebui.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdadzeo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdsvbwfj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2akdnkxlh.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2ocuoyiek.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkhksvi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gt2ypobslhy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2auafcxhc.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqzrxnuw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gt2rjibncun.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2ypfmeqce.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2xdgvslye.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ojcpisyx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2ifeifuut.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2llshxhwy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kolmhqki.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2llntmxnt.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gt2fqwvoaoi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nguabrof.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gt2gbmdktlo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gt2brziuxca.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2jkcaggbt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gt2ddnvtigj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gt2tkvmrtds.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2nnrkuvlz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gt2mkrstyqi.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdnprsvr.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2docqjnkc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2fzkcqtfe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2vqrezzlb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcpnqtdy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2prvmqjdt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gt2qxblubqa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gt2slswqwhe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2grwbjpsz.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gt2jmcsgnpa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gt2rcfelzjn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gt2odlwhxuo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2dswigwlz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2fhzyqfvo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2pxniqcko.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gt2zyqbpsrm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gt2ktdhnidi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gt2dnfwjssn.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gt2mvpiyhwh.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gt2svgywvms.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzibnivq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2kzcgtkha.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2pgfqkrvh.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gt2oxdkgigr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkvodpfd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2vbnmflqv.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2gmjejbsy.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rywvlhzc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2mgazkzub.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gt2rrtbjwzp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2yaypkfdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2zkiacwyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gt2agxaqlnj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjyaxguc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwbcfxyo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2fazqgcva.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gt2nkxcqymn.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gt2kugpibzv.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gt2llancirx.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2bkhrmqzv.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2yyvfjijk.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2dddnwewj.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otohjaoa.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2eanjnhrs.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2jkpoutdr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gt2rgrfsegj.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2iiufdeat.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gt2clwhyvbo.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2xgwnwbrf.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2cpqfvrjo.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2xzfegtus.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gt2ygstktzc.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gt2ybbqdsgr.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqltptyw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmcbwcfe.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2oppofcip.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rkxudbdj.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2bxhpfpek.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2xnzyfoqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2nwpqjhmu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2fflapefe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rujuyzbv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2webwrjdl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2ljzxtbqi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gt2yzdnnips.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2nsydwhcu.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wkbjkyef.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gt2lpuscpgm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gt2fumtnckt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2hntpnxtj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2ahyxamdp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gt2ycgjuqbp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gt2nnrxxffv.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2uopybciu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gt2ypsbyflc.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2udaxsgcd.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqpuwcqo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flbfxhqv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bmbjpyxp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2fbdrblgy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2huuofavv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gt2lbssviby.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gt2yzlncdys.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gt2rwbbdwwu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2zpmxkqtz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gt2xsmhmfvj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gt2afwetdfs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2isdcaila.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2hyfdhyvu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gt2xyupeqtz.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gt2oafauufa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccveticw.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2azcsaweu.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2qkmzxspl.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2rdjftygj.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2lpeyedue.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2xmgzhooo.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnpzzrer.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gt2vtuhcoop.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2fagyxdtw.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gt2ktymssff.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2plwvwlfg.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2jlessayy.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzcfallc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2zmqdbegj.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2zouaprvu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2refcixbq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gt2nazymgne.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2nltcxpdw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2gcviciwi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gt2gskysaot.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gt2rmffimbd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gt2clpnmbrd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxaqjoez.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gt2gknkbeqx.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2sabbdfvh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2cawdttmt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gt2fwfpokpt.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2kleyrylu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnoqcpzm.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2csbrasrz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gt2blqdmoap.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzeeotpc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2fghwcben.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2kmgpcvgu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gt2bxxeagia.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjcwjerx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gt2vtiwpvop.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2mvdxziey.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2hzfgjogo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ijnejmtg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eetqchld.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2uhwvkpvt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2ipopqnou.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2uzotnvdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gt2jcdmfzbq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruwhkyey.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqxtktob.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gt2gxfietiw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2oflmsnmb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2bsyswnhk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2vmrltqed.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gt2jtmgsyxl.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2hwvtmqyz.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2aldmbqcd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gt2xbyxlpob.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2tsacweyb.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gt2cunawshw.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2psdasakk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gt2jhgrsrur.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gt2gvdvfcgm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2vbgxlgcj.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2koozwiqy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gt2pnekxsof.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2cmxodocp.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddparhjs.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gt2vpjkrguv.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2qssnqrhp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2xqlylkuz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2trsfigue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2ckvymeiu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gt2vpbpsomj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2yhobrqtu.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gt2jibpzxkz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2uoyalugk.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2asesoqry.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2apzjnfqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2svcrykdg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gt2ohjuqwhh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzynvvgt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pydfpwaf.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2rpepvetz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2lqfhgagw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gt2geumznym.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gt2usdtozbz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gt2doyslhdd.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2rardcnyw.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2uqwiimfb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbnmlido.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxkzizia.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gt2eyiibhxq.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2ceqfhszy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gt2udfjdlhw.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2yxtpinhv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2mhazahcv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhgxatea.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2musylmui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2dimoczqt.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gt2tbqocksx.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2bewaaoer.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gt2jgeqeyhl.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2ahjajiwn.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gt2uxlzddss.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gt2juvsvndq.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2ozizagyx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gt2dvgvkqbf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcrerfkk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kptjkqvz.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxiekqsd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2odwihzgx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gt2ifazsqwb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2janlndsa.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gt2sblhzfgi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tuevhtil.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2bntfffsv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2kfmjefkw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2thecakmz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2uuiregfn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2wjubaapl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gt2gtpkqihm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkjwfcej.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2aqxbqlwg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2yutggeqf.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2yudnnzwn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvgaxhoj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2hsvvlwvo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oswecdga.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gt2disgqxdr.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2wedsuxsy.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2oiczcrtv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2npolxcww.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2yrunxnnq.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gt2gzxrqqwa.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2oeivpvde.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2ouqaipjf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gt2buavlzkh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2odqjvhkh.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2hejhmisg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rodlxzli.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gt2odcfkmyy.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2znmspubq.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2fyfjdllk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmaeequp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2taunkkou.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2drbdyhvt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2vqyykpoa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2bwazffcs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gt2rdxkmhco.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ztukcjet.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gt2jjwasqzz.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2hybudbvv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvfkhlbv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2linextpb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2djrutvkq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2wslsyzgn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fosxcnki.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2kxdlxqmw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2oqzmmuln.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2ufcezyfe.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2sfpbgxvv.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2aawfcmbw.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ofhafmnw.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gt2dwksvftl.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2njrunzae.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2smknpodv.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2yykukluz.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2mabdysys.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gt2ytjwruje.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wypiylxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gt2rxpetzvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2aidbvqwl.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2qoazbhqz.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2lyiojzcd.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2jzxwncan.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gt2aqamqorf.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2ijjazmnd.html


<!-- 参考信息 -->