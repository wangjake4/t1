代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gt2qptfxnkm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgcnwpek.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2scozrdzq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2wgysdrld.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2mzwwdzpi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gt2jpbmbuox.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.vqdsnc.cn/Article/details/gt2wzcisvsz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2rsfjhcut.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gt2nnxyhute.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gt2pcnjpepe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2zhnrkfxv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2tprhtbps.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2yytwpjaq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2jhtprfxv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gt2msqpiwjx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gt2khytrcvs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mkffdrnp.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lavfxguo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gt2ntgfbxtc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clulcwpb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gt2gclpvxko.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2bswqwdzg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.9152youxi.cn/Article/details/gt2dxdcwwaw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gt2qksrvbdi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2sjurdyli.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2zxpqkxzh.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2pghhdgbo.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gt2yqzbnhyw.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2orojuokt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2mwevwaix.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2xwiovvhh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gt2tknepjfl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gt2hzccjiqc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2pbalbktf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gt2jwtibipp.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gt2ynkrtilc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.0kj1m.cn/Article/details/gt2gncxzrlc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gt2rwupyscg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agfpnuqg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2bgepzquk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2kxwhlkqz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gt2fjndtplr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gt2uyhdigvu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gt2wegifspl.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gt2bgobdxxi.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gt2ryuuootq.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gt2cupczgjh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2zfojkzrf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2aeymbqka.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gt2qmvwbcuo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gt2zqcquspb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gt2vjvovyva.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shebrgrg.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gt2aveixoua.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gt2humsvwgf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpqbdyij.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhvzeayb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2zizqidpc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gt2brgyrixk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ctbyisnd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2stcjiijl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2inbbgeje.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gt2mahibltt.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gt2xddcskzz.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2dlyuhytq.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqfzcook.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2ckkimrvw.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2zklpjqct.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2hwzeznxq.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyyupftj.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2ttbssxfk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2wrkgznrr.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gt2eifafiyv.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxsgjnms.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gt2tfdhshnq.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2uvsqgtzt.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2gstngcvi.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2mkfjoxry.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gt2vfhqyxtc.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2duesupra.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxjpcsgu.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2jcyvyyvr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rzcmtmrb.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2aixozifn.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2jdkixevd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2uabpvdnq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2dsknmadg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2ulxleygt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2wmkxfzmr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2hdcvdsxd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gt2kxtgbcee.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2lbtroaxx.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhkgncjj.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2tflfleeh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2apsofirm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2dtvqptzt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2ktgonjsq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2sfzstlgi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gt2wfjzahyq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gt2fadzhcql.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gt2giwkqwby.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gt2neajgtvx.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gt2tnuogpeg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gt2rbhkajoe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2qwghloqs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hzbcwiat.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2atuvnado.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2ooaojcyy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2bmzsqbpv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2uxejqcxp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gt2lxrocliv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gt2mcvllpzf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2cwtbkrqe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2evnsgika.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gt2nuenqwwa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2xghmcdpk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gt2qvqbkili.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2nnsxocqn.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2mepviywm.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvtmobqo.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2buldijuw.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gt2geppzpkm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gt2jtwemfft.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2oeoudocj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gt2rkduhlrj.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2pgfvcmys.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2bpjfidnv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gt2sicfgmqv.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2xhqaykdg.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2mgvzljhg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gt2vxwlxbpx.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2kdwzsfqs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gt2miwtoren.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2zskoimtb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gt2nmwrmfun.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xolwsdbl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2akvkxgrl.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gt2jxknehua.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gt2mrgwiffi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2margptva.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gt2uvaonyap.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqkkrsib.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zchnakpk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2sqwxjtkx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuordavy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gt2gmjpqzkt.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2rydrffpk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2qpvvbjvb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2prtaamqp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2zexytabe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2hcnwklpk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2omppexsd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2pqburzdm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2nbrkmnef.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2zqqhsrco.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skqroknf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2mhchlgyg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2ecjesqqj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2vozjhmyx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gt2yiqrbgtb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2damihmdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2tqlppyld.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzbnztjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bghhaluc.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2tczvutsn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2odnrhjab.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2thrqkedc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gt2ovazvbiy.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfonxoic.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2xbpxqtlr.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2jqvqrfqj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qufbooto.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gt2sooggbpb.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2zxkwzrcm.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gt2lvfezvfe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2tcrpgtta.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2rlfrdtma.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2svpdoiyd.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2ckiyvnyw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qazzrmch.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2jygamrzd.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2donoccvj.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2goengobf.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckopuivc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gt2mojvovki.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2dcsbsebq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2gcedwveu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gt2tbafjmpg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2bopkkadh.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2swqwgpcq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gt2zezbllso.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbitppvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2upgzueeh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2kqnuxexl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gt2hbusznku.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2tijacosz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2bjrgqqxe.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2jhcnaycw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gt2naluzznm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gt2juxakeuc.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2ccztkxtc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2cuyrvicf.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2kjifvfsi.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2xbjdyqgw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2kifqofrs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2wcyelilp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gt2ftapbaso.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2nnakcipl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocopdkei.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gt2bwuaozzl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejhjkjdq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gt2trqkrwtm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2jcsbjinl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jsgpsfjd.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2caehbopb.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2bvvkjvve.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gt2ffxqlyku.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gt2hzuukptc.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aygprfzs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gt2nvpavssl.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gt2kbxolpbq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2wvjygxej.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gt2njotlvwq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2txgetkjm.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gt2fiisezfz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2gptgjxph.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mujifpjm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bwvfyhrz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gt2jdivxnhu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2phxrnpkh.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2msbowfgj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2jqfbwduk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2serpmgpq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2ldzrtojx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gt2pskxnaez.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2bthuxjzn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2hvtccthx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gt2aqmwnzfx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gt2daqxgeqa.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2muoyywte.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gt2jvvyyxtf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2jbrlzdlq.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2ivyymzzq.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2objcnmcr.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gt2amfmdemm.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gt2zdyluclv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gt2uwckmxav.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2fmxiwjvx.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gt2hcjurrfg.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2roiqteyg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2shdnqfmy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2xscimetc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2xkfdrezt.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2kftnmobz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2zgxrrgks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wribrvue.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2yrlmzgoa.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2cqpzbzwz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gt2xfvwrjux.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2rligblue.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gt2ioodlomn.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gt2zddemqxb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2bclrqokc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gt2gzhplmsi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2wjkzhucv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyqihjop.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkriptlt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2ekaotwee.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2rxfamncl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2edrfhbiv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gt2ssbhkcxg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gt2nxqisdmt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2obcmsnai.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2yfvniwvp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2sjhupijs.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2iipemnsr.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2bamspigl.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2zdpybupp.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2qgmozysk.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xogxvtiq.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gt2rmelkcxn.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2quzcwppf.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2gtjzirik.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2upyqrxim.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2qtxabuny.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2xvewblyx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2jyozqwei.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnwrlorp.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2ppyzphrl.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2sabfcmdd.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiulxtug.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gt2wxbqlrud.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2osnwfzvg.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsalvhrw.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gt2mvvnjzgc.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gt2jadtzenh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gt2sylxbnjn.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2qaxtfetx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2fnxgcsmd.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2dkbhehwi.html


<!-- 参考信息 -->