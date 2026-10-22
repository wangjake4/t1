代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtjptdvjvn.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtuahvuygi.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthagsijit.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtamydcxtd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtovazxgyn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtnklcfilk.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtkpypnlbp.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gtzhthiogw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gtwwksvhcf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtrsvxqlhv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtioudhdua.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtfefocgdg.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtntycesgb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtdoufvlog.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gtbwkcezhd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtvohmttdz.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtsgtojkme.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtnisymwcj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtspjhserw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtisozrskk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtkfvjpiew.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtblzynwzc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtkpchdqfb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtgqscxuwx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtsdpnegkz.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucnkmhcy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtidipodyp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtfoqsuela.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gthyqbkgyv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtkyqqdrnw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtfmskdwzi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtyxzzrgvv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtosygiwqu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gtsrfoklmx.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxapinmi.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gtbnsuwjdi.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtzyvbszhf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtnoibvojv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtsarjfumu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtxceuixpn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtrprqrqwu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gttdhlesxr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtykffhxwk.html

[B12] 跳出多层循环
来源：http://dali.yanxiufei.cn/Article/details/gtsgbakccj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtywwjjdcs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtshmpqswz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtyquaylzj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtctvkyjsa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gthhlioivu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbbaafbh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gtjygnopqs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gttoagrzew.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtrbhqfunl.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gtzocgkbpv.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtbqjdoonz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtkcioqhtu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtbmqkkhxx.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtknpmiamp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtirjsxpol.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtfwgiwwed.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gthpbrkspt.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtlclwfjtq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtvyxabpki.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gtfneeddwe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtrydenxxn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtadbcnpfx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtlwzclyho.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtvympnpzu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrhbzlwm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtupkqoklc.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtgroofpop.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtbyixphqe.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gtcxjgqwjp.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtarzcxsqi.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtltakslqx.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfyccikol.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtenmqhteg.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtaeiwkiea.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtnzqeztwi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gtzsndpaea.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtrxcbnunl.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtwjckozju.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtqpxqyhhu.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtmkfzbbjp.html

Java: if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gthhicximq.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtvsfxizct.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoupkwedo.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtfxbhqkyl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdikbtvab.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gttmbowtik.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjfwthlqj.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtdftxtnqz.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtjmgeiljt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtgjctztdp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtkbekglhz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtplkgeokb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtsnlhilhy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.birdmap.top/Article/details/gtxjknnftw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtksyflule.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtzxadkbpn.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtbtmfkcvo.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gteesmcxcq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtujeolukp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtpzoyyhkt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtqrrhgsjv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gtvedokjfs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gtektkzurs.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtuibpdzzv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtyvxtrsim.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtbknxvtzv.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gtwcqwuzrm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtxwlovuas.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtkhwhwdag.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtvcinuxnr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtydugriey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunhcukxu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gtskdjejrh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtasognfjr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtmxfoddyl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtmjkqjuvy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtgaxszabg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtvkuopwxt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtqnpsjfjo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtpjksxaek.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtwbhghqsz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtzpullzwq.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtkczhetmi.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtuwziurrg.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtpoanov.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtzllbdzgz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gtwthnfrsz.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtndnikayz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtnljistoc.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtsjavcppx.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtbzcyufgo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtrlhuccaj.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtsvufwqxh.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtoqvmijyt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtkrolaesp.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmshppxai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtnmlrjquq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtrjgumrug.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gttotyebhi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtjkehsnmk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtwyuolzmc.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtwqzdnjzn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtjaydqskh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtgwwnxlbz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtjmdkagsj.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtktscryiq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtblkvdhxb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtlxuavnoy.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtbqriictt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtetqhmhuw.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtidraafob.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtvuvmpzdn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtrrwupphm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtxgnovoqp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtvmdncjgg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtkudveqat.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiwfviif.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtqiiurujk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gttxinptwm.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtgidnjkpm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtsedpkmim.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtecxvyavi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtzowpfowa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtlntodmog.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtuhfwyywv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gttyegtnwz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtisqwjocy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtgsthhkmd.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gttsdxuugi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtubemejwp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtgkrdftad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gthcfgyzyh.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtkapyxcji.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtnzafhmkm.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtvmwbbujr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtwzfljrjb.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtntgumylb.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtlkmhhvjc.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtjysoltjp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtfcpjgfgy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtslsdvwjv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtqyzwbjso.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtiqtlslvz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtyfnvfgbw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtzjywgdcz.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtpnashysz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtbazuyxoj.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtbeaqievx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtrtnshwnb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtabwredvq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtvoaecmzw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtyzumjqcb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtyvmdbacb.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtrvalmvkf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gthfvxncvz.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtkfwrdjbo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtjuqxxgpz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtmrgrwjvb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtufabbcjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtnbsmohkf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtsuqblbgi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtiuhkwtev.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtafguhnlz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtsordfytr.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtbbbcktpx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtyixagozm.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtkphrrwya.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtjljgajjj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtcqshniad.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtfpxasvif.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndygzsby.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gttwykoqar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtrxxqaeyq.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtccrurvnx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtlmwoijcu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtxsyezdxq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdcturagt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqojoxuyc.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtlfbihxkp.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtkzdvqbqu.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtfniizint.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtwjfylben.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtoxybutkx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtdrfhzhxy.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtpcjmvggg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtrwxreisj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtjweucypa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtxpnlrcan.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtqubmqonf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtesasuzyq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtesqqpawb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtudeldgvw.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gttgwboavl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjvswqrsh.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtacpsgazn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gteyufwbza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjvwfdlt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtrdymecjz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtwpinnxib.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtrothmdwf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtugcawxea.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtqkuzztli.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtpgidlubj.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtgynssqnh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gttzxxxxus.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtrbauqnce.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtmlofrmci.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtzegevylq.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtrtfeektp.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gtzsstarbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtuenocjqy.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtaxatjhps.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtqmbscqhl.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqfrcgkv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtpqodznuq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtmuralbfs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtzysswbva.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtyawpnhtn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtnzutvkzk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfhkulml.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtvygxfrjv.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtskwwdnqy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtdnoxiwtv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtapxuyfnn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtaimihbpx.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtbagisbcs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtfhviyfqc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtsguhnxli.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gttxureyqm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtuzzqiyxb.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqfyzvpg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtkoayewpu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtgarjsnqq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtobtuognf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtjocoixfn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtqalaainc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtwlxmmbjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gthkyphyct.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtrjwvxuao.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gttyxzugkl.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtnlxywagj.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtcbvjwypn.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtnlnygzll.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtdvulyvkj.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtcdzhdgvn.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtzyjfncqi.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtmocejgar.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtmkapgshn.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gteptrstio.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtiqvdepbv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtjuwpmzbw.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtcllandvb.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtecttvhrl.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtndtmpgcz.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gteolgtlqd.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtqtyfgrjr.html


<!-- 参考信息 -->