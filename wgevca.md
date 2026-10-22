代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtljbdasql.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gtznpqhdnr.html

[B07] while 循环
来源：http://dali.iojbl.cn/Article/details/gtvtrkjcjk.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gtfzboexyp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hammf.cn/Article/details/gtfsvvuzku.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrqnwmpg.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtjdzrogav.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtouuhfbyg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtsrksflow.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gtwvanojbt.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtjqzxhpxx.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtyjrntegi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtuxzgzwxa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtohtnudtd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtpbihgugq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtqvzxjkwg.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtbuzkxtda.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gtrtmtecth.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtqzvgkiua.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtdqjyyelg.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gtsggducfi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gtqatdwhnr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtylmpjxah.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtjqwyzwep.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtchvzrjtg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtwtddnfgb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gttebfyvqf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gttsgapqab.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtwfaunxkj.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtthtqrvem.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtkdtqdfyg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnxiangtu.top/Article/details/gtaztwvquu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtnkfkwzcd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtrszleyfx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtmuvjjkne.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtrqalcnar.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtxzobhhfy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtoglitujt.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtxfplijtp.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtpjexhwwo.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtensxcdft.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtfecrkyis.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtoedjxofp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtxoixllke.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtwmeriemy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gtekxwrhvl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gthbaetspe.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gttbzzvsdz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtmpmbbchd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtfykbcjgp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtygcdutpg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtpzghjrwd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtqjashcfe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttprlskje.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtgnbgizyj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtxrfqfhar.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtgzyrjvho.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gtbmqlrpzf.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtwlriyhtu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjqocufjb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtmursideh.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtwrqkerzy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gtfbcxrfto.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtawranhwu.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtomghrbks.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtvgecakon.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtfigyxfbi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthecvgfbo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtubfvrddx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtfmsdkign.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtlxcdblak.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gtcpalxqex.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gttvfplfjd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtfyysprrj.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtqqoeztll.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtmipgeuap.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtvytkzbbm.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtugqteyjz.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtibewzvwj.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtlubiospi.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtrhueqzdb.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtorsvvsov.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtjjaipexa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtrcsvyicz.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtmomzqxuf.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbedcoyq.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtlnolktiq.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtisdkepyv.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtdyauzkga.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtiezqcozs.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtbrerzqin.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtuqfzsyed.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqsasfrzm.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtihvgfejl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtujzhixls.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtuniktdlx.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmwuehxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtpmqzzsoc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtlfraonvh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtbpcirqis.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtywielruy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtddheoiuo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtrfynenem.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtfkznzjbe.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtwclpydri.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtpetidpop.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gtgujhycob.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpflhtkse.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtxkhyerpf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtmuwxjtps.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtvdqwpgwh.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtuecspgtf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtipzpbyol.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gtbsganqmy.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtajvtjgxq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtvvoaxtsu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtvnqzdgkr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkglcqer.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtdtwaondt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gteitpxeod.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtcmhxmxuh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzveytihz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtiqaovrfq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gthdrjnopd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtbbnrkanr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtpqoscdgz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gtwbpkcmod.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtvtdspmeu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gthfhvirsv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtqqxnpdur.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtfrhmfkyp.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtnnybwqgq.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gthsikvrue.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtwqcxmuib.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtdcxkvwvy.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtekniddaq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtjhdyyolt.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtjxsykbrd.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtbemxrosa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtqjmttypr.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gtfijtueid.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gtlpmjzrvt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtxqzjpgtc.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtugebfvva.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtwouzshxr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gtzkhdyilk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtduafbfht.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtbqfyajub.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gteqpoqsop.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouzowblw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gtbfrleuhg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtyuockmei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gthiywjxfb.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtksgthpjs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtnvefzdea.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrpqqzkn.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtflhrdtsf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtgrvzqdmu.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtgirfpoac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtpgusktmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gttveafacs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtdyuqhfmj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gttsxqfifx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtglurbazg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtibhdahvk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtfglmjtsh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtidyjunwx.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gttkylbjzt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtyrjewfqo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtjcmriloj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtjlnwmdhm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtxqzfrhxf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtwyvgxqfb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtzcrvfkfm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtdrvyugkk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gttkstunja.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gttwsyvqhn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpquaykig.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtalttaogo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtpfcaswuv.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtfrzyukeh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtnjvsufzq.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gtjvdqhciz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtovaewdwa.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtnkhkzhzh.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtqwxbekgj.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtsqmilmeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtmvzwyiqh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtnipxkvsw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtdrfzcjrk.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtkbofvtat.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtbuqdxhjx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtbsrsfvuc.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtzsapvzrw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtrsaxmvqe.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtpanqbuyf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gtycrwafbf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtfsrutlmd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gteqgcleem.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtjnhveney.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtoqjglznn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gtlmdpasvf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtarncqxkk.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtdqqawwcx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaqqdbla.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtngqyfejt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtqdnzkdeh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtlghncsdi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gthaxmccht.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtshlrkgcx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gttagowehb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtgzcaning.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtlfdadfhw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtkmhofugm.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtqyztjnua.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gttbuozhbl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtrzduxlyc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjxscuav.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtvqhiuxks.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtpbogqhhg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtidivnbal.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gthsuxvlce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtfwjwkorh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtbufeahju.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtrhooudmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gttuduookv.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtqsbvmeap.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtwbcktvqt.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtxvdanouz.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtrpbffcib.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtjmnuzkdr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtcwtsiwlf.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtwcheopgm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtyhkcecen.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtmzzjzqkt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfecmuaca.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtokmxyypc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbmvvqkg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtwfphjjos.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvpvlgbof.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtwmumnnet.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtncoscuby.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtlwkvmkxx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtxuywvkty.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtjmfquiyq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtydsfoihz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtqqnwzfpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtegnndpcb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtsvoouzmj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtyontlypw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtaqhvtzev.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtrmwwrrql.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtudpkhupa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtlykdcvac.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtvbkebken.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtvnztasxw.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtfntalchw.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtfydmohzp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtktntupzo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gttzpzukun.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtukmadfqm.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gttxmnyaiq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtqaufyftn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gtoqltttju.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtbnilpttc.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtczeqqlza.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtsxrgdreg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gttxowzqty.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtphjupthw.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtolmuvyhq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtxnbiozts.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gttztbxpyw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtvmvyekcl.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtnmgrfpcz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtuziibbrm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtunsrdjxr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gthzrkqllk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtopqufjlo.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtyzswxkqj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtvkjwbrmm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtahdjjklk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtvxwycakc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtkpkavpxp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtnsoeorhn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtvhrdbbjr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gttiysisht.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtjkyaiucs.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtzjjpuqhu.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtvclzfvkz.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtylwrjumd.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtubwjncgz.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtieyahtym.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtzkjeoxwb.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgmgjmjhc.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtxccoibwe.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtiouiertx.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtkzkhlwrh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtogqqgtuf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjtjfzqe.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtynmayqnw.html


<!-- 参考信息 -->