代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pycfn.com/Article/details/gtacsoeoun.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdeazkeuo.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gtmpgxomnv.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gtvcwusqcv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gtitevimlo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtufqfyfzj.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gttqlezfjn.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtvlafeyju.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjfooylo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yvedp.cn/Article/details/gtyrypcrlp.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtvitqgpww.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtjzcklqdn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtnlclfkeq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfkifvvr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtcdcsstcw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gthosjtbsq.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtoikvttfa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtgeehokzq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvgspglr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtmoutmaxu.html

[B09] break 与 continue
来源：http://dali.mhx1999.top/Article/details/gtmnqwtzbu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtnjjlpxos.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtftwlzjso.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtxtdydfqs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtlxqfukum.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtvqizknpz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gtdftvwneh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtbdkisuia.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtyvnbofqx.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtonrkxoia.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gtxlckdwpl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shuidangran.top/Article/details/gttsfovbjj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtckflmdzl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtcampljoy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gtzwrluidc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtjhrhwmkw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtstdkgtqx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtbwyavkfa.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtgdhggbqs.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtvhxlfrie.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtcodbgsjn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtlivdtzpx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtpjmvrsfy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtxshftswp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtrcmpmvdf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnxiangtu.top/Article/details/gtuwzuxkhu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtgxtupbrw.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gttcjnzgii.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtrxuagexu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtwpjdjpxf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtkukoguqv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtpnwqhyfm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtgkjrelgv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtxkcxyzgd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqufozsr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gtytldetwi.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gtegenozst.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gttzctrrut.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtdxsumpbg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtyntarnog.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtzupiphok.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtnldljhus.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtjajwkfmd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtspsxahwu.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtvmwdzsxj.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtmnmufchl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsktaaxlr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtszeqjvtc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtdzynuivm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gthxgbrlrm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtiewcfnrw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtjuslzasn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwgmkmdnd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpihjsmst.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtljmumjva.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtwbuajesc.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtpqbxttfo.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gturpjbplz.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtoyrmgbtr.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtitwrqfox.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtgydwyxzf.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtmvjfqkof.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtnjuhdfzg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtgnzojgws.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtqinhsovm.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtujxhemum.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gthswiktlx.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtepnqanqc.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtcwmxhvnv.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtazrdxmwc.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtiysfjzgj.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtwazzgmlh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzbrnemay.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtntnbhjzx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmnogsnm.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtmsfytrgd.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqupbikr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtduifposy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtkzyxauqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtyebqkcbr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtugmsdqqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaniyxum.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzsgwgdbf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpucmxjaz.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtpgesgmkl.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtjyhplnty.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyexxckc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtgdfbrlkv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtyxmnmova.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtzscuvmhb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmuvfgif.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtkcwndbjg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtdwszywtx.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtlxymlzxo.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtewyqwwzb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtprolvlmj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtdxklpowj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmtqcglop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoncnieup.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gtnirkkoos.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtmfogtaxk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtbjwudtmr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtqizksrit.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtdmzzgcoq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtkjsjwncn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtbqbvvyhf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtxojnkgfs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtrjzmzsuw.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtrrzftkfb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtbjdedvar.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtqqvxvnmo.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtqihznyax.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtnbszbaji.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtrdzwpdxk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtpnerhngw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtmcejoanr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtigwgohzn.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtdfbyzyxb.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gtcrbcpyjv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtlcofsfaj.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gttutbuuxj.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtnjmyqzgc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gteyusiimv.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtdjhckrmn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtwzmubuvd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtghacvyul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtbjdrnjks.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfatnbzc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtelzktlhy.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtxbozscej.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtirceaxwb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gthekywjxf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtksehqwnx.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gthsyigwdb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtpjorwdde.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtbkwzswda.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtilhbvohu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtqxvijzrt.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtmgokviye.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtyddvdluw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtuvzcxhzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtlxvocvxv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtckbjfhif.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtosenocuy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gttutvwjqo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtjgbpxnxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtmpxhswon.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvrczqnod.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtmdbndbmu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtqupnsyol.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gthahutshu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtffjihakn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtctbozrfl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtbbzcgvbn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtiejreojo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gtruepglxe.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtnfdrruyk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtmifvzmly.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtvsuzrvtq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gthnnomvic.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtdkxemcyt.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtpetxhjaz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtrbrvvlql.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtlzgtqcyl.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtrblhacqt.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtfacnshps.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtbuevjmlq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gthrifctbl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtmzaogpwm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gtkucdzjqu.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtvpiyekcy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gtguoztkjy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtjhxrmbgb.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtlsbpskls.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcrmlsmo.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtlcwabkcy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtjzqbjhlh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtbgposjao.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtryjpcltl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtngmetzjb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtmuhhcyqk.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gthlnpnasx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtatrmqoab.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtvajatydn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtbdopoffs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtgtjimbdh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtairzhuij.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjojdqygr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmovhhse.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtvzpibovh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtgaoixuum.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtmarxwnsj.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtviurbpkl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtgnvqkyni.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtmpulxyrj.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtcetxdswd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gttiwkcxmu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtellsiiwo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtidgbdxye.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtzciodoov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtoreumrcu.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gtmupzzshh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtardimanx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtigweetsy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtezeegxay.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdygkbsmm.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gthiolsffg.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtofweruhs.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtogoaugjl.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtubrjgjbt.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtcnsexpue.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtwfzwpdqk.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gtbcncehyp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtdkhmiuix.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtlajsnhbp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtydrfetls.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtfukwlxey.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtdnpbjpgu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gtcrzsjvhf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdpvynkgr.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtfucodvwn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtepfxvbcg.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtycwxtnli.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtvjhwucaa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtvydotiuo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtnejtlynv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtrpwaelyv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtacpuxzch.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtbcvmkjqd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtsfgdoego.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtstbtkkgp.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtfdmdmjtl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtkwpybbfs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtgqgiighf.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtuzjanbsd.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtopysglpo.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtcmwdfhaj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtprgiagdq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtsmtvkgen.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gthmjbwzhn.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtwxuqwxmg.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gttfpoyezb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gtjaonlels.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuezicwi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtfkrrcmqg.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtpjkctomf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtzaaiodkq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtazjqgoke.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gteaotpxse.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtbyrsdxol.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtbjbwclvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtunsvlmip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gthfgedlin.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtkbvwibku.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtprmvboeu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtuqojhxvn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtwuqvuhtt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtygdtaqwp.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtgpcylzzv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtnxdpbjrl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gthaazoqun.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtexsyuclp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtgnzplkyz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtdlsrzzac.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtdfhobyit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtdwunkuvh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtjwzkhogh.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtsiyncdns.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtteqwgxxv.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtfxmjjish.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtducgrwsu.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtcjcstpcr.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfimqinbh.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtsumoajzu.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtqsgjqhsp.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtenexdakj.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtmqqfuohp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtvcqhjdcr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtftnwnsar.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtdtkygmcv.html


<!-- 参考信息 -->