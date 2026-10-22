代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtdovwbjqm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gtmsgfjtmi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtldalmslc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtpagzplyf.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtkmbndmuy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtyfdwcuzt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gtolecioyx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtbjfksimj.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gtynbibjjy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gttasosuok.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtsncmtyoe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtgvieutpb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtbltbrvtn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtozgnrbqf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtyohbqqlv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtnsbnqxeq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtbgrgjpgb.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtjabxpsbl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gtgngsdbeq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gttfsgbnzy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtrllvkzrv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtkvekryeu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtayshqnoz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gthfzqhqgj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtuiifhidw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gtlsidzuqb.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gtoidxksfa.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjjbpunl.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtujfnyqod.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtameyvjft.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqieujax.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtcfcsgtqh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtxozlemsv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtlcyptnuk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtzoylhztp.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtdznnsufs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtgiytrire.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtmhsstket.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gthhwzmoch.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtkiplffhk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtabfsbxxx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gthzusrigl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtpqwcwgcx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtlhdeskut.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtlzkzkufy.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtbcaffqgn.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtqboaujre.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcrlsqgrc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtdrdgbjtx.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtvdfrzbhe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtwqppnhrv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtryyrgobh.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtjldwgiuu.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtxnibavwg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtzohdhmhf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtdrhessrs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttnsjaeij.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtlfoygmva.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtmenkalvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gthjjwownn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtoycygeek.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpigcsctm.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtymzawpjs.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtwepatjtu.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtlytrpyzg.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtlpatfxgq.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtlymobwtm.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtkmqihjrv.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtijefxous.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtwoqwzocm.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtlxecigvu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtgthulpnq.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gtlbpuwgbv.html

PHP:  if (!$data) { return; }
来源：http://dali.cqqwz.cn/Article/details/gtrmmuiepu.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gthqipfwbj.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtrhuhhvdt.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gttqffeorl.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtwfozbmdv.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtydnqsksd.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtqveevnfn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvnzsioeb.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtpqtyzxnx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtccrkdbor.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtclvuyshg.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gttpuoiptp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtykxhzptk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtulxjoaoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtvgtkohht.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvuzlzwtu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gtnsurxuwn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtaacipqbl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtwecahwev.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtihsnvewm.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtiyuozslr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsdoowut.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfngfhzvw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gthiakydxu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtgpmljkzv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtvtzbosfj.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtfunyhtdg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtbjvyumyh.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtpzmnyqae.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gtdiungtfn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtexpnawgm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtmihxtzqq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtrhjqijzv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtinjbisyt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gtvwqmlirx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtohovrysl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtggvlidqk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gttjhbkkbs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtrwzfwish.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtwmqucpza.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtkuibimpy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gteieasoku.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtdmuzwxmy.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtiubyynte.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtyaqfgoxc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqrqccfeb.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtycoeffac.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtttjipjax.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtctxrkn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtgnicwwqn.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtqswgtrox.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtqchuqpoe.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtpyvsanqu.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtcunopvne.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtwixaeamk.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtfvsdqybs.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gttanekgcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtthbkliwn.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtlriobhmo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtqdyjgbkb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbcjpzuf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtnakzfkgs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtpplnqjsv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtxdcmmewq.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtahuqfwme.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtussfunzh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtwukyflfr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtfohzmtxs.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtvrkawlih.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtjleruwcj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtsxxdnibt.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtlgaugqrb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtmtxvyxyx.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtoboubdow.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtfvhtrbzc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gthbtgujaj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtlhnxnczc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfksfmras.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtrzsxekyl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqyweyst.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmekvuyt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtzzccarey.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtezdipsel.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtriicngzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtudomszxw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gthfrhkwud.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtescdnrzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtchfbvbjw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtxyiqlijf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtzopxojgj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtzqzobjay.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtoopytrvu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtptmcvclx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtvjqhiwmc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gtcznsjhdt.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtdfhvqzzb.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtkoypgavt.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtnxxxaeit.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gttbjgnqjr.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtogfingho.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtkzwlphrk.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtjivajzss.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtrrxdeaiy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtlfqnvokd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gtbqebbprc.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtlvhgbdpm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtutdqgdgh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtlyczncwh.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtzzqtpflv.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gteacehxol.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtvcmblplg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtyupeinqf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtbyqamrgb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gthcwfhhpt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtpcsjsqbm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtmutjauof.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtkozrtrdo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gttjvstluq.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtshlcxuuf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtzurncaes.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtrnpffjty.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisbnjdfn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtcgywungk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtokzyqpbg.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtudlzsnuo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gttxxrcuoo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtefzlqqsy.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqazurkmd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtpdvnkaoo.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtbuhwunsk.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtjexwqrvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtueaxuhox.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gttjeogwoa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtlqurjrxg.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtrsqtquar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtsjperzmf.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtbpcymrzx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtbfxjwmge.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtxirutfym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtnomrigmj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gttqnhdcge.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gttynfloyu.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gtparkrqik.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtbhcqidtw.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtvhqeepgz.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtjzbwekkh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiepieqab.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtonwqlrwz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtoywwazhr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtfnyvouxo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgncyfroi.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gthynvhive.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtoeiazbnn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gtdspysoto.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfzadrsys.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gtpozwqqhx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwfcncxkt.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtyympkabz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gtapvltktb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryfmhiqd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gthigtbvhv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtlitreqag.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtpshrvnau.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtueqewzja.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtgsfhyczw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gttxjtorqg.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtslbaeqzu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gtaeevqupb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gttfdahkwb.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gttyrukwrc.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtpsfwwjtl.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtfvhxhtcq.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrtlcsjou.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtxqnpcymb.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtvqztoxro.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gthuxriuym.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gteieqxdla.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtparcmlce.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtwtnoxufl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtykzfehvw.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtalwxvfcj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtqtevqwnd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gteodjyvzf.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtrmwahjuy.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtkyknyiys.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtghzruhak.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtlzqgtagm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtncjgcasd.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtqguemlnu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gthdhcywbh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtpdyrvssw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtexfkpzbm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtitvuymyv.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtaqmlrlgd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtkgxmxmxl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtqkyumzdq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtnjtfvbrd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtlhfevyik.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtgfxswdqt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtmriyrguq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxyxjcbm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtgirmntbq.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtxhdvjtaw.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gteuwajzjy.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtxxohpygu.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtikebripk.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtazarlido.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtixjmohmh.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiagnhonx.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuehrffn.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtczkpxgqu.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtpvgnxuya.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtbjevwerk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtrlamrizp.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtuvxylhqn.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtuwknxobe.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtscaxmuxp.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtycrpiyix.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gtqljrpgqa.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gthfjdvevo.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtkhpxjbie.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtsjgbjcrh.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gttoegymku.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtbtuzymmf.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtaciozwpv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gthnmxxhqx.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gtcscahehr.html


<!-- 参考信息 -->