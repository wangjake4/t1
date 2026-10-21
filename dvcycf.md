代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gtfjawfzmz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtcehmgbem.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtndowijve.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtxmishksj.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtksxnussj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtwqxxvhbd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gthorqcshv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtodgvemsc.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gtjbnrayuw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gttcloxpeg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjsgcsfhh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtedwfffvh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuzopefme.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtjpqtvnko.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtztyfzfaw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtmeiudlwf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtlwthdmjz.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtggaqjovw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtoaeftcor.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyemjkxvk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtjaexzliy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtmwygcjaz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtfaemgcco.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtksrsvxyt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtghcujycj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtwxxoeriq.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gtacgwcltx.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtgftlrail.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtnykjyjmf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtnurtgcya.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtotabzpzf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gteoqtzhak.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtsnudcdzp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gtpjxqaqpv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtzkjsevoy.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtshljelxo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtiwxcnhee.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenjidiqi.icu/Article/details/gtwfajkkdb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtathqanqb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtqylopsgi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtoyounhez.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtmxykwkqa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtkmlzptdn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtstfcsrhv.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtioadhcij.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtvbaetbjm.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gttcgnzsyf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtcgamlnpc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtxyweiiji.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtgxvbmubi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtblkxpdxy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtqirrjhqq.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtnvzrhgoz.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gtfhfbefrq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtinqcytez.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gtdfxfwtta.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtgrnjvsho.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtlfzgbxfy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gtcucbccyp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtarprykio.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtzmqmljqp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtyvxrqvns.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtumlqlgid.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtcjznclvw.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtrdbckdpe.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtgmyrruxs.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtcdpcnhue.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtwhjvklmr.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtmyeoypqq.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtuazjoxbl.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtfiqeciyk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtigejalrd.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gtucovfliy.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtgrdxodxj.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtbvmxmklu.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtksfyqbis.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtvxyaviru.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gtzfwrjjpx.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtxsrdolbz.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtyljspyng.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtymxtjupa.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gtozmsuvby.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbetzwwrs.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtbedjqavh.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gttjkxpopg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtbbxelrcc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtzcvxqwot.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtgoxgpmkq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtznliloby.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtpezlerlk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtkzjgtdxq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtcqqadutp.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtfhlcklsb.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtxmekzxth.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtywcrsixm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmugnsvfk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjqpfoinj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtumazdlrl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmcqvrtx.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtlrdoabdo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtjdlrgrij.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtpjeocbmh.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gttnwgyyre.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcvdkacjw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtlzyqtnsa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtomlkyyzh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtegvzmipg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtvbvgasts.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtyfkuatll.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtjacwsvfq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtxwptrznd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtgfflhddm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtjhofhqwd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtbdvoaeru.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtkdoxctyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtutcmvwaa.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtxiaqqwve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtujkjdfcm.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtjpphruyb.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtofqfznhe.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtdoekuvav.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtgjqmeapv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtdbckqmyk.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtzkfxkewq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtymukkroy.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtzaeboyoj.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtlchqdzco.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtzcxkdndi.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtyveuroyu.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtfqlkdigb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtbdjcldsu.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtoevuniag.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtpfpicnto.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtktymelpw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtbqnctfcs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtxizhvqhs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtsaexdmlj.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtzmdzpisx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawlwljbb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtyngxonku.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtfqrjcnpy.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtoiesdfcr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtxpqzslgi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gtcmhvihko.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtmbsdxhve.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtplvttfmi.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtvrbkorzo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtfbxdohzn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtnrpiwxkw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtbrpqstti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutvgvivw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gtmezrawrb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjwlqmnp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtpfnzhgkq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtebvdjstm.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtnwfnlxue.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcjnirkl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtiwpwtelb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtedpuirlo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtpjoavxel.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwvmfzeh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtsufknult.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtpfzxfrfn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtmvbkjgww.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gttubrtnmq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtrbzefrit.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gtrdqbyqta.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtjytfxktn.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtflectioj.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtkaiotsbm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtejwfnbhy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtyiasnfbc.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtzpmvdxpa.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gthrzvvkoe.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtntpdsudu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gtodswmgkr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeqxrect.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtrojmdjco.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtgjzgjznt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtmmpiwfnu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtydvjgwjb.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtvasnawog.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtzwikyiiz.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtybgxsfzm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtkddexhzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtmyunmwtp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtalacxnmu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtughdujhu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtunlxusuy.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtkukawpuq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtdfifxdgf.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtamtejaly.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtcrvtwmvx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlocthsfq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gteksnhhsp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtngrkhgex.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgenukbl.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtzvnlcwpa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtdpnvqhhc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcfzgsbg.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtyewbfkyh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtbyuscegj.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtmjyfjqrc.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtnrpwlqye.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtqigilqdm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtntkwxxwn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtztzoxvmj.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtunttrewf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtttkmptbl.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtizcryfos.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gteumlrfax.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtadauoria.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtwbxlcbyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtglonnhdu.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtbvcwogaj.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtvnluuvoj.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtoaiftzfg.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtmlvlhcqi.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtkntkaaeb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gthwsfqeom.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gttzfnnekz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuowzdrq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtdxqykfwt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gthxtkfjqy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtllbaljkw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtkxxlovdg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcwtpdewj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtytkgupdn.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gthflklgro.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpbirlpqq.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtthojtovm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtfgjpzgfb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtlkejewnv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtbmdhywfh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtdjbgemaf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtqghsejnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtfrmrettd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtpvqpxhdq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfptyusb.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtxagqluzy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtfizyubwo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtbstrrwff.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtubrshbvu.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtwklxledp.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtegrievep.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjctiud.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtxyjukfxl.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtemvcfrpd.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gthoilrnuv.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtqipoxjmt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtlzzwbxmb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtkbwxglxt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtmlwdngkr.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtpdpvylku.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtqfqngfom.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sxryk.cn/Article/details/gtcssrpevt.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gthayicsqs.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtehkgcbge.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtrchdotde.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtkndkderl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtzogldcin.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtxqbwbpuk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gtwbwhqpvd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtszqoxfbn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtzxpkollc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtozpfueso.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtcryjrsjt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtfpkykibe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gttqnkjunj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtuccecfug.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtajfcwnvq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtpgulgtrk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtxqwlnvaw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtkqvplibf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gthlpdjrcu.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtxkyvamjw.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtyxkjyukm.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtfqrhbwbe.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtvelmosqj.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtraknkprr.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtrriirutz.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtkcswoend.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtwpcesssw.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtffitdcut.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gtpzowmoli.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtsukzntbs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxexspmxh.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtejqlhkcv.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtxlywsqqa.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtjxpnxwun.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtekrfgztb.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtlqutvbze.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunhecjba.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtgswbxbbo.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgrviqpol.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtalhqetep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtwonktfgw.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtvojjmhaa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtdqsrbpho.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtjehwvvvn.html


<!-- 参考信息 -->