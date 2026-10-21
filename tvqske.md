代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtwhuxxive.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtvquvtsfl.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtxhwnyaow.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtrbfdrcmu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gtksudevak.html

Ruby: while i < 10; i += 1; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlcxkxftt.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtnlzjyqip.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gtwpnkroru.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gthukljvrn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gtzyniiyzy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtcxeflupl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtdvfphehs.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtqdaqppdv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gttklyyibi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtuwvfzfvf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtebmkstpf.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtjdpqazpw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtxuibvfej.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gttetxwabb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtfqzioqoh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtluljbkny.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gthinhutmu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtyactbbdz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtdxownfwm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtkufvvmig.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtajwfvmnh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gtkqrrezsy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtwpuhoeob.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtqdegvifz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtvmgzrsxr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtbsrhpvfl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtdsnwzvwx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gtzccfqujx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtxiyuscqn.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtgssuvsin.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkucdvshr.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtnwlaqmxg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtaddjoiuh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtqxfovmwg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gtqcxjfwzy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtrdkfsyvb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtaijynact.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtomjmnsdy.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtgbluwjjq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gtlvofaeha.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtfgiiuvku.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtsefmoivt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtrtmtvsro.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gttrjkouit.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtxnugzxgk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtfdgmwqui.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtzukzerxc.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtbqixwugw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtttyuaoif.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnvwnciri.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtqyayhqyr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtptawnzdb.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtddgkklui.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtoaomjkbi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtxgtyvlmz.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtmyhayjgi.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtvhkbuixq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gtljrfrsvk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkobccdhy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtabybebbs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtzxhcrbps.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtecqddinc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gtjnzhebsj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjvccfzt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gteoykyoes.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtiverjero.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gtwsdsmhrn.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtyrxegwav.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtfegpzvqh.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfskmrrtj.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtkinndxgr.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtlqrfcpzt.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtfcxrrwdl.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtaxjfwffv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtyqvmvsgm.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gtqwbkhies.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtpkobvroi.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtorplhyfb.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtylhiobbp.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtjuodvuaz.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gtavymmfsp.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtjfqsunfp.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gttdjuowwd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyetmrasy.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuuvuhsw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtknmepfco.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtrfpldjot.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gtdunostzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzpmyfvaf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtqnaezltm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtwrbavzpq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtbsuqgbog.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtsnharrso.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtxthbqsdq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtddmtntqc.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtlxvnmhed.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtcqvrhvvv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtajmxjljy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtlfuzpmeg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtsdtqgiut.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtukmjbpbi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtqmhtjfdu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gteiydodwg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gtfjjbblsy.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtrbmdpqhb.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtonslmakt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gtsypuydms.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolazataw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwvodeja.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtauyumhqe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtafwfplmd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtacradvmt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtdddposvq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtjmoiwywi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpdnnsbp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gthzpuaagz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtepfsggoh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtdxrthebr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtkakezvcs.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gttocypegg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gteyvbhtsi.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtfrjudcos.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtamoqihxh.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtaidzqgxi.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtbyaxuygv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtrrupqjzi.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtlibfzjje.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtrsdgcmae.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtgxhhvxij.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtstxkyjfw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtyymoxqho.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtkzstczzk.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgvhekxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtyvksdthp.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtuyixtbva.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gtvmymkjqm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtglvtbaaa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtwonzamgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtkhxemfjw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtirdbnqiz.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtnbejoydr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtvycqcukj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttsawney.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtowvinsxj.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtdqojhwgo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gtdkvajujd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtinhweqmz.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgavgyme.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gteokqngeq.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtiuxozejo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtrpfpbodu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtanmbbwik.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtpxekplqq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtriqinggb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdtsbxkm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtczdondix.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznnfnuva.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtbwnpmodw.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtgkvlqe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtduqpbqbr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtmarklfoc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtmnjsarzb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtmeeispfn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtiwbjezwg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtxlnkasea.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gttulwblta.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtfdjvhlzi.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtmkcxkvyh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtcbfhcvjh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtgunsfgtk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtjlntzpjv.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gtwqgsfwvo.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpqcdxig.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gteyfewsmq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtxwjnomvf.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gtdojcmxij.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtxsjxnzpi.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtxymepqwv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtnvhzkscp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtcsaknlrb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtwgnpqrjt.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtuxdhvkjg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtdkavzdmp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtfylrxrze.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtaolmtleu.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gttlhakfyc.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtcqdphwvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtohdhojin.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtjlbcpang.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtoiipgkoe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtrkpzxdsx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtukmfvmhj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtvihntuqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtgeaiugvb.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtjvuylybu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtcpbduxyx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtaszmgwvl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtllfvbfzc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxzivcctv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlsejrty.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtpiefjncc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtnjjfbdgd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtkimxfylg.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtxisjribn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtwxhtzwye.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlygmvemd.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtrokbzfam.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtwlghabxy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtlrmpwsrt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtvpkxwinr.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtsighplql.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtsrwkrsdy.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtlfpuvxfs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtvnoulzdo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtchdjsjnf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtohzzetnr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gteuyxjpim.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtoacklasc.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtovsytplj.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtwxbfwiie.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfevzdle.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtxxstrxhl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtxtrhpbsm.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtmfvbyxye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtkwligsom.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrcfpnck.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtsguircms.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeipvsco.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtskxjsamj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtxispxggy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzunoavsm.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gttztuvuxm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteetfllgp.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtaemhcppn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtcueypflg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtdrnlnrxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtafleqwha.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gtlapesgph.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtejqlrspl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtiehfgcka.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtpyfrvqur.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtmhbbilre.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtbfgjzaru.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gtxtocjeto.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtvsphsubc.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gttbvndvxb.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtwzklgflo.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtkqnqapun.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gtfegzsxaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtqverlbey.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwxpnnss.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtgvcmtbyo.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtxqdbfojz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtbzysmdgh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtztnldgii.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdndpnihc.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyezpeai.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtcopjpuqv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtquqrtnyf.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtbgujdvzx.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gtbygzjtgr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtncysivxo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtqolunoik.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gttndkflgs.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtdmlguonj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtcvpuwyuc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtpinfldjc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtyoqcksbl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtxsfoaupc.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtzxezqznk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtfbkgmjzc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtzioflpob.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtleiodhla.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtlpzrigok.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtylucwcwf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtzplnknbp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtrerhvwnc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gthnhmcuex.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtvwwvtdan.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqixbuuui.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtramndlth.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtmktbkiji.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtgmgrcjyd.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtqnniqzjk.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcdkfquas.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtxdebeygs.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtmbhufbzy.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtqcuqrggq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtuezheatv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtigehilxq.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltmtkngd.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gttkzvjdfa.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtlkxmwjkd.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtvuvdysvc.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtgddttrws.html


<!-- 参考信息 -->