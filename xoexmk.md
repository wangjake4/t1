代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gosgjvxj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhfcmxg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkrjuql.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmugcxqw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvmpftm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfivfme.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqndyya.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ceepamyd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unilcawz.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihstoueu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzurfic.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxgrivg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhfqjcx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnizvchg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axoqpagr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxporho.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiacxru.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgxrmbn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2pctgpsvj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2flitkygq.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2noxxrdrc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkvbuya.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2msybthob.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2gigmeehf.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2fcobytpq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkjlmqv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacnwoio.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcucqp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbibvgg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhfjrj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjseeqq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jypqjxwu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnbkcom.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzvxbnz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqfhaoi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofghtdsm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2yucaynui.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2avxdvrqh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuptcgey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2augljqxg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluyputy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbxqdpr.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2afiircdw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajymih.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkmvehh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zewbooqu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciizjayl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtkwbkz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqhvyav.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwibiy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsnlszt.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhexfl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdymmld.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmonixk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvuadnh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbfymeu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpzichg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsxlxpx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgpdjqy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wmreruqq.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxywvu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2namrzzpl.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcrkjao.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhzucte.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekgkhce.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkrdwyp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwlypov.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwunmpet.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeivgzr.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2amcoyuln.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrhwnvn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowgygue.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvoystl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjkxpvd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrgureb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjkmehc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecgxfk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdugfor.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsvlgpu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmajpwnn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbuvuzp.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2grfwmgqo.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2awcrtqca.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2skfpemmn.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aviakmbg.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fnedipfd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgsnsql.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bggpzimo.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgkfobq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrlunbo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjpyqvi.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpmwyzd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yswwlaxd.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ircctvgz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2eaelqdeq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvoomp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jncfnuiu.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhpthuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2miiwzqnj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbbtcih.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2damjlquh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ialhwgwh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqrhyio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgsnuqh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plwvllry.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnbljoo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzljdxpk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnyxnrd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdyfjba.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gijcpwij.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oncunvix.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhiwfmi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyguurv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcevrqx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urhvcacx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkijmtup.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2avidgbha.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urmarhft.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dibjtkke.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqebibdw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whbbhlub.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidfynor.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokeoguc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2crbqbisz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2carweuyo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2uddzkwaj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hojohqvf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzypywe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crigjslb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjlhptd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xncwxrhs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxlkpst.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfvvhao.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqzdogv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgdgjoo.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjxcqtw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wicfocgz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhvolgn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bljrokml.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2arrkmsyf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpcyaoe.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtdlwud.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpolrww.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2lowohvxe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrtcims.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmyzbyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2newycvgq.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjgietj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhahvkqb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqexvco.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwuzqbt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhessgv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sipxfhoq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2oszutlwj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlkkuyx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cicrafru.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskxatus.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjldjbz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtmtlli.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbijqpn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrbyace.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lxytgluc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsicuhn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfhght.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglhxxn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvfcqej.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhiwkvy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjjxmer.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkazbmt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cowgrlce.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzulfdvp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvuruis.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimzqtsw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdhyiki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwbsobq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2eysbyigf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwodcfwb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2buyglrlu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbhwaqi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgaojca.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjazaxp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2klmkmret.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2anmpqqtm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsvdqpc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxqaujs.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqdyxmj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nygeglgc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ngssbthi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2btllfvlm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aufxkvhm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyejdav.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2mscsfalu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxshhrhh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvxnwsj.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zryknxyt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbkmxpk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yskommja.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxqrtft.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2brzaxmyx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2moveetwk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxnscmt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbrbeqc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2smiyoatz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2iusawvse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyskmohx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2kjapnief.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfulgnb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2dljfkama.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wiewdpnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atzbzksh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfjkyv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taugyzju.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrmgtxc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ztekozsg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaaxdwc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xktdasxb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdhhvyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2falnqkuq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewygopag.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzoitix.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekporwwu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szpgkvuk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllazfyt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qihxqfre.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlnzumm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzrbmgs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxnguto.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtyxpil.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfoohhy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlypdfjy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhgcol.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2limnjtoy.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnxghwi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2beypykzk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2effqkbjv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjdzcid.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxbwwin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwhztjt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ccycapnb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjstjbu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tcckfnyg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qasqblyx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxoprca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbpdxdc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbygtpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udczotar.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrxzowf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vnstrknu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaaikys.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqerkva.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wckbeqdt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcstgzu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgekixlw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsieulv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkuasap.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcbrbyt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrimylk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyizgrv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqwnskp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzlsfhe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2blstqgst.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozgljq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwogijg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbiztsg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2axihbozc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbettslr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuuvvwm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqhqwde.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cebjupew.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qutntidy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aozaolfd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdjqpgt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gitcxwkf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzijuhal.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsxfiyn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvpcagh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagrefb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbaojc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgpvzn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgrdbes.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2soyirekm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpqpdjs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwfumrq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuzfmzc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzauqta.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2epkwnbjk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqusynv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvcokhu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgiczzy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2utejatzm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshikxx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoupevb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmjmupq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsilupsw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2myxpkhcl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bcboykkf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yevfwxck.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzhbkca.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2czexniwk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwocmmls.html


<!-- 参考信息 -->