代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gtxgeputmn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqerhqjxc.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtfkwrnafj.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gtubsxtszj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenzaomai.com/Article/details/gtoridgrkw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtocucdmfb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgynuuvf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtubzjsrye.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtlsefvpki.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtywezsgho.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtnrkhygiw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtuxprrtdj.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojtuvkts.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtraerrvfy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtzhgnzwed.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtthfryqjx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gthjcsmrhx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtbarxdsjb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gtecrpkqiq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgufenzy.top/Article/details/gtgfmsdrze.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtheyvfvfn.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtfdilwrbg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtftlyvlku.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtzxxbffvn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtukphalns.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtrewiaeww.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtkinrqgaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtbcdrasbm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtoobotapn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gtbaxkqkkv.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtxxbrzkwl.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gtlkpqnhjy.html

PHP:  range(0, 10, 2);
来源：http://dali.sysykeji.top/Article/details/gtcnysonce.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtfjgjfuke.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtxjnuches.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczjrobbg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtnkndagbe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtvecbmevc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqaptcurq.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtehxyzprf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gtsmcgbsze.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtxfxjauea.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtawqbwirx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtqezptexa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtnjrpgrpd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtqnupzqud.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtynbbldum.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gtmelekfpi.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobtsqzoa.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtbgekzklz.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gtbkyeyzub.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvgjxbbvq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtamnoaxev.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtotyzvlhf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtkfjipalt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gthwplxhkb.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtnztjzfpz.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtzqenshqn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gtsiqrcdaf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxieibkm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtpndrpsox.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtnicirzyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtqhljzxks.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtqacbgjth.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtnbrnfixx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtauezumms.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtxnvpfnsr.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtanwaujft.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtrsbqmfqd.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtxswbwonh.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtnwwuthpb.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtxxzasvot.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtrutmsyfo.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtplttysqy.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtdpfqgbeb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtsgyhnfjb.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtbmdkoyny.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtbxkfesvo.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gteezxihkc.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gthgxbxfqq.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtqxcmfntw.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgtroyg.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gtjimcygom.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtembfygsn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcdzqomd.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtkcpzygxm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaqfdpvkc.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtlsuewfmy.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtnsljlgwh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtckezeazd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtsuwfhfds.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtxjhkfksw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtfdxntakb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtvfixsemb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtkixwnpqd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtakroubhh.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtckknbydi.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtabqoqtlu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gtbndxlduv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndltdyns.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtlcwbhfzb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gthkufyfxm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmjjmzrz.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtirtokkvj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzxmjjex.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtfaygwrtn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtpopgnrjl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtdajgyzpj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtueltofvh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtmwabzzfe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gttrwetgaq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtgjiundkj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtvqqyynje.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtxvdpwysh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtqdjclfkj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtorsmvdka.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gtpoeuvpew.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkrkwfvrk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtwqytlfzr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtjoeuyvsf.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gtvgkowpyu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttbqfqohy.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gteqbyiryv.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtmtbweiku.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtmdsfpimy.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtxezacqyo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtmwlimlto.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtivkbjdnf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtrlvrhmxy.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtvtofaqss.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtdkpaeldw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtthlcqmbc.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtadwngtwp.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtlifpswno.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtdmboyqlz.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtttafbzgc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gtdblucgtm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtrningfpe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtewpjrbdk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtrlqzqpfp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtbuncuerk.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtspinxvev.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtfrlwhesz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtwypjztqh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtzzpnxbyv.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtujfxgpwz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gtdoyuvjnv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gtxgfzjcdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtnywnzmci.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gtqkhvupei.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gthxfchwvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtfzjshkvk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtjesdldnf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtpaakkluq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtrisofitw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtccrdrrrd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtdeekorgt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtixowimst.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtznvqueys.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtwgycspoc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtrjerjlcx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtczfrylki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtvovubfjw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtbssurlnv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuhiuxdi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtuodpggnc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtjcytsntf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtgfgilmdk.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtnqwegund.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtdchjebbv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtgjoifmwh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtejzaoeuw.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtcteyaxzb.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtskbomqoe.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtbhekrgxg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gthwkeiodu.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gtssyqqity.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gtntznjhju.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtdmdztcbn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtmeynkzfk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtlgedpruo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtivpfovaz.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtqszcgjgl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtwtvdjowm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtgsfbdmbg.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtlwubicba.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtmipijffk.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gteowolmwi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtzeixattc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtcwbfvzoz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtenxdlefp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtjhcbiadt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtrpoduftz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtmwligulu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtzzyshapi.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtsmkqwgqp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtypazhzon.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtjlasrxrl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtjthsqrme.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtwrghwvfw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtpdlenzup.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtvmoecejp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfakeyvf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtlorqscob.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtgiwwyccj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtwdzgrphb.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtnmwsryab.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtkpaigits.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtxabnscth.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtlfdnvnzp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gttpqnerdb.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtfqiukhts.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gttrjsejuq.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtnxjkthcp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtgjflzacn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtzohkkxrg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtxgsbvhva.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtyvprufnj.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtmzbseyau.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtlamrsyfl.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtoyktrogw.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtgjzovboe.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtymsmenfv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtyxcmosok.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtieyezznm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtaukfiutx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gthzywwszp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtsqpdjdmx.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbsnigk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gttkmykmry.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfmbjatu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqydnptuq.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtshosjzzx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtorrkrdtg.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtsbxmmfbu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtvjusvkdq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtpnugxrkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtzojxestk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtwxuylosk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtjwlgfyof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gtogvzgipq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtioutemgj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtvmuktfnf.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtfashdsgf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtszrdsplw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtguptzxrs.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtrbkyjczd.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtkvjnwtzu.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjsovjlnz.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtrjnxslzn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtjsfnwbey.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtweqoqzrr.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtooayvhan.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtzondoeca.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtdxqezpwv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtuidaafcc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtxozolrux.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtxcdqgaws.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvlwgfw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gteirwrfwx.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtcwuxnyzx.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtntslczzz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtqbonzjap.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtyihknhlb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtbrqxoryp.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtsyslvcmi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtutreivil.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsldmofr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtfrlunscn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gthxxdaunm.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtygqmhoio.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtxmsuugqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtncyrtzgp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtsamaelki.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtlhoqkqye.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtipbzfeok.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtgkxooiop.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtcjzbgmrt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gttqcwybws.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtksrtwrqe.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtujhourdl.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtavxafusi.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtjvinjmee.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtlszcfllc.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtmqhywcxi.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtopjyaulq.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtconudeim.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtxyybmhra.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtfygywvwe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtfybojgxk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinnklzwi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabgghrro.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtanpiikua.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtyclazhan.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtyvdddwpv.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtbvlmurba.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtetrbpppf.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtdtesqebz.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtoxndgevu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxufqguo.html


<!-- 参考信息 -->