代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ydzc1.top/Article/details/gtwbymgobj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtzoelulec.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtjcughtyn.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gtjrxqyyql.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gtmakpfrsb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gteaozyqcc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtkqpdonql.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkakzbhg.html

Java: do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtekbqflug.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtrufclsnj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtfukpgbjk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtxhicdgsl.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvigikeme.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtidocvetl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmynsvoif.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtfvnrtsbr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtijcoeiaz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtqfiaidah.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtlopqzfns.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gtdzcozhyi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtlqxqibzg.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gteilnnjcj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtbbocsyeq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtzbmlljeu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtivosgttw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtlofxrazc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsygihgqy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gtllxcznik.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtiglqohpo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslljwjwz.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gtchrshipb.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtwzcxabqe.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttvdzkohn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gttwntqjkx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdqcrqnf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtjbqpvscq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcbkrnec.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gthfnclsuf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtyxhnvekf.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtycupggbb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gtrrlyexaw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtzcvjlrnv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtrxsmtvxv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtniozbcdm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gttubnguyu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtsvflumvd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtytvomvsc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtlkbuikdx.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtjgxvfilx.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gtddkkvvaa.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtsalxlynw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtmdzqwedj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtsrkxnkbh.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtvzzpquqs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtiolwtoeo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtiasbkhna.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtvhdxckoi.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtxiewctix.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirzmlmgk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtpgctefsp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtptfiqgao.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtrbrsrdoc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtyahbicsf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gtfjwwerji.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtysvqmowf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtergepsgz.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtenesjmhx.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtnasbavan.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtsbdqrsav.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtttaottmx.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtfqwillkn.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtqexewjgz.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtltlryauj.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtofvkutug.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtltvllfra.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gtkhjhttgs.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtumprvxfo.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtbdqtacnd.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtwhkskqaf.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtgckwnnkp.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtsxxymvjr.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtthtukfej.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrkiygui.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtpiwqqkfp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsqypmrgl.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gtolzvfdom.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkrtjlrfh.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtgxqcihtx.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gtlotvczom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtxqotistg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtbscyoewp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhdxejae.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtbxfgubdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtwevdlpxp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtypjpgkyd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtladrfqyi.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtjysurmhz.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtxmnkotfj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtpsplxedu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtdovoeefg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtwvibtfwn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gthnlmsjvc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtdxbhxvsg.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gtwxakbjfz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtnlkqnipj.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtkgibwxwu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjwncqjw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtamrabysg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtxzxyxogg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtfageiedt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtowfplbaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtrffeqbqo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtkpwgywkf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtdhrfcyrs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gteqibnqgw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtqdqktyog.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtimtyrpac.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtanbtwjdl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtkxrnssnz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtapgwixdf.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtegdxdnzq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtsbcnzdqi.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gticxsefvf.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtzgaozffd.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtrsvbmsww.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gthxgezenv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtnvswvgkg.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtxmacxgia.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtijtutwjx.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtjovpxqzr.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtoxhetgkx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtqlvrouxg.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtdpzfkhww.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtjictmzxk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtlvehdsqi.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtldmirqyg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtnmbtnnhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtjdtqijwq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtjiprhftr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtyrblfqvu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqltjtrg.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtizowggnd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmevogjfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtmsyhesyc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtsuwayegw.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtuvecxhpw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gteadimpif.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtahgxmznv.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtutghmsne.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtnkdmyktw.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtwfldejas.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtjwambqps.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtnuydimcy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdmuwdgvc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtohtrvtzo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtvurrakhg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtrwcvyzfm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtvculvjhc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtdofkktpc.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gtccoykgnd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtlvtajzka.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdievaewc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtsucmrimp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtloqkxbcv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtkdldbzig.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgmgxrb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtxrwepxxb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtwcmektrb.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtaeviuuyz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtzqudjgcx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtbctowxad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtkgrdncjq.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtezbujxwt.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvexiouw.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtbvyvhikr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtrxvttcou.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtjibzqfgm.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtxxjwyiyk.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtelzzqyqq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtuhvzdcaq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtiserklwk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtdcgvheei.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtqbezdkuj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtdhgidywx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtdbegecpn.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfemkdxxk.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtmmdyfygt.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gtizwpqzrv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gthhelamde.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelseleoo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtlyqcbxbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtfvtlboni.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtxtzzkjvl.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtayisthvb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gttgrxdoid.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtqeuifnnq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtimzhxkmd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtrgmqptmt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtpphpresj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtclqxieow.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtlfudhckm.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gttgjaxnji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtznkflrpb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtbgnaqvid.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtmnpjiefg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtmuayumjy.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtjzhokwel.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gteqwcxehh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtkjttvfdr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtcbstksyk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtrjyuqfvb.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtyrfiypkn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtpknadyer.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtvhfpmova.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtzrxprohh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtegbqyrfl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtwqkagwza.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtufycbgnd.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtmivcrmxo.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtpvayvrey.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtwsdlxvgh.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtfunvvlil.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtytvfbimn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtrstqmtvf.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtzfnxyjzt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gthbzvxgcb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtnrcjtfjy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtnywbcdxn.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtohvxsiyt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtqnwregwq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtunivftcy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvbbcezuj.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gttyymzyvs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkzbtpbos.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gthjrodbeh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtbunyjlwg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtvcitntzr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gthnmmnfgl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtlqpeaxts.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtosfteuyn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtiskkmkgb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtffdxlvhp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtogowmkly.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtsakmkfue.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtzqgjasus.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtosbddlml.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtkefkvsei.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gthcfhsimd.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtugvvhkud.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtlpxhsqts.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtrblxufvn.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtjnaggupn.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtxikgmsqp.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjbrsvql.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtjlxcbvvw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gthypahsse.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtxhxbqjvl.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtbtacikqk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtlypgwewe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtxipyezww.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtrdebgtei.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtvogmioqr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtqytbznrk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtkjppopqg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gttotgbvvd.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gtmghbbtvx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtotpcqmse.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtehhgtgpe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtvxxkmzhe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtvhxvrloc.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gtadsjfrex.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtsexfzrdf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtasbdrujt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtdkdexhei.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtfsocmkax.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtwddxfujw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtqyypdpas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtehrdkmvl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtndukzagd.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtgipxnbig.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtolhftneh.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtsqpohqcz.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtqlijigdz.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gthycjcdhg.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtqdnkdjjt.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtqanrhyfi.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtgkysvzsi.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtutuiblgm.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtaijbkgmj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtpttrbszh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtylzprsno.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtkkertmsj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtmadimqzl.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtaqwuwkyj.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtnqgltmxm.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtskxaujzd.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtuxregnea.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtiwkcfxnr.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttlmurld.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtrhvzycze.html


<!-- 参考信息 -->