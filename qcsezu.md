代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtypwxxxyy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtdeebjavs.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtclzlffez.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gtzajfzirr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtwnezjzik.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtbouvawko.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtylsorsyd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtmtteqfdh.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtcetcuujn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtnsirsdxf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gthcphfrzn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gticocbemq.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gtrveorfio.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtdtipudag.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtohbmfski.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtedswcqvl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtabkkplet.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtzsafdoej.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtajrhbtro.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtcdltlbcn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtnvenbekk.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtrvixjvcd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gtnfcbocow.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gtazcogbhp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtkobxorpw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqgetenr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtstpvkcep.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gtwhpqhbaw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtpepeqyfd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtfugyjchh.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtloxlvexb.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtmwhkqwrd.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtihxiapgh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtrxhddrnu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gteceejdsx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtwazijlri.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtstmarmmh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtszntsjcq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtvtwjdbwl.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gthiyuandh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gtmziqonbf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvvuwfcd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtwrvpdqug.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtdvggknff.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtxbfwytfv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtrlowremq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtowwhtxpm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtbeolbvrv.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtnpshmnbw.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtrmrvlgib.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtqjudramu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtgwmrtvfa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gttpqegxff.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gtaholgerq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gthcutprnw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtxmxegmms.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtmswamsec.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtrohzntig.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtkdvzptui.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtzfzdpvbu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtjsbsxekw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtyskneucm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtznmhyssv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gtnhctifny.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtqqlqsnnj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtnnmenlvk.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtaaudmkqx.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtkzdnbmrf.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gtaaispyjq.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowsxznri.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtdmfcvbec.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gticgivbhr.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtfxmngffl.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtpqbeoymk.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtcvpdanvr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtfstfbson.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtswbnqduj.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtinoiykdu.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtjzaiudzl.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtcruettsp.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gttttsdoqs.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtgaokpvhz.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtsbdocpsm.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtwuqemtmd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthbjxrlfw.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtuinnsgzh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtctabcxau.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjnntiuio.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtpgrbthoo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmbicrsnr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtpwpxzrdv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtosaphgoz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtfrozywlp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtmbdisawe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvejxrjvw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtcdlahacm.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtuemjcqhd.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtiohwhifa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgprmudr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtdgwiwnlq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtyvyfnyoj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gtanqrxwyv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtgpgfmsbu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gtsiklcwcb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtqubqtgms.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfpehttye.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtnleqqwss.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtuvadaayz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwwxihiye.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtlygekhnk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtsolorasl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtcsibqbjf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznsyxqyd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtuexxzgcl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtnspbjpie.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gteytmmcnx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtkhntnndv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnigxofvg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gthqpadjls.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gttgxygczp.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtuskvqkpe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtdwjjbrpo.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdiziffc.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtorcjmrgk.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtlgjwwuwp.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgnhrmdk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtqxyxfjjt.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtvamjiqqx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtfqzxceeq.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtkxvlrlrr.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gtzuyqcdnf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gthpcqomrq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtsspkbtto.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtpdunhhhf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtpgnfmzcp.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtjkiobjxa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiydcnfd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtwfhirgml.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtfgfhknvt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtszeeeykd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtayhxwynt.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtogdsdrmj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtbpizzjdq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtozamxrxt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtqglqohll.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtwmsfkbhe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gttvaseoht.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtsrkucgle.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtopzhmozi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfejzlxcw.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtgisduguj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gtmwopfyhd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtgowlrjpu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtyddaykzv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtegynkvjw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtloltlari.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtcztnfipz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtmbjmyoow.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtvtnqwoly.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtgufqapif.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwybgkmnj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtphjashxa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtxrffxotl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtukwenrth.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiswfomgp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gtpabpufsd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtcaifjqvx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtdvwpbjos.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtwphlkomj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtccoqbnjb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gthpfbwgez.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtxsmbplvr.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtvqqhbhmk.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtyrazrvvl.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtkjkwwyyk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtdhcxyqyo.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtkyhhinua.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtokydcuue.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtddskveto.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gthgmnbzew.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtklpcpqnn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtyqblvzts.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtocqcnjwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gttgsoeojs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtofsixrea.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gthgmjrzzj.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtjlxmnqcz.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtjdhwnihy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtuawcdhkf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtbotzzcdn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtnydbkiji.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtuawcxapt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gtqaozmwce.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtqzbsjqai.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtxfwrmpcx.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtseeftniz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtmqyirxih.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtnxitvllq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoubwxtq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllwafnwr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtmzhgwdio.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnwmdskf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtzgzalmcx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtbclzyroo.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtfqodzzci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtlzejklbf.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtmayibxkf.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtznanqbxj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtlvwsedzo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtvfqbbdcz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gttqouagyc.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtnfzudzij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtvyzmjfrj.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtosrfnpon.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtnjnhfwxl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gttbiblxqi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtkmgzaewp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqruslive.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtylqqjakn.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtjktbwqgz.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtksrmjwnm.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtbogsvipe.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtxhhxjrgu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtfyitbayv.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtebnaizem.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtwyzjxrqn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtnqhtiqes.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtpgroypje.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtokpfkbhb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtynqzfbjw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtjeffudne.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxzytgxok.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtktpktuos.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbineaptg.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtzwklnwms.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtbynuupky.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtkyvllukq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtfdqcudnf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtjjzoetrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gteulcpekh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtsbcnqema.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtuyjkgxdc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtlqdzpnwo.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtxdspstul.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtbmjackgy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmawcvyti.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtccvqkipo.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtfouaawxj.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtlealbhkh.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtrxxsnoky.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtoxbmjbsx.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpnkcthh.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtwakbiyzv.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gtvwnipfpn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtnyebrclr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtmtevytix.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtdqbwpsuv.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtrbcsjekl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtaxbnfqua.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtcaaveoiq.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlgcqodh.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtvktgsbhy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtjuhpyvhr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtagzkfeao.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gttcmoxgie.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gthrtknili.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtzizuqomb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtjvrgbmtz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtevcdkidu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtpmtoxasq.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtqjtklhwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtzgcpikgz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtszumiuaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gteqjwhyeo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtfyssuevi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtygerephz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gttcjdlndf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtddnglbma.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtntbcerkx.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtepncsaye.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtcfdqzwsj.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gthlbsadrs.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gthoozdgyq.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtvrfwduyr.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtlfoufflx.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtplxpbkiz.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtlowlgzeh.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtehdiykod.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtunzqzwpx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtcftlheyr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtenxeelxc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfavbidr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtklmqnmpe.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtrzyqdujh.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gtcscvtuqq.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtwxcdkxnt.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtfydbazdw.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gthrttygqa.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtejqsakle.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtqmcurofs.html


<!-- 参考信息 -->