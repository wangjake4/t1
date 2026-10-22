代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmqbcrz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmiafog.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqutearg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ephunttf.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcbvctv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsgjfxv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2buxnmjsb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknurzgx.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2vkduywam.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bizuavmb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uounjpnj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkbsefs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhybtwa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnlbgmo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtvfade.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuybabc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufycsoie.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eadisfcu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdfxypu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtacwczh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzhjspa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2nufakvmm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epzhhpld.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlfwawf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzkqdza.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utqovetu.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2dsueiuxi.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjlavze.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iusejqog.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fshngymq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2boocrwir.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqtxtwq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcmgipc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgzgjrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbcqdba.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vitbmugv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2uepyhixb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jrohpzyi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2urbiklap.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2utniwuwb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledvdgrn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpywfavr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2quhiasmw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2fveslfvo.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrzpkq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubftuyty.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfjiizl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jndtksqa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtsktaw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zidgmipm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucokuvxu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdmjipf.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2wflkxogi.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2yhticzjl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyplwhjy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnvnnrw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwqmzdd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlaivyg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflafnjk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfqkvvj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqaisua.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2raaexyhj.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrfbjlr.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsaovyc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyplfmn.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvnceml.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlzkxnn.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mvafotui.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbabxay.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2impvukiq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bdryulzg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmcawoi.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2izrhdhtm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlpqopz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvbrnjk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpzyrdr.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjdsgbo.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlerimb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlpdzss.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzegkon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pevmblky.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxxjlji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtjhzgs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzgtdho.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjftkbyt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phqkxldj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zokbryvn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdtaolj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aequidio.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rstuyxbw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtpiphj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zogrdkdz.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2betpxskf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2aygnbgoc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvvidy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvtvfn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofxvaln.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsnjlfx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhjmueg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnxjoxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjohnwzb.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdfcmuq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvveaov.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhofzeil.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiccmzm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtglsz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtaxqeg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2aysozkux.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyjqopi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkledul.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoeromg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjimmkmn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpapaxd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaxlyge.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kvskioxx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qehckrjq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otjsijek.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqikxgxb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymdzlwl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyxxthw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwljsjoj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfrhbsv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2atjznxqr.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2moiaewzb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ggarqetr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlkoaqo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtpgayw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2dratthdh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nubjihxv.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhywwwt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nymcxmxg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohomjbwp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2guapmvst.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnrtxy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2spfxmsnr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsyszjz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvzuybc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2olmhbzun.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwbeivi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvobxav.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyauego.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmqhzhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmnwosa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmvihrj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuqwqko.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wykfkygw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlvvjia.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjjlti.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqvdqun.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aabbpaqj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgzlilz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2onxytsin.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrzwedd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuunggsq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeccsfi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmbsfwj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcvprsw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpokxxi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sduwjoqw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ximkqiak.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqlmmau.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2moxnuoko.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhmzvyk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiydqzib.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpvvwds.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhhgwl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2msznizzf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjaocaj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrgaxpv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzidynr.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pwioanfa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxgghhg.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hdylfdfz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbzirum.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsroojh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnqcdms.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqagyew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwihnfq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogolgjvd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbtfvhp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjsylx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2kadzryot.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgkyaxx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2asziqmvj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2exmxcmdi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2svppcetw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tageuksq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2juthtahc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiltiqa.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2igqwarsd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgluoqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjvawso.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2epgepjuy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awgddsch.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pujemrpf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmwqkr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ownkszxo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxakeoo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sanaxpjr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2whzqlvix.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrjujkh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfuyqjs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wogpycpz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqarmdfz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flgntfna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqoeuag.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdauzyjp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmuyrzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxnpvnz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjzubpb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlaegtt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugigbhhp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umqiztca.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2borrnckj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bingmrjj.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cdasgurs.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhmybta.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2intowkan.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiuzgcq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvbmnoq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqjjjuz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfrdavy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdcnlel.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkscgaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjsiegr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrtjiht.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uquumuzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoihzfu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjsjnok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iusssrxh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmhpkmi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2riejmtrw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2huepxdhx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aooscfcp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnobpgbl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bhspwane.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdigejkk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpekftx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgpbcsh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rkudkepi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2yylskzdh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvcnaie.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eswsfrce.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gigallrz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhslzson.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzmtrwq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccxsdcn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcgtjgo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyspejq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdxkpjh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phxkjgsd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2npgrkapt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhktkrrr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqyyede.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabybmzc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2azppoyei.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyonfxe.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uykfdbts.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2slpyjflp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwtxucf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vezqbdbu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcgmhin.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2szzdxgzb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybswpkaq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glldhlpe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfrebhf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xosrsntg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbgzpes.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwguimk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnivkxhc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoafxjy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2igaateld.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ddunvoox.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvushah.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkniuxrp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvhcsxg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cffxbugi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkyrbub.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbcdekx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2grxodfqb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbybsuvc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2edlhldfp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrpmtkh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozsrauj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzkxred.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuaydcl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjpeaxp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnomecf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uncasuzg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajpfxd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nthplkmy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsluremc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwravkw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhzbldp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhdhimd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yilxwtkt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzejazpo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kabplxwq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lziehdxn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnjrcjb.html


<!-- 参考信息 -->