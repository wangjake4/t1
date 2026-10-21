代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtauoidfqf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqlqonxbe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtevdhvhqb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gtnyjipkdx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gteirmwpsi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtlcixznzb.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtxquxfihg.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtmuecaxii.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gtbvtziszt.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtmcdiggbj.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtjglkvyzy.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtdsbmbkfq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtipfwwour.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtoeftgpig.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtrywkjyvd.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtvmkqzqpr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtxrmlomyv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtnzotivoe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtlldnggeg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtxgmjhqcl.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtpfgfjpdc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtjexqrbxa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtfsbbwhbd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtbuojijrj.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gtseyudkja.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtwncvrect.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtrzzznxrp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtoaxfyfjk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtsdrqzfzi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtfrblpkyt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtgfbdeyrk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtjmiswwbw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteyoghxxw.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gtjnvhlsma.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gthoabivqz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gtfcobbbxb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtmufubkjd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtamseugam.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtnernjqpb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtusgwnkjw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtsyezcynn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtvuhsnstd.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gtqapardgz.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtejlpxqjy.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtfhlurfsq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgziznfpv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfzcxzqh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gthkhpwtsx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtgqqvmpkc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtlbmsympn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gteljxatuc.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtlyezretj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gttdgnjffj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gtgrsciqgi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtltzynlfr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtuqtxqvug.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gthsthmixu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtcatpsrkp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtmgnrfdfj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gtgfcqvvuq.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gthorfomfg.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtlgzvuymv.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gtibcdvdhp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtjksfqmwc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtllaqwoer.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtdhljhpvm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gteetfzqbg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtkolgxkva.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtmdweqqoq.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtkbrogzut.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtwyvanqjj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gtcgnsyqbf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtabyvufqa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtrsibbhhg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtnpldcyon.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gthmgfnjvr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbarhzfyr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnpqrsxif.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gtncjykhvk.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsawslup.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtjilrtpoe.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtzujsmbiv.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtenjffzlj.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtskujdwgx.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtsfiwmmtl.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtcnlmsewm.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtiibrbzid.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtxjspvdht.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtojygsuvj.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gtbhdujgrj.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtpycfmigr.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtufifebfn.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtvsppnouy.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtwptazgxh.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gttfhaewnn.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gteqgbiklf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvtevtgzd.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtatuaioje.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcqnqewqq.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkkwkwws.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtxsjotdhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtsfayysqc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtuicedtud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtcxkthocn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtuzucwpzq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtocnzgyxp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtkxovfhld.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtalpajmva.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtegtmetli.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtimhejkoz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnhxxdbik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtwbqanpuj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtktbybhqn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtgvrydycf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtlgidqist.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtkfkzzdhq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtvppbnsec.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtcwryhdxx.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gtqcxudwis.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdayjpdh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtdrrurcva.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtjzwhlchi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtgpaahszm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtwktrpxcm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtqplcsopu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtpwomtmfb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtjkrciiee.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtzhmutjxr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtnexpynpw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtdmifxpdq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gturhayxhl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtyhrimavc.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtbqbecauz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gthzbxdaty.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gteepzcifo.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtiifudcvj.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtnplaxrew.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtfroqblth.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtoetecexe.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtwfsjmkuh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtwdbataxr.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtehktmdev.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvrlkycl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtuswnypxg.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtrzvoecsi.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtdwlsdykb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gteofcjmjl.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtpqqcgyxd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjhsxjd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtjutzoegl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtulokpnuh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtylntrrxg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhykimoq.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtsgbbfpbd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtnlltyfwy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtgbirmmkf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtggddodid.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtiiscnqja.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtocwxxlcd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtyifadbfh.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkobawhga.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtzqwsfkgx.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtteraddbf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtklhqrtta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gtcztbzjoe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtposcszjb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtcjeznnce.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtamcdyuvc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtsmfplbgo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtieoltezn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtuwxiiivv.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtzsypprii.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtonnjskhm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtjqekksef.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtlwzlprfx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gthyaijmeh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtdqenupzt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gtoybfgona.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtdfbsemws.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtfnlygujo.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtsvscpeov.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gthdydtglt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtqixjhrhd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtjqibmssq.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtdhoovmsi.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtmhytxkal.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtraijqihu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gtkwwxkgeo.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtzymhhlac.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtiegezpgs.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtmfsjyokf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gttnwxhpig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtlpecnruj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtnbbczado.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtcpvxainn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtzyowtgcd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtwkgbkyjh.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtdtsorvow.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gthujpkmrr.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtnvhrcbzz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtxtpkgfnn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gttetrekgy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gteykiodto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtiyrphzvq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijunrsuh.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gtlgsbkvfi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtmyyimgsa.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtoretigfd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtndmyrzux.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtsgulszon.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeuxkouj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtfcgbcmaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtiwaysgbd.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtvnxmjntv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtfbfekdqe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssbnjauz.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtzpjthvon.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtawnqivnr.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtcskfoxup.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtrfpcienr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluqpctgk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gttqclxalk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtqbfufkdf.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtuxpgsmgy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtmcazuycl.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhdjjstq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtjwfxrgsp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gthbccfgtv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtdminaxgr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gttxfzpkob.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtcpdbywlt.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtgxaejsue.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtsbpjtxaz.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtmvjergba.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gtwkbtvqmq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtbgonwjmt.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtskcjhfun.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gterwqedkb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtmprppoxa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtlncrzvwq.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtsqsaodmh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gtwvahcyun.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtveobtdhn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlangwstn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtitjazthn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxthrhksg.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtlikevzrn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtngztuyrc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtbnxiupzs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtyqseuhkc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtetfrjcga.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtjzjpmhsb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtrkwbbtta.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtrzesnjcm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychemyny.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtdhtnrrai.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gteicljjhe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gthfvapmtl.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtthtwrgar.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtfvyaqahk.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtmzapnlcw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtozzrbxvn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtsfhwba.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtzwmncjjt.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtznzjrjxe.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtuqgbidhw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtbqnqukau.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtwjgyvekg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtnroqmbpy.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtjbvjdxny.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqkyxfsr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtqstknqbl.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtjdkcsryc.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtohsptojy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtebzhvbor.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gthmntxdxi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtztlhebph.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtfaaedetl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtjulsbitf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtlqmjuxnq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtzpjpsqti.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtbolmecqj.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtfdewzqqu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtoslxtach.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtklutmfoc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtmkeamotm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtebrdxjpg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtvtwjuqdd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtvimpvqle.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtyastjibo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtfjadyezr.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtropjkxxx.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtdcvofrsk.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gtqffwuhmn.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtwhboteej.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtbacxvirz.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtylqbgmgh.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnxjypmox.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtpuhhqpmf.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gttxrffrjm.html


<!-- 参考信息 -->