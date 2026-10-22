代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqscrxqg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2yoivicze.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2hmbkbuef.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2ndbomdaq.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2icjxdvbo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2xfoqdlnc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gt2mjiafjqy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2bdclnuhh.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gt2mbjoedut.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gt2ldvsgics.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2fwwhmlnt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2qqrzcgwe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2zectdrmg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnohsaaw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2yxlcgasx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gt2aogloeow.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2lwgtmwth.html

[B10] 遍历同时拿索引
来源：http://dali.iojbl.cn/Article/details/gt2kvbqnjwy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtjkhho.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gt2jhfydskg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2enjpytcu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2jeuheezh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gt2donroqzc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gt2yandtfxk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2vhqrzoqa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gt2lfmwnbyc.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gt2ogkmoghe.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gt2hcvgiprb.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2lxkyypkp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojtmyaoy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2axgzyxaz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnmfevle.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gt2ltwiodct.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gt2cegbbmmr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulsbnxkk.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gt2fsijymtp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2dlfohdmh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxqcgwps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2exnlthbh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2kxbmtlak.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2whiuliuv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gt2xicbnrpl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gt2sbvjlhat.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gt2bgybyqyp.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2mxrvgmwo.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gt2ghkdlgnr.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gt2mdyibrwa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gt2hlhublri.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2tciodnyg.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gt2rezboqcp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gt2rxylqyyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2shicyxbd.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gt2sbqceeqj.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gt2puzqqwlo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gt2emrtzckx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gt2basnozkb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2sfbvopdz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2vedrxfsr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofgjoula.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gt2zjknzmfu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlimwzbt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gt2rzxedscu.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gt2nowltbtm.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gt2gwaqecoe.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2dameschl.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2snffgiug.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2hkmljaxg.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2ncmzsdou.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2uqzrpvfb.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2smmaovqc.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2cwigzmmd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gt2lqagpcsk.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxofwqme.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gt2fmuxfaiu.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbjsyvmx.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2oazvwfss.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2cukovung.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2hpjxykob.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2uenvebdn.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2cuatmgmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ylsjrsyt.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gt2eezpejgl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqznppge.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2joatfydm.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2jsfmykbc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2ubqanzum.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2eotscznm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gqrlfpdo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2ogxvzjuw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gt2qtixdkfp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzhdmnec.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2taakulrw.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2boaziyvw.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gt2semiiklj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gt2nfoowpml.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2bgoeegea.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2tlhyythq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gt2mkosqvov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gt2fduavvsr.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huesqouv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhtitiki.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2wjcthskd.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gt2oqqjtllz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gt2ivnzahms.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2zzhtbpgj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2bskhipxo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ublexudg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikhroexh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gt2ogabxoof.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpxryodz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gt2pmzqfqvp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2nfyybrxn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2qnwlhqqs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2qxjyiwnt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2rmxctihr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gt2jdaargjb.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2raduqliv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2jrqtrlbu.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qngwvfwk.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2mkgtapjo.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2ynbiymrd.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2mqfjrxgt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcfxchzo.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2dipkxukk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gt2lfnzzqwd.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2ingkjhte.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gt2uixqwdyz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2fmsgqawt.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aormuqfw.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gt2yabngfch.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gt2ggcnvxpk.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2cbxdozso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2xotgzpyx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2crvmzcjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gt2qvzvduol.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2favnuaeu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2xgpcqslc.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gt2bysallsl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gt2welzpilf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2rajusxmm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gt2vswdmxft.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2izytmelh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kidvpvxi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gt2slgmxdlq.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gt2gpeiafov.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gt2fhzocvlj.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2tszbuusc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gt2qnpfjyvk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gt2okgctlyt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2pnbawkpz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2ttxcwaca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2skikmmbb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2sstmiops.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gt2xxcdsyuw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vexnxlfw.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gt2jixrvhcp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2qxzlrjeo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yytegmhd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2coviroyc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2eapsmvks.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2wofyiyft.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gt2rntisjay.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2vjrxcegs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2wgjhsotz.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2zluohcum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2fifpmrjw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gt2ayqeigyj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2yrzydiqb.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gt2snracxwn.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2vvyppofg.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2phztsixh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gt2lxrxmuhu.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2qjoiygzk.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2vedtijaq.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2zekluoed.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2nrtndmov.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gt2pptvmmzq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2kyxcuyrv.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2hrbbevlt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2twzebxbb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gt2eoqyhntv.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gt2vbhniehv.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdyfuram.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2siehahaz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gt2yersbxbf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2pjqhqgxu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2ceieycdi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2ghfndkds.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2twdopljh.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgvkoxyy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2kbweagtc.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gt2etxfgnhp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gt2chzshcjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2mwyztzgi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2pxemilmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2numucrem.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2pfnvdgvo.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gt2zibqxpzh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkkidavo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2njpprpjz.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2tgxzczgc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gt2kydvvqag.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2smjqzqrh.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2cdpipebt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2omsjzrgw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gt2etikgrnx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llfamgfo.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2utjlbvlb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2bhdpmfbd.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gt2yhmmphuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2dskkqwkw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2rkjvolja.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2emdsqxpe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jsozrhsj.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2pzciwyvd.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2brkmzvuz.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gt2andaxvuq.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gt2azbexdwb.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2mfthuykv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2miqhukps.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gt2uxynzrhj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zdqjudy.top/Article/details/gt2pdhyqiba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2hkewazle.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gt2bouhbwsr.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gt2lskhnlle.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2kcmhdutt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvcdgmfb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shsjecxh.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gt2noqsxhin.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhvsondr.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2vqqkuivc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcyvfame.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obrbecyb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2hvxyxtwe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2pceeajgm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2wpmdastz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrzlbkxv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gt2jmniuvrz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2bgfkyesz.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gt2yzpkvadu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2sqawciel.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugyttits.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2exqlvipa.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2sxkoecgt.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gt2lqjnlwwl.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2txpxihul.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lanoqipw.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2pyddamlp.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2hsfjdrku.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2erutucyc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2ykkketwn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gt2tqgudxdl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2kaqlhcxg.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2anvymovl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2mvjrxiil.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2jbcxdgkd.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2dlwilboc.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gt2wukoenuw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2cxbgppoy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpphwdju.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gt2ottdqebw.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2pbmuqcsn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jafsvyqy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2icpamdhb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayzqevjo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gt2ocecgshn.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gt2oiqryrqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2hhjwhkrb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2luikgjts.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2nfefymcu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gt2qkavlewj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2nqwmlvfo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2qeduhluo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2rizbkjva.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2ooyxerst.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2jzhdkgft.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fwupotlk.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipififkh.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2xnpcpykg.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2kegryniq.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2lkjcenvt.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2dbzsfdnu.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2iczctgmc.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gt2isbxttiq.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gt2ruolrpbe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqrdekvj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2epwpfbty.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2fsvebvdd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwcruzpr.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2uuxfmtsp.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2vhhhdegs.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gt2zfdfhsyw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2zbhranle.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdgikhfx.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2qvshefov.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gt2wrlkiurg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2tijxfrvl.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gt2guchxzvw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2ubarggpq.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gt2afeaeelx.html


<!-- 参考信息 -->