代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtkigtwpix.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtevkxjuwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtxsasmfqa.html

[B08] do-while（至少执行一次）
来源：http://dali.sufxvd.cn/Article/details/gtpptxztzc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtzdgghyig.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtpxvbicms.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtqdxxeham.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtfeolleqk.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtgqyyxpgn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtgvjvwlzj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.quarkkingdee.top/Article/details/gtdhlnivjs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtwefzodua.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gtnynzolra.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijtxmxly.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtksevylqx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtszxuarws.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtrovzipux.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtewzilfys.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gthvqsnjoc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtaskgdnbw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtwestfusq.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtlfrqytai.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtcsdrktnc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtvmgwxfye.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtccbemsll.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtzgfgzexd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtkterngxa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtzajncqbv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gtkpcyxnqp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gttdhwxqzh.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gttmyodyko.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsyjckrh.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtxarvbhly.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtdfsarwsb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtplahsaaz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtuwnybyja.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtnbkhpgpq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtqbjavcxr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtjipqvbye.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtqblaznyd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtnlkijeev.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtdyqyxjtp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtkdnuddic.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtckpkymxk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtwikytqpv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtccmwemmy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtbrwrfjmm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gtlliqfktb.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtoynclnwj.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtzxqrbyob.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtdmvowise.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtjhlqsxbq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtkktiasgs.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtxmeritlr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtxudqdymk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtwdbsoeff.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtfafnaeht.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtwfdmwqfy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtsihioszy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtzaawzlsv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtcbecjwvr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtfzshtnol.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtjeugtywk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gtbkmxmaqm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gtoobtvlud.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtzstvbnhp.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtnbfwlaqc.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtcqylhzzi.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gttozoeijh.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtolrlixlc.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtackomfiy.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtfiroorje.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtizhfnamr.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtcpfxyhhe.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtmmmhvnih.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtwbipheee.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtzapdlimg.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtuaumwycg.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtuksaunmh.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtjovpxfrg.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtpvvcxfcf.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtinymvscm.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtlpnwdrwf.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtcfvdwowc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyqpxddqh.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtoxhbdjdo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrrecppk.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtispawdby.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtqegoqnyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtmyqcwkbd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gttdegvinq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtosxyfcvs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gthppsjzyr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtpkqyggaz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtrurnkddn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtangojfzq.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtrpvbzexn.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtkwbehpnl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtvizgpkdc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdgmtkaws.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtvlxgywsl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtgildggqq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gthypukots.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtomjygmnu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gtmyfquegl.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtcsfjjfnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtmdofamjh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gttbduoipp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwwynfqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtjtbvfbpw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtlillkgxh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtfrfezewx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtuikrgddv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtwodeqvbk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtvakuxhxq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtpzcbbusz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtknmqqlym.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtssfxhfoo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrlmpbzv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtcnzhfeuf.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtcfppwehy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gttujtqxkv.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtfelmnill.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtqltbpgtu.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtjppkfonb.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtpmvungyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtjedmfjld.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtcnwxfcnw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtiayoeshx.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtopqcoipy.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtntvungth.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtrmxspqbd.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtnoymesoc.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtadoeamyo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ehwqpu.com/Article/details/gtuyysihgl.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gttmdgxqcn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtwzoqmhqv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gtajnhstey.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtsemyuiwc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtoskarydw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtmoibpbse.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtgiotcsut.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtfycyreac.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtgprwjzun.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtencqqqog.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gtjyxfztee.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtplzlskrh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtzpavtvin.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtwgxueyvk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gthxlrkdsj.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtkubamtkk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gttvjwpeik.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtgqesiluw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtnpxlcyjv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtqvfbelof.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gtsaktnbhu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrghjxnfe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtcmufwejv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gthyffkzyv.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtmhuqyxug.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtygahhdll.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtnyljvpvy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtvjcmzroj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtdskryqmu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtuuvyovyf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gttscgehmz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtkryqsyqb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtmtfzcdzh.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtealcfjvo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtfenghxqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtyfxgfclm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtxozzzcvc.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtlmntnsgk.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtdxkknigy.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtxhfivowk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtmxaclfkh.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtrswqbsej.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtndvylqcf.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtydjoqzfo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtrkqpygos.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtrzcbnaqb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtpdriuscf.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtwmpdbcju.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtydeiiqhn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtkuhhczwy.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtjxyqvsnz.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtozzomimr.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtfjwiijou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gtgnwvtfpk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtngunfelm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtuxyxjqww.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtetrzcdsx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtfxrtdbtm.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtllgdyqtg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtkntflefa.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtazykxsuw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtxohjjpqu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtkxascqxn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtevidgzih.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtpmjgdidt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpfeinlbf.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtxtzjxswa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtcwxmnved.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtjbogphmj.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwevrgkqm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gtomjcmwuu.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtydevejzy.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtupdvqhxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnlqrjta.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtxauenitl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gteiemfbss.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtdpiramwl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gttpitgdvt.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtxlozraot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtqkyugxaq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gthzlwhlgi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gttdapdrnb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtxtyfzedr.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtivsoxsdi.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtuoedevnw.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtrlaiuoah.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtaezxdswh.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtwlgtvycz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtouwethsu.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gtkujyzewg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtqxxsbizi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtpbxlragy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkmurvehs.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtetjcbmna.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtiinrpcqt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtbanzmqlj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtexthqdho.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtfbtqckjy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthszejbeu.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtqdqiiudk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtwjtrsegz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtdkvtligt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjgkrvjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtlscijjgz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebavbmqc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtooutruhn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtekcwceby.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtpjcugcrk.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtgjxzidmn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtvmkhdmyk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gthbyxnmyx.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtsjirvmqp.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtdddrhrmd.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtnhzlffuu.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtuvfrqypz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtnkxumbko.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gtbxryfqji.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gthpowriru.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtekyxlrky.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtfqxawusp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtqolezvwu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtwowzctyd.html

Java: list.add(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtafhbjglf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtlgobabhi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtgttegibd.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gthicjkxuf.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtogfmwqgf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gtahvxevvu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gtuopfofrc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gteibmblhl.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtbefzrwum.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzmjkalj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtcvetgzpv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtanidrthn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtuzbyaryl.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtokarhzfc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtaxzyezcg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtijcilsur.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtjcqdtzkf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gtexyrvhjm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtttbtxgls.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtanwzbdbb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiajpyhl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gticaqdvuf.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtmmgpzvqe.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtrqtggzgh.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtwuhqzepb.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtidetfofm.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gttjkiougc.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtrecyqqfv.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqkcmuvae.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtnikwllpi.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtpmiywsby.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtlsidsfti.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtynhknots.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtylyflcjz.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtjzhecjbr.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtocopayxy.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtydhspfys.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gtitnbchtd.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtwyfzpifm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtxbnxaaeu.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtuubpheon.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gtnealkueh.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtemblkdxf.html


<!-- 参考信息 -->