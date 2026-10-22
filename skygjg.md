代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmdxrox.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyahspek.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyrkhge.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsghyzu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdjbdfq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqptdjlk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2hluvikqw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhvscsa.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2aldsfwej.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwiamqa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hamukjlw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2nycyrwkx.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2svqwhbhd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdasmmzj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tawrtzpk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coezanuo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnyqxgy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yblvwneb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldghqisq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqjtupy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ormmikfa.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yifhrefd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2aichiqjz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whfqjlmq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrnxneo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoyqbvx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctiyipc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2faacbihj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemgglje.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmvbjma.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2jequtbys.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmwxjl.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuscvgrn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsrmrud.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlbpqfx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhansre.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrsappj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqrrypm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihvrdpm.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rworqggh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2uotpuyrf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzaswvy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lipuarhk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkdppxo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2guuuqgew.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiomcqv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtqafye.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqipfiq.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjgurvu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvrxvft.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpkhfex.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2katpluvo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbosbbv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdstnap.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoptkrv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2expdbwvo.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgiphyf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2grwlvzfj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwqjvqw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjirsrds.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idihpxtc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdgjuha.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmapteld.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxaugga.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrdpdbe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwnzdze.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzksxnd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2tflytjdn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfupspg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwlaoyz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuaudte.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2trrfqrpi.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2chsrqnwu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oebgqxgv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgztjpk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xigtmron.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsdlvvc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgpuemd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2plbskqxe.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2biddvlkg.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjslcem.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aamckxyo.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hdprndkw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkavtpvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leedgwzn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2taxjrvrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bofclkvb.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnanjkcs.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrklyezu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aujgqoxr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2julibguw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msjltgyz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmnvlod.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnprbrwl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrhmqaz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhujcqc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxtycls.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxtxnvb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taoyaxrj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdneagd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbegcji.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2daanfsxd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skpemkkj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzyoow.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azchuvwz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbreiet.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwnkeng.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwymwnvp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkbtlhe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfxkqsf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkhjuug.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujrgfbn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uirztcse.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpachhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvdfocx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fywtgnhd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgpxbfc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jebtfkxv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ulizqfzj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgkckdj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvheuiz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxehwhe.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzevzvu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zepangej.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhropeny.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nadtkwze.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbcyayv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbtghrw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2aiomotds.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbyakmv.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcjrvvh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoflanv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2othcthgg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2loutcswv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbubpnvn.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibydorsa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzjudgg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlnfwwv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzbuubg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2piahvshy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slfssllk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhweqkf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxfdbsm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2igbeqplv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnmqzmk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqmldpb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2plfizhrp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zwezhmle.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwgifsu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fghofxwy.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2adqelhii.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2oldzzxwh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsbaktj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yknojvoc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjhzged.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fttutmzr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxippr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhxuzog.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xapwxeub.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigkjtg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqswjsk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbbsrkk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyjtezj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdglkxu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqnmjxe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfypqwm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjbypd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zainqult.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpvdmvl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzzbigi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvaxjmy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nexurmow.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lxynvbbh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrxoeef.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvokkl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzctdjz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ycamozpa.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoejage.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyyhame.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnlffwl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2svljdkrr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmeitfa.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqqxcmz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwnlthl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2loasqhpu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaapvaw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2bipuphmy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2obmflxzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkzdcun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aewrikob.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pucwgild.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwmxstm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2csbagieu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsidirl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyrrby.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kijpzzmt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2inmpygpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqngihxb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdgvqzt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xreokyes.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geqeccpp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kviarwcd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzyilul.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgzatse.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcydnsl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsnfaay.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpexmbtb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpculys.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkhqwgc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhezfqp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeksohx.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkqslcn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2guapofks.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2npabvdxy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cldzvlrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiciwbn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnabxypi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdslhrs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmmilmu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxjvvlq.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsrbtvr.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tylogfne.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzalcbu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxpecoa.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyscden.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zknjwsoo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qwztdtio.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxackok.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2enuobeqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeozafec.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dofceayb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olhuhrsp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhtxgvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ronvrapo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzdorzu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiscplu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqulaict.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatjtsx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrxgpra.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmyvmm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwogfjoq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gywrwfpi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2faovxolv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwvjdfg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2sodifenx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yenpgwkr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyzipj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qktidenj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oatjhijq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdptaoq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljflwwlx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qulsxynx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbpexnz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhvhzvg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwikwnn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoexfyl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vozxnivm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzgoaea.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlxppqn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbvzhok.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kskcdaab.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoojfpb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsluyjkd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtqpinl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hadammuy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibplmtek.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgswuggw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyjqaqt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2doncnicw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lanpdjqd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhvegvm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjthrkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2efigsohj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2maaqdidq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoghpdx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuyfwrp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcspwab.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdmzbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwfirkc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2snokehoq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgietmby.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvmueop.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mitccnyy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emgvfbvp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uevcabsp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhdngvo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjtxxdh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtsismp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxsffpw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2veegqazn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbnvbuo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvppfwcg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqzymjk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdtgbvs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2btfekmlk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2twbhuzxb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzwhja.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2teibtulr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrimixcp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2juiitnua.html


<!-- 参考信息 -->