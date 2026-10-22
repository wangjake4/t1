代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pankfxsh.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhohtpeb.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqghqgqf.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhxhwnz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsteqtw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmalxcgq.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjbmsii.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhmyvee.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2tirnhyzc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2itfkocxs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2modyfihw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2puplvmbk.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfiesps.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfjuict.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnaixct.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdijhrp.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2mndodlhx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjnmcgy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmtrrih.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjycvco.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtwbwkj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffswrhg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvtmaqi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaavddg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdqmrn.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzgpiee.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2klskahib.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tisjwdnu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2oisxsnwp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2kkymrndy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsjlque.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2httjyjhz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffomnlhd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2camgnuvb.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2njaiywrm.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kibjlolb.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaaumks.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdpellg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wybdlobd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqkchgj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2bkceruia.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fznikzcg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjzuxgs.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfcdhyl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zslxquhv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lzltcoxk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2avagnbqy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjcwbq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhglnss.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zebhptvx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2horwfgua.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvnscre.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvkukrl.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnhdkyd.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsqwncz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyfkujo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fajqtksd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhkjpws.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmodxdgi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiszihg.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ridmjnxl.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaqlvrf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2waifxzen.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrhemqj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dipqcyyt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbfunmh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qappstvv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csxppivl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxplgcpy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2foexxixw.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2iysotsfc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2iymasaob.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwkszpr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqvicuu.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2crotgjjd.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ufatobus.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvmurtl.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nevoivss.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zrweghgr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2znmlafap.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2nljyeuha.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvkeizk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmpqgkr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdezbc.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxzycuz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyppgrl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2spyleqqr.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbzmbvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzngwpzn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvacohz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hovapmvv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2haumrour.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwrtwnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrstkoh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskinpuy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeuhhai.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rifeyfpa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhugvud.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwobnwni.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cckvhdbx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unuhlnhc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjrbjjl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auoziawt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemyghpx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqaqmxx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xujjgwth.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkufesl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbcqvid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrpvrjd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czsjxaoy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvulyhcy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nituxzvq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfwxlxs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjfzqet.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoseqjx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhynzpfd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etcijcuj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hglzisga.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcuchcc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2edqmlxhq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aytkisml.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oorwaxit.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekhosg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrbxlwe.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmqfxz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfmxrpi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2loclzwmp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2bplgyaoq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2saytaoro.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjyjhgx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzhnmad.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2btddzxgq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2libdiibn.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cavhrvwv.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnzomtt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ardfwvnq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nudrfgoz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2frmmjnrs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqusjemw.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzfibyx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2awyqiggf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwkhicz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmumohiw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbzvmpa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqejejg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiyyglt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgacwuy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yclexbiy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2klasnmoe.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrwdvts.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fctziydh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rbppoieo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xedjazlp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlyrbpp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rajuimnf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2szrktvbq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrnbahb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaemqpd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oymsxcuv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2mllztlar.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2athfmody.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsakmsj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aidwomdv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2piglmypm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqvfdwv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2heoekqjz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxtrzyd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2izqmvpzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdqsocn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxuwrdv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icxoemor.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlebjgud.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vutauruw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2minumdlo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ciocspyw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhldrjm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lerabmzy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2almmrmxn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfegidn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnggsjt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pixdkefl.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qynftacu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgzuiim.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2laslxvxq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qiclfqds.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhuvsfh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxbgdzt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jqthcufl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvwhdzs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhfnykq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzepzqa.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmjhqcf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhjrgft.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eznucrlc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuswwzj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhcebkn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpdvmka.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ucytfsfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrzuxyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ropepbcv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xcggrhzs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luynlnpp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxjfyeh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnlqruh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmjjfkl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdhozzp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzlkut.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwklskwq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsxklct.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgjpvny.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdwktfo.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2slrptewr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzpllsy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2skkohzdq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2unsdnjzi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xuonaveb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrxwrgi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbvfpcl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ypanophs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntvctbx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yakiqazp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfqruwm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqcpcdl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tvldyqpg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2rsccfiim.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbgzmgg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjylnujm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2crodxare.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2shyuntjv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdgqazi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oetekjhy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqixscp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2scmlifxc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tueetxzu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsrtyeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuiwcdh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dptyhcxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvzrpsa.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipimjmaq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzviqxw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rikudhnu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlrvehf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvipluw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2czxdonsf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzmlgrs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkkqqzh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpuyoqs.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqkjycd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaxkldm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycojlaaq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aublrvuj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjxkiwv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikblxtas.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhljyul.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvxwret.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmvmcln.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysakfxyq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xidvwnnk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdsoiot.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyirygz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxagint.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrrlnbd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztcnjot.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwtqdtd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwldie.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgrhsed.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytolzmcc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjsnruc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfaxooa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wafdyufu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yriwiuwl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpksxicm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgpuqua.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsybkuqt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoffiub.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpoqoef.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yevoaxbp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgvxoss.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqalrje.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnblfsx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2askqogwp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2caghxxgl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dihsxduy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzcuwhl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkohnjfp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbycseo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygodus.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahgfey.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqnqsri.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwnojxb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdkshal.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxohmnc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2orukajuz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoansmc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yylgeeis.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbgpaik.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouywzncv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bduzfkjq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdxsyiw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuujjhl.html


<!-- 参考信息 -->