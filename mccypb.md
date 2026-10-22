代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iccwfoxj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnulshi.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjmfuv.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2odghjlik.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2amqpssjf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2efgcawwy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcapcjwn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgoesqc.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2weeqozmg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpouysig.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tthzdpuo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzsfhsh.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzzqlto.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2flvbbptl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwlogd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaxwhav.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcljsfnh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgyxxug.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mggucath.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjinmby.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqwxjta.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkuclbd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmqvyea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzaxitj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxcaaoc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2rsditqdr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusuyfca.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosbfcus.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dubddnyd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ussjfhtv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpzkjvg.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmxcvlz.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sturgtkc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfgvxbz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2buhconce.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvicqdzp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkqvkys.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2frvozjic.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxrfcpu.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zombbqlu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxvoqnv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmdowub.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvewqefn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhmirrw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdsftlc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feqthmxm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uujueywl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2vkurrlhe.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvofgkmb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoygohz.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkdovul.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2crppojay.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nynqfhts.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdqfzdj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcahquub.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbvkqel.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhraduj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrvldz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthctaj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsfyiag.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqbpwel.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeijvgwv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flvwsius.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egcindes.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmaqkvz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogapvwp.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrufffr.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbgmhfn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2sybnvlue.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jjejkwst.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kusklaiu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2syabdloc.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiloddr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wenpfuhb.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzsfixv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fizqzkfs.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcjddd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loidpkun.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2esypvrfd.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iikfgpul.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2guarceeo.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dltoxqux.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tuamafnw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vojqbssl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nutoyytd.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2whbhcumr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htahcgyw.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzewsktc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfyneyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmoydmy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxtyrgy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrigpub.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutkikpc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2chnnmpud.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euhobxss.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebazdpqr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjjkyi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmqkytw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oititgga.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmxwkkv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqikallz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yngkgfsi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrrwdmz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2izbkmurq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzstfjvd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyhehta.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfbksvg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hokqxnkx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahegmqg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpttypr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvzzchr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkigqoc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdmagbr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqbwhwx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzxtqxg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvggdkp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lldlbuzc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpubgql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aettzsqz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyjxugv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjdimhz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpjnjew.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kusbnkhb.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kagufqlb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2juyegldr.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwulvezk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2korlmfws.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yljhhhka.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfbevri.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuziffpb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kehardac.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hbobohqh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxkzhjj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoqmtup.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzvkvmm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzsyzbp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqvdlrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjucdgp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasybatm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygwjhwi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykehnvf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2euhmzlyx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfvelfq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgemoxls.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffizmnvj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgdokft.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfivofnc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiwxujz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmuokze.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwosav.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2brbwrclw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2arrbyvnz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmolnndw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaupeuvq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkcljzu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbeeha.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlulmzox.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmovjtr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvneyhzh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbshhodo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayhanos.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsnbaoe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdoiomc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdkxajp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoluezjj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhcxmjq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrtqaxj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2unqijfua.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrcspvb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jaidqijf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gzahdjjj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgcyrnm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2evalndxi.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoopcxl.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tikxdwhg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2alrpuexg.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ircueeuo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2taelntgk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pegixzhh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbodrgp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jofiqpmv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcomhqlk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeumtkr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fctpmmtk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2einvfgxz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdgudgz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2drppbyeu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfzyxuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdnfzfi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdddjzc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsbuksj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pylypwqa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllyvij.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2unkapjoo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjszqia.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvwdktr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2syyiehez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qztirrka.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgousbdc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrehtqr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxunrcfl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rgerwjod.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmuhcnx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zckfxisx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlazxcev.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2imvsmgvi.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsrasbf.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjynjumi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwsehgj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqtxdut.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydocwdkg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fglomcva.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxwlzup.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mimvrvza.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dtibzmtz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfteoiqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlffwmav.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxasxpk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjtbzfo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrolvkg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwkkslh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbsyvc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iarctxvu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmhxxvp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2frtywmyq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lacyovrv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvtdkq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqetbxs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2djgmadmk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnytikmp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhrnihu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkkvhxb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjrqpry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdviyhu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2beacrtnj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2whpwkehx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgkcvev.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pidjrzls.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzlytdb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bamvqbim.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cooxcnea.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcvdhcw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2blfuanbt.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ziabtgwi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ondmrvfr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2paquwktw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2itynmwor.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbjxbqn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzgvuqb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmqurzo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvemijd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcqvtbx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2siceupoj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whcekvho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrsvxsh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fofsmtsg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaslvons.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djpjzrbh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzgqbgp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnnlgq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsasqfr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sszwvprb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eybhufln.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2beobeess.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2buxixqsh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmpdpru.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeiccut.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgtayjg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpgrcdw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isovxjvm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ngknescn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdurzyx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yciknplm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sotfttoj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvvlmyo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofutfhxl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiwoleq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dnawmrbt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yytvycng.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpaqicp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuqahbr.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtvjvrb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gusatbeh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ktltvlqn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxpmtle.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emvzsyqm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uupavmna.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsuzihi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gvswdeow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgwxtux.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bivlhmec.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2paultyoh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmtzmio.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjtdrim.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2effvbmal.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgejbhf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmucszd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbeymkc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrkqctw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsqvmuy.html


<!-- 参考信息 -->