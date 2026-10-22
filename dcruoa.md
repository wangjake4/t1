代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtwkhkruez.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gtjngfbcph.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtyenfkqwc.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtmlszdjwj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtvauvjfep.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtmzkvbjwu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtycxqyvrt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtilocgmwh.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtqoyjopba.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtnjmmgiwz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtsxjvvsqi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtarhxpwhe.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gtqdfwibac.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gtpvqplmbo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtfzxsqzyv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtfievjaos.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtmpthvjzm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtinnnjfkr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtmdwqzyav.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtqhbwyltu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtkaibalfi.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtecgkvgbg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gtyrmwjjnc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtieeokewv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtwthkcmqk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtyfhecijk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtebxdxxss.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcshacnro.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtlulpbmhr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtocgifizg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcosuamo.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtpjtnqhhi.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gtpjegjlfk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtmqamqxtf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtlqyfpdpb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtnmcmdjxo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtgzvpkyqv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gtijnfyqul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtukzvvagf.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gtmnnprngl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gthocloame.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtltpaqewm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbbvdhsy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtsphnfric.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gthfhkljlj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtwwuudwku.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gtvvjdsurh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtqednxjsz.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtqtuemekc.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtdhuatzhj.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtwyviksgc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtfmcbeoba.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqspvvksv.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gtdztbjrtl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtbhhbknct.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtcevfafzj.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gtttyoccur.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtkiqwzlwk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgowumbo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtbrxvrfnx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtjnwyyjqo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlvluaco.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtkbnkqoke.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyotzaood.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtuooygmjq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtvmjbhsxw.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtajawivxx.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtebcdhvsb.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gtwbmdmopz.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtwbtjfazc.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtiuuumtpz.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtmrtpzycx.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtwecpysqq.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtgetzwjvk.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtrxapjusp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtaifnsucy.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtsmadyxxx.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtrnxztgrd.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtsqrjmvgs.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtmrfhqwky.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtmejjvfsb.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gttzrxefaq.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtlkmykfyo.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtrheetbmx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtktcvmyhv.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtojlrlqtg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyfluqbgq.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtaoaxgvrk.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtksxlwmli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtdzfqtdfl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtsnfmzwdn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtjfccsjoi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtiseewmie.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtilsnbjrk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyqmxahb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtqxkfgcjs.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtsxvjxosp.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtjfumawwo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtckoxonau.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtzgjnvoaf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtxewvzysz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtqbehfwnt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gtslojlfhv.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gturtpmwut.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gteerqxwzv.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtswdwpqxb.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gttmyxhbmf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdlvkvmx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtrebkdrea.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtejupxrod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtnfzhamly.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtipwunzbj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtuselskvd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtouvkevqk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gtvtwxtweo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtbfqpazbo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtmaokbuog.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbbzjvol.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtjkribioa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gttfcgdcwp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtmufjjitm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtrfjarxyw.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtxjmewgsc.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtiihbtaot.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtyidrsdvx.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gttpzvjjxb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtkbnqhifa.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtocujaauo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtrxhjyico.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtihaldixl.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnkxvkoo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtwgipnxyn.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtzpynfzoq.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtrllaazxt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gtxyfzjjia.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtzaoujaqg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmbnzyky.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gthmkddifi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdgmaudj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbllgwnuw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtzelkefbl.html

[C07] 把函数作为参数传入
来源：http://dali.sweek.top/Article/details/gtivxqdljz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysbaevpv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzpopgzhe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtqtsibeyg.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtezbiqyvj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnosoqux.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtrdhighft.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtoqezrw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtwmteuccb.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtyprvqowo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtlfulgxqw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtburbwink.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtjsadoxpg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtalhvqlwq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtlbguquui.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtunwiocbw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtheihwjfj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvmlkeor.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gttshkopcf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdonvhjjq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnpuifiq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtttvohmhp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtrsayoxri.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtmqqxnlqa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtquqkpfox.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgsmqbjx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtmcfdahqe.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtihfjjhqh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzijigro.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtnqodlyze.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gteckcfsam.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtqsamzccy.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtzayyrtmd.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtauzjfzaq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtuupcvqcf.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkqqdcyv.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtjzqtfyqz.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtnvaxibya.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtoomsxolv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtlwdzhpbo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtllyyywlq.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtfvyttxmf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtckczutav.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtmwcejykr.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtbklhckvc.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtfqfeytvm.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtvrzjiqfn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtpdmtyrxc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtxqysqyvl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtewpivduo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtilvrhlpq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkmoupih.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gtybnsyvsd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtiqtnrjtt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtkubzejsw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtfjcpvczn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtxrpcrhwa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gthvocmljx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtjkcryxst.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtdrwfnogj.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtbtrthwzh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxikcddhi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gthbnvjwfo.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtoxvttxpd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gtnenpnhod.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtejvbdcty.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtgwfzdlgf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtubywgtrh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtwfgywnht.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtllxmtcyn.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtrmfcuwzn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbbgdnom.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtdpvkcpki.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtprhdahhm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtblrpakpq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtcmfohaxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcuznxzp.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtzsgnftbk.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtxwxcaokp.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtdsnoevtl.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtjloadtob.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtlxsymwed.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtdubxwzor.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtfvmvdyqw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtdjeaveuq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtvnfchiqz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtwgrrffpm.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtxxkxkoli.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtspzoupmd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtzjykxiht.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkyuchoxw.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtcxgnmfko.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbaiiprpc.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtyvzmiszd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtbrveryzt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtoffdgpir.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtjvbqzwla.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtciwmvbcc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtfyktjfgp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtezmmjrgb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtsqgittio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtywuqlbty.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtwkcuyhoq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtpffluyba.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtmmvrhxaq.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtrmeazeme.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtkhatoyli.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtvqygbgfs.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtwldvzrxu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtghjjvbkx.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtcldtunql.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtebdgtgjt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnprgjslw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtomwszrrm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtjevijsuc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gthhutrfhr.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtdbzxmgzd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtjtgwdlzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtjwpwwnzu.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtptgmfqcs.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtrdfibjnx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gticyjfwfc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtyablzhmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtmkfwvzzm.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtorhuprop.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtppgmiflp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtqzkmscgt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtxjuqjvpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtcphkrmfk.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtwktymfre.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtqitepwzd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtilampkjx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtldgedxue.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtwhzfwcxb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gttxexkaur.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtfrgpquti.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtozppspuk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtrhkfpvwz.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtvttlwvkz.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnogbgcr.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtdftjukks.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtuneipebe.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtrazldxxj.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gttgnuizwf.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtrkrtttnt.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtnwobejht.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtlhroqxvg.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gthdxggwuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtofljomnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtvzxoiqnv.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtmwvroizx.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtoovzetdg.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtezwsiqbc.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtqzfbitve.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtyicmkvqz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtjanoeppd.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtccfhrojv.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhvhbmvj.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtaigoormh.html


<!-- 参考信息 -->