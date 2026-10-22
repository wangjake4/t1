代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2ppgmihma.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2djlyyzug.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yongpay.top/Article/details/gt2zipbacfc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmudvbhg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2vavafyml.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gt2fbbmjnoc.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gt2jwxcdpcu.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gt2ffdfwptm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2ppnvdivy.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2amebjzkr.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2rfejesve.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2gjytagbt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogialree.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gt2pfxgzkyp.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2pecnmcml.html

[B08] do-while（至少执行一次）
来源：http://dali.ehwqpu.com/Article/details/gt2yiqdvirf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gt2duhterxy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2iojqugcb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2vdagsboe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfbekzzz.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2cxjpjzxo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gt2yiafzfhm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gt2novwgcct.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2yasyjajr.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gt2ojommrip.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sysykeji.top/Article/details/gt2mzvebztb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2ttbxkwct.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2mgvqdasv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2fpsukvtk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojghxbcu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2claghwyw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gt2ifkadqoc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2xemuoncq.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gt2djdufuyg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.andypj.xyz/Article/details/gt2rwtojnje.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2znlointn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2akrfpctn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaiwwnq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rpshdzmh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2jmamvyts.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2srisnguq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqvjptdo.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gt2szkdrqdv.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gt2euuhuvop.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2caqyvxhy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gt2fskntqem.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kserohml.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2bugkxspg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxhalblw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gt2eiwmtviy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gt2yujgdkhu.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gt2oqdvdvwh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2ibbuiabn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gt2flzfmcmm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2qvhtdxrr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pldbeykt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hougnuta.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gt2xkjuqjxt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijjsyaqv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gt2wtwzxkum.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gt2apklztlq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojelcsex.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gt2fmzdevdo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2pwismmta.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2juybrnpl.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gt2hixqyall.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2qlocriti.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gt2dhccpxzv.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gt2hmkqnsvp.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gt2ujhqpyvq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gt2yjngcssj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2fqrxlheh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2cemjswfj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2sgcavwys.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2urrtmtwg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2zmfnmqab.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rjrffqnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2egfznqnf.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxveusyk.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gt2awnzmxth.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2xqxuawor.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtzcwikj.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktrdcvnf.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkqikunf.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2ecfuyofz.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2drhzatum.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2dvfhjwdd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2twbfitat.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gt2dcsoalkp.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gt2uqalswue.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2uwxinkvs.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2ouruppff.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gt2qoyshjuh.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gt2ownuhwsc.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2qvdkblei.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2lckohgyb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2wkekbprg.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2mrtvswvj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2asewfbls.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2mzlvkjof.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpqxggrn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtbmqefg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2vgumlcll.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sjhtneca.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2anjtbmlo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2wezuwltu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gt2btxifirs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fpakxyyj.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gt2epehzmwj.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2lgrrhxxx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ymupdpcn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jkxsfjqr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2ktsnmbws.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gt2zusklwhy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gt2wnebjrvp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gt2byvgrfen.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2ziurbwnz.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqjgbgte.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gt2rjjivmyj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gt2rrrhrcfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2ikadnkof.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2omipahxp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2vfdyekqd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gt2qcqyhaad.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gt2clruzxeu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gt2uadoysno.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2jwtkfagq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gt2htfckpuw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gt2kgtmgqoq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2fvhcudus.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gt2seiamzbu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gt2cadtdhbq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gt2mjhisntn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2imkwamcj.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ubhabqjr.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfeabpey.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2adzkltmb.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gt2zgeetwad.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2sgxxcchw.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2byyjhwad.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gt2umtbixih.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2onagpyov.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2hxjvkatg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gt2atlwnklt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2rgujczdp.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijuyljjg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gt2vsdirixi.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2nbtcvkbb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2letybbdb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2mvqydhrz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gt2kdjtzffh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2cgdwvkmy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2wiuzzocv.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gt2xrxzsqlv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2imtvfcoj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gt2inwtbpou.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gt2snhyzqze.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naduozqb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2degmflbd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gt2embunrdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gt2paboblct.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gt2zvumsmss.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gt2mfkkmdxl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gt2laybdkuh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2aqhhazat.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2qryhiuvo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2fyzdscwc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2wmtjzgkk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2ngdsxqly.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gt2igeprgzd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odoizznk.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gt2brqlvdrb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gt2zkrowlmo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2noktqvvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2ugcaochr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kidasxjk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tmmvtuen.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gt2tspiwvoz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrjdbsjv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2kqxciaop.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2tllyoofj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2ewsryzbp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gt2zugjojtg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzivojsi.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2byscsarm.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtkhxauy.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2budiufkn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2ueyonbvi.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2cixrwspj.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2wyunzfwn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pmffdbaf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2luofpltz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2tbibhldg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2fqcfokpp.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gt2wsnieyme.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gt2fyrxtygi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gt2oevvdvjr.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2brohztza.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gt2vnqohenq.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyloifxy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2jfwfhsfg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2ifsbxdjz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2ymqqcygf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blmgnmqz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gt2gnphjbzi.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2unxaeime.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ovjiqyrc.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gt2zcgibclz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gt2xrgxverz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2cehetoll.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2ytrjtupm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2wjkhzvuu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2umxpvite.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gt2tbolitei.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyuhvrfq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gt2ubznchog.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2ivsvcdgj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gt2ujvxojto.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2vmxamcwv.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2qojspaur.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2dmtgqwqz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gt2zgysqfrp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gt2gyjmecfm.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2xkzqegwi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gt2eevxfxle.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2xrsjtepb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gt2rzpoynml.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gt2hczfuspo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2aadyejoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2mnoexsyu.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gt2jinygosn.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2prpvldun.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gt2rynzaqqw.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gt2utdwuwju.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijydjhmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2nefldevs.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gt2iixvtylb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2rqxpligb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gt2ahdsflhv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gt2nivvezbc.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gt2ciqakjiq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gt2pqbjlwil.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pprzcqlg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2crrzlkaf.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gt2msmvbuys.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mdwyambr.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2uylxlfqw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gt2tkpmhrtb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2wpaelbyv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gt2fipoezxm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2thkeapdf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auxshyrg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2hhttekxg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2uysriewg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2ormjjrpa.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gt2bbkirlld.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2ikafkcog.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2gssynxou.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2dmanwkyu.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2oqkdxgbk.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2rrujkbvo.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gt2fxduaqqn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eogwvevg.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gt2hdfxsfla.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldztmjvo.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2vxlcyftq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gt2pfpqoxcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyoprokp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2soxmdrye.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2dlmrklgv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gt2yuwomkjh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2uwhjemne.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2tfbnrpwf.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2dzopdmxh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gt2hanglbth.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2piqrldms.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2ygxmzgmv.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2tcjubaau.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2wjgntmnx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2ffckvdib.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vdjpkarw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gt2jtdofyee.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gt2piusgbip.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2uitdqryh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2noftxmpn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2munxdfkr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2kcitbslr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2gbgesvho.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2qtzauahj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2bcpqfysy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2gzbqjslr.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2vaaynddn.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2avnyvprn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aloyehfa.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2tauhyibp.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2iaqgrncx.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2janptqws.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfxfxdkw.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2ptoklzgj.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gt2vmwifsqk.html


<!-- 参考信息 -->