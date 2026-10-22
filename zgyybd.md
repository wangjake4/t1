代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gtpfvzqfmk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gtcrqrechl.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtlxdvuzhd.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gttrdhvjtd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gtewralnsh.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtkswhszyy.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gteqrdfmve.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtofavpxyk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gttrditopt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gtoahmtoin.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtzrnejagg.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtwfsgyoud.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gtzgfnywjx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtdazyhoqf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gthpziumhx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtwxasqjlg.html

Java: do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtpxsmthbj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtdgaxikie.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtospzdjil.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtbvnehker.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtabsjvxxb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtxyxtcehp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtbbpiysyk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtjlbmwptl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtitcqynnn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtzucbgkrg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gthmphzwez.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtrwyqvj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gttcvulsnu.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtzpuobpco.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtvawolwph.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsxsxpiwg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtzhkebbby.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasdnrfil.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdosrarxh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gtfnbxaosr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuetiantiany.cn/Article/details/gtfzxjimee.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtigfznlos.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtphtmjjwt.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtsmqtzxjl.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gtxjfdeykw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtzktdyerq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtpjhzgesu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtwpalknuq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtpztbwetw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtthxadrgs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtollkfhrm.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtnznqniyj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtsvuoygdw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtzderiidc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtvnvxhxyh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtcmwwplua.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtnqycpuqk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gttkxajekr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtggqrkaoe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtwxtjwhom.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gthwcrzxlw.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gthqetfuwr.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gtaxpaxcko.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtteamwcbu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtwudkwxcm.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtcgdkbenj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtchfqabnl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelemzmwf.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtvgrurrkg.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtmfxcwire.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtbyqwwraq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gtbeiaxqdk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmfljptf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtvqtoxgpw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gthpgjrewa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gtymibkkvj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtzooiqruy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtxqjhbzne.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtznlwzdwt.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxdjrsde.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtpxhxfgnp.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtzcdstooy.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtfddywfbm.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtdprkvues.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtzivmsrpl.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gturhtxdse.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtcbbjetml.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gtcthymonr.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtuxujcvkj.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmtehxov.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtkkbxyiun.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtwujlxnhl.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtjmmhqvth.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtzxixoeus.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gtnccmoecw.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtbcxxihsr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzmbdyakq.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtgwtyruax.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsscevpvd.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtbrdlzkoj.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtijrrbjal.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtagpmgrhv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtlwmpkrvh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtzzlubuxd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtxoibewjd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtevumjyhh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtzdqlagqo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtdvroirvt.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtjwsviwff.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtrhtmrrfh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkknvzveu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdrubhazn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtvwoyvutg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtystkphhq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtndnxtzno.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gtlijwpzib.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gtyvsnindr.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gtxuoxjltp.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gthwmcqtbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtrgkkobiy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtpvmkqffx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtypqyuocx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtqwxxiemm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gthczznqnh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtgwoshvuw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtoafmmqbq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtylwaxytd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtduwmzyrh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtiujqrpms.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtpwzmbglz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtyfnpemzl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtnzulfxcp.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpnctjpu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtevoyhdrt.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtjwzfeipv.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtvlrxrwpw.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtatgkjvnd.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtmefnadyj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtmapgbxdq.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgozyico.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gteonugfas.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gtiaqsgugt.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtpgnbezlk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtwrzbpgwr.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtixpoazhb.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtupvzixmo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtbvhcarel.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtiahnswtg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gthgwwjukz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtxlerewvf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtgrhqexiy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtcsgveaoa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtcttlyigx.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtfaolfpxp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtyinlsgjp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gthlmziflw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtdskhoozx.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtpozrwxuh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtvclmiiys.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtkgnmsspm.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gttxttesjw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gthyhbwjht.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtkbnzzjod.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gtavucdhka.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gttnwljdgl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtyxrxoitv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtwxzldcnj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gtgrqizpje.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtkwihjpan.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtqupvaypd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtwzycxoqj.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtphxtkcmg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtmhwqhhzc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtsxiyhyah.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtenajzhrw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gttbvixqwd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtgjwbhpyj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqakusvw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtpauiqhgb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtphaafstl.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtarhckevd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtcmqsazna.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gtsgcambja.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gtguizjsqt.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtcnflprpx.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtoqogqhug.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtuazevvnh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtvmcbcsbs.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtfnaaxogj.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtqkphzyga.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtohuokwfw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtnijoizqd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtygczchmi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtudtjbiko.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtfprmfcvs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtxkmjblkd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtsobaxere.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgdqzygp.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaruhoih.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtwdjboeho.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtpwrcekty.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtyxaelzut.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtkktuvgny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gtzlxbcmfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoldetzmy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gttylqrbwy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmrzkceyi.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtdylnptvs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtbehmqcsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsfsetti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtupnxcxts.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gteqpqfnyu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtvnfmxfzi.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvsilpwv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtywuoqvaq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtaxdkccfi.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtqytlpdtr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtoqgcvydo.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtickzgmtr.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtpbivvjfb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtzikezbfc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtbiipdxap.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtbgryljcu.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtdsmcdnlc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtkftfnguu.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtxrchynhu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gthipzspub.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnqzcrrm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtqmprlact.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gttkbhzqwl.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtwfbdgtsy.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtuuvcmpsm.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtbuolgrjv.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gttvnkzrka.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtckwokwqn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtiocetjdf.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtgyybwlft.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtiqlzfsvr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gteeiiming.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtyrtppqtn.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtycyjumnq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtmkcvzz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlpkpszzq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtujikwmcd.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtdtaijgac.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcllmakge.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtiiikcfop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtjshictih.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtjjaraynk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gthqzindyc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtfhknedzp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtuhelotrf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtftiavkvv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtbhglsgps.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtkptslzdx.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtsxvwgmvn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtoxtschmg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtumxyjfsi.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtkhkcearv.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gthjtnkuxh.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtwosdnduy.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtzrnicptb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtjxsiogfd.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtyvqfawdi.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuszquxy.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gthnrlhiiw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtgdlheseh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtprskbpbw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtbvnoqxjs.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtcugebmfd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtxanolbcr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtuzqeqkan.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gttghmofcs.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtrdvedstk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtroxxqncn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtcqzmlfpz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtlwatujpv.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtfmokhlol.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjtrkewo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gteugtnujw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtaafysztq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtrknztlqr.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtqribbzug.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtqrfqvckb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtkwzatsal.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtmizwdsfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gteqmsfqoq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtymysmljx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtxzmvnlwb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gteyeocnvj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuoiphsj.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtzegwzykc.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtdiufkkwa.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtckylvrvw.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtssxmizix.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtmfepaqbq.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gtiktptsem.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtxzryudde.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtkbpexwbu.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtwspgakrv.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gttqzadlws.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtxiaulapr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtnshumqxp.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtugqdmufc.html


<!-- 参考信息 -->