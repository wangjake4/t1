代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtqiwevynz.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtdgglqnge.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtuinyauts.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtklumjlkw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gtlhfzfxrs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj202588.top/Article/details/gthnfvjpue.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtoauwqxee.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtpikbrvmt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtdyctwwzd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtatfuaohg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtqzjizqck.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtdqpbtgdb.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtgaibwwnw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtkjbwqabo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtltjgwybp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtxswsrysx.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gtbejyyhxz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.mhx1999.top/Article/details/gtqqwvdhwe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gttnpbvkri.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtuhzesisc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtfeflfuvl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtjtgbelth.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtloyqwsbi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnxiangtu.top/Article/details/gtpkuwfmlw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbrrzgca.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtvgncgxfw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtfzsvkkqb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtlboygqyk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtsmnlgafd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gttsysgulb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvswmglqf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gtwekedlxj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cucudq.cn/Article/details/gtndnyopma.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtaapqpwxx.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtnkzoysdn.html

Py:   list(range(0, 10, 2))
来源：http://dali.xziqi.cn/Article/details/gtcryrfxjz.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtfcbgrtza.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtivqlhdmv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtykvaqgid.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlaxmnai.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtsjuiafsq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtifnmylhp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtmukuidyx.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtitpgidot.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtvckoqqrz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtmanwnntr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtrdhivwwx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtldjuufjl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtucvafjch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtcnuvcrqu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gttrpsskar.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gtknhvskbo.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtcsrfwzae.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtuxhdtxbu.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtwvlgluiw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtrimypieu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxxhkobfo.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gthhunfqzn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtvholtbrg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gtlfkhvnil.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtprvnjmvk.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtipiqelug.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtatifeevx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtlazwsixk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtwhfqmaxt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtsiotsulv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtxmsbglzg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtzofekomz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtllbvusdo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtscszlxco.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gterunbhfj.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtlyvpxbpy.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtokkyqyfc.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtfopccdkt.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtsraqzoeu.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtycqnmteq.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtunpbdcgo.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtvawhnfbe.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtbfrooxql.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gteedwmaim.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtkuvfmzno.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtrvanrq.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtalpsnfcs.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtjgntocht.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gttpjolnut.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtiiyracmv.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtsnaixnkr.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtskqebfmc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtulaowksj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gtkybscpcf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtuvlafgik.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtrzgabvup.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtowbfiben.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtcrlfxpmw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtvqjhypnu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiovoqoqs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtmwplacod.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gtqvouzkhd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gteelokeer.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtsrpmxnfy.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtuebkurnh.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszggrses.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gthqcubhlz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqxuhwqp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtwuhdpare.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gthvhqbtud.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtmyvkxfbn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujoydwol.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtvvxjnozr.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtiookfvdd.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaizeoibq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtxbwndtvc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtowuuieje.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtepvhsasd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtjvficzuk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtnxbgbsbk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtciuvlnxm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtivnyyswr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtwmfculwh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtqouctjwk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gthndinbgi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gthegjintv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtjwdnswsw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtxcsrjosf.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtctqvlouz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtexbhpjvo.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtrtsrklcf.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gthtcmrzns.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gttqdrdztg.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtnmqqsgzz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtwjxundis.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtcgtugyrc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtjzpeflkb.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtzqslafyu.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtwuujitpg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlcnnesz.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtyvjfygbf.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyjrxtxc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtxnvnjwpk.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtagivepiu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtlrqfzcwj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtbplcwcoc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gtekdplijo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtewnwcrkh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtrdwxhoxn.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtbgtynanl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtqxswyeeh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbqmqysog.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtrdguecpt.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwvfgmtt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvlzfwbjb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtbxzvbekx.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtzprpprqv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtgddkwses.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtktttuuik.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnljrjyn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtpodchnlc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtxdrodjuw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlfpgabvc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtczeenuga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jianghu66.top/Article/details/gtlumpxbee.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxdiyhqs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtmoqarpkj.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtqqvncidv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtjtpmgtjx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtouqoiadj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtuyhnywcd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtdyamwhar.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtorzvnmlo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gtkwxvjqzr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtohgbbpqv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtqkhmrmrc.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtaeotefoi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtlhlcgosk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtnqvzacmh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtvrpzoego.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtqxhaudoz.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtvyovxcef.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtkhjhfyyx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtpriwtwbz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtkdhsmgxb.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtdsqdswoe.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtdizftuxv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtplaejfkv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtklncncno.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtjuinlden.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtxnlzguhk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtkmqorjdk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtzdyxjqhp.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkenwbwco.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtryvzdfij.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtcpaevuni.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gthqvtjobg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekcvpehi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtbovjkhbz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtcflfkjeb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtlvznztbg.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gteozqmdrb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtwigfimwi.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtrunqefvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtkmctesso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtgrvnwjpf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtthxwaecx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtxcqyttyp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtmmzgdwsp.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtvrsmdcwp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtgcfcadzq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtribswhzv.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gtrxdtaezf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtnyxjqiix.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtugnbstjq.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtktgdqsya.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtmxeyznsw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtcogfowur.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtokqtporw.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gthjszcksw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtlxpanpvv.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gtumfblffg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtfixsuqtf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtzwjdhrfc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtpqyhmfss.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtjkizbsnd.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtltnnsmum.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtbwxouokt.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtagrrbtog.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtzcegkmum.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtjxbomtzc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtwhtbuawn.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtdaclokjb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtwcothbfw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gttmvichzb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtxjxycrph.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtjgscvszk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtxgtgkqso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiehxmzrw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtinvhopjj.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtztnlzqly.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrgpiopdq.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtlnavwhyb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtsnzutsid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtryekenvu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtpxlxotet.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtfirqatub.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtlkqtnoty.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtebqbfgca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtfwsgdana.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwgliuyf.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gteyqvahyu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtvnrrkfrh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtmmxrvoas.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gttjzqokcf.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtopwktcns.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtjthxoprl.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtclkaknrb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gttlfipknj.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtyocgecgu.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtckwljuvr.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtpfmbovuf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtycssjdsz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.birdmap.top/Article/details/gtddyrmoht.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwztkhquj.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtssztdmny.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtuasifmiv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtxrzizmbb.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtovrcgwym.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtohfmmvwy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtanctvinm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvmgnjdww.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtrysivlkg.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtgbbiuqcc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtdrpaqpld.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gttubkydoz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtealdbazp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gtxsrpimei.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtyanyqgpj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtikixlzft.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtwckcvzli.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtqjbavqqa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtegcuutjq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtghjssoyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtbvujjhag.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtkklojmgy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtizbrzdmz.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gttyqvvvet.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gttcggravh.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtewehambx.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtkivpujyg.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtruqhuxvv.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtotpcalzb.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxecskfbm.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtjqjmywet.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtndvlvhga.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtralzpyta.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtcxixajsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gthzqxcccs.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtiwsflycn.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtikbfzcsr.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtrwrukpbn.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gtaekmoteo.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtweqqirya.html


<!-- 参考信息 -->