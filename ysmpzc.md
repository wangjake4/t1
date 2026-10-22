代发 wailian999

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2ldadvhvn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfynxti.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnwnlja.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iskztklt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzxypu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sffilsnn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2liijxuoa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdaylbm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjysjov.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kuolqzdq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2sggjaslb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuksrik.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgjmyqj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2lumrhrct.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wachtfra.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzadkxr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeriarkk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbskmlok.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2motuuwtg.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiakqkw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcmgzcg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwnjdbo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzalsgil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlbbjkh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2utmuqslm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mjigwiry.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfdkpzz.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwruhrxo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2fagpmvas.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgeixnw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2symzqkye.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixjxtnt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrazpay.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clftvoro.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzaelyh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwhszae.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2haourygt.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgytxszw.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldjtsrp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjplcfb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzguych.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnzmycv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkytayy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmjgiix.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcmrjqr.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeesews.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2exknojtd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvzqzwv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjkumez.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uccxrnrv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzpnwga.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlbifgj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwjvqch.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qehquqao.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jupfvctc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuspwfs.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2gozngnxi.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkcpjcc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2llmmnglw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pezkqfms.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2syopodnv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tqujobsj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgejzr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpbjvcn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxstkiw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smxieraz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhenxbl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiumynbn.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udjgheft.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjsxmqj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbsknyk.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkkkgqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbcdkcb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vdikkgmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeppczg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlksvhly.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrbttff.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjnxjux.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqfmqcj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypouljod.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgoywpg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnbrsla.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnavxkuz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aevfdvgb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qszkiuzg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2itoszhzq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snnrjapo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsskbutn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqjamsu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2opizwlau.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urwvgdii.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwtlmhn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2trtzlqyo.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmnzno.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsflmnx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wczeddmy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsorxeso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrvvuvz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tovhmywj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbfhpni.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wilzbrcc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzxzgdk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmelmwtm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrhveym.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gohpixeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfavnto.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mbttiesm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2syifkagn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bornetil.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqwsfip.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjtiepc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdcnhdm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoivjhp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiggdtb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgydmqrm.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqthgakc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2iijnsiqj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlxvlrx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrihbgft.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mhniqmrv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmphmto.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2isxwdnak.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvxpvtm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iapphkav.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfskavly.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2inxsijiu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqggtag.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rojumnol.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuclrrb.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfndqvrx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2riutnceb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyzelhv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnchjlle.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2udcykxky.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvgtbfb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqrgujk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmkdozs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2aelcftxj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2haeblrle.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kwewyxre.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hugxgbsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhebiwsi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknisyjc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfjdojr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcclrbwe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azhjwefw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqhnbpi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2brwrqlaa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzwvhxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnsxdei.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmxpkgx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mukczofy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chhotmbr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2btjluwej.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgribeja.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yznltipe.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rihjajjd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xamjtprf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2yllgmcel.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cpziskuh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xrknfvkg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cpedogjr.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuninap.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2visglryt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2adpbimbj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2izzohnye.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2loaqaaec.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgtqej.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtszvxqn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2omyfgmmq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjbjdqu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nsknfliv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2skekhdqn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjbqly.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgmxvfw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2uppstjwx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuaznlx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kaffkxbr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwhlotj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgrsgjq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kldorgtq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeqkazo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfratia.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdvniw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmtdkrj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xawsbuxs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkqexj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmmuuqw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfobyyev.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcljeji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2huuahzew.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxclzjcz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzmuqig.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsfacov.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2awwzduzj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxxmnbp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kamtjvra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvynswl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntodtoef.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgnfxqv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttlrvk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtlepiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2juvpmrdm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fezvonuc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxvlmry.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcyjsfc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwouhxp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oozqzigo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2chkglylm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcfwmga.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2swzcnson.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsbafwu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zrizwkdq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmmuqek.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2teuullyz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sssojblo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlchxbw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwwzuo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuphqsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwowjizs.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhennhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjbcpcu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbetfkaw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2eynsugik.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpepigd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyesjwea.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2enyhhtnt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gveiaytt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lshdjiif.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikibnahp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2damebziz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjgdmwd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfdzmo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiahpteo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uilmsupw.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nouhlubm.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkxiwka.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkkgeeh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2irxpuyyf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hijupkqg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuruvqn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhteibm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2txtjsxct.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrmgeia.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2llonqsqi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwshikpw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbydwbp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjwfxxx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lazohmsb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmraxjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsbhdcw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbnycyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdrfdms.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpapytvz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyczhjr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tijouaio.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfwgynt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orkleisr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jjluvvog.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rdliyyzs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxmybeu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsoifco.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjogdqiu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvqhsht.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2myicxjdz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jijlnsvx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2szuokzyh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2chiddojq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmajnbix.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfyoqkh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgxxgbm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvggpav.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2esmdgpkq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2polhbobk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tikdfucy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrouxuc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihckrr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2isxawoad.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmklwcd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeorczy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhurvddv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omliceuy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjedwed.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpytoyoa.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2omisonyr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfambmvg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buiakhul.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dadiabev.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvbdxfo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdvgyev.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtnnbao.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zntnwcsh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxtqznw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jennqmyd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rheygneu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlwfeyv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhgcdqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtitkxcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2rakrvvyh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmslsqcq.html


<!-- 参考信息 -->