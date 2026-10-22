代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgdbovi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzyffxf.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cvczktre.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhckbvt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjqfsec.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbkgnvl.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tussuktt.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pntwbyfp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwswpkw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbksxkpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymckfdsc.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjjucy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2yvryszjb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2voorzyeq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkevhmv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqbdkwb.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvrpowr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywjrvep.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzwmiin.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurmasrx.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqqpudm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjxextm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfolhcyv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ornarhda.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlqdzua.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlcesty.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eepmaujj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpryupl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzewlvl.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2psfpykml.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfczaix.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofthbook.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2bavqnnjt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2dyylybqf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkpinwe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wackzbvs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgbbkig.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsrkywj.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2poceuvys.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrycatb.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyylfxy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uorqybug.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2loqpzigr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jviigsey.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsurecm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuvqemh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2huetsljv.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2niwtnifk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfjyqph.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcercih.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2elwtwnwc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyybauz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnuaqnj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueezkzrn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvxnjcx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvjjalo.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhdxaev.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpfguyd.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoaorka.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lirpzkao.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckfxnqn.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqdqgyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyfijdr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjuijyv.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrjiamg.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxfxegy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2aokkxcqe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sodlwxid.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnelvjd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pltejinb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flfunnbv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuhkapq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xheqnoze.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczxowfo.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkaemzz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jupielpr.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbypzto.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iefbtaqz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdydpot.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfpngsr.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gofmgise.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlwtxxi.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjqlgkv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiqqvdt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2dndqlbjl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geojbbma.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsujpxbl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnythuy.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgtajnq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktyslsr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2naujrdzd.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpxdxtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdutfkl.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2txudawux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnpmgrq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktieyash.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcmykty.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtysstdm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdrvyvm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnuvfrg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmkggal.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2euewwkfp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxgyoya.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwpuoau.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crtahhfi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2zocvedwc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbggymp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzhyrjo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoabtsqx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxooxwy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spssnwyj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzpvupr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhckxxnd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfibaamr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmayeep.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbulqbj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqtgfau.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfrisrt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nugjqwvs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmnmcnk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tidivwpu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbygghs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmeqdrt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnazmqts.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwllczie.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhckugz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aximawer.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsfvuwb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqvndqy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpzrhtq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmpxkse.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmqieui.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnovcin.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bytblddy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmldpte.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2knpjweal.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2phtvexjs.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2acsqefpe.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2opyitqdh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bjitiwwm.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjxhcsl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2pyalgzft.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvejlucf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbyyuhe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2udtzjxem.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oohkagju.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwzwfts.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jktxfhmg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjctrilo.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2pjavsroj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsqsics.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrwnblj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvppbru.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtlwwxq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkbmlho.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrkkwdq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2riqdwfkp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtizzryj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgocwwk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2uufpwwpc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcifhdjy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoocpdv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtooeuwh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gfppbmvk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzgsxek.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhydcl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcssxbgu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pztwpqef.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shgmdbjf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpiagjm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfshtx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qoersqtm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubestutg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mraywjam.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgwvewe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrhqmce.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mozyyybo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nenpsnfc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljfjan.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeqtqdz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2itcjsybt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnjwacr.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijqwee.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvwynln.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aspqgdxy.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvxrhyv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwphkam.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfowptf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuwshbz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2aswdvvum.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2efyapoqb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2apcgdekg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfjqvte.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2iccojucr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mrauthcb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2maeiecdt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2alstdaab.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgvenfk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkohhkjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2oeixchgd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjzxsdy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2itqewesc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akgiuaie.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hahyysme.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoklbng.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2majstwig.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmekbvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2navvwkyr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izrsyxil.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpcpord.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcruaesj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2axtggspa.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdodtst.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pvksfkog.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbwqdz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbgyqpv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qesrfvxr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfojgpk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxxdhdd.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzawrh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmoydae.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2heegiiel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqnsda.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgfuzxz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwstlapv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfyoxva.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwgkoxs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2suddirtr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zfebfisu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwanrmzo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wwegnwex.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnqqlfu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2msyicscb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oadtmwav.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2saoqgxgd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsxfkrd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jguvaojg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aufgqszi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvxsffu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mznrwazt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ausziofu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeovhpro.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsbjxal.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2aowdcruw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkutfuio.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2smacliry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaefhix.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnvrtsg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kourvybd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnollqui.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxtvnnr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjaqfnu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2edduklnx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhtbxgc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqchsciu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onzcabub.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yywhkmis.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxgnwax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzycrhq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ombfjngk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdavvzla.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2junpxkrs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvhustm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuqtmuf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeqdeqh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpeavxf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbfrvbe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzldhtg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqvxmpz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ankrlgwv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoicoix.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpmilof.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfwnmib.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fetovvns.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fddmzmee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxymtqr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdthxfly.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzvwmsh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2corhilwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ignymtdo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhojeugh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vasfciua.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkgcfas.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2whuqenpo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhwkqto.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuhbbfd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvhsqpy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpiljlg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yozyaukp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyohyqn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2girnzuqb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmhglm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2axjszrlt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2useokcjg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vylobjoo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgcdjaw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apmysnnb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cexwpskb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqllrem.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dunujnjn.html


<!-- 参考信息 -->