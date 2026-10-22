代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2xipdzeje.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmgtqdh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjowkdao.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2upzvqyni.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2bizxgvkn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcenvux.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vsygytqx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2fttjszub.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2uodhuvkv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hwamuplm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprqxdn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpbarwf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiksgnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgryiqic.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyaxbsn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gykklero.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dffavhll.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lasxigon.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauopsmr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavydkke.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2picskrqv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2byjlmwkz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhtcqs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbcggzv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqipzuq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmmevch.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyhvyep.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnajikx.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gciixpwj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkodate.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwidgbuk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfaqoq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2smixnobt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcxdge.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhodfdrv.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkacuvo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zlctczeq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpaozoi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoapdrz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqappcxg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzklhkr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lljdpbdk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yytgldlu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhwkxod.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2acvoksgz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2viqselel.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcombmvg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxomhemn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmellhxq.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2fddrbnto.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagprhs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2usiifrae.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmtkgnd.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2dckneuke.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjpifwz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zasijcbe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnbumhi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snuxyqcj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcstzez.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltonugz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzofczxp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2faxxjnjc.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2baklaqsv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaymvbe.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpskhgo.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uziqwpfy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvivdkd.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fneoueac.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hctatipj.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2youlgbgr.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cscdenqy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cbapmkiq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hunuynvu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhujzxqp.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2umficdnb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoxpzkx.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwnfddx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsursshn.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2kbithuly.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmxiqlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjugtyq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkazflo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsiemhd.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrwexqn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjvfsfs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryamtlz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akeedrrd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyjdkas.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdixzltf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcrvslo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iebffpkj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhkuqmm.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjqfow.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2reivxelm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkqdpke.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fppnfaum.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2behgwiku.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2axjdhiio.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqkkkcx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsbqkid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcieqihc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sopcpyva.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaisvag.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aingaovk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfrmshp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kruclgjq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwurteuq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoeiecz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhthotuy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubqajm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unchpmjd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjchqq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hozzxtxq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iumvdpco.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjewnfo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbeghag.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzammda.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgxqhz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lexykhpe.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcaaduu.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoqsxce.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukprosmc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2etwhysbt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzthqlzf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2foradord.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zscbdcyz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxmslir.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwfghoi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxmhhrh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2szwhfzml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2upckkiys.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnahgryl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwyajsz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sasspqaa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipyozun.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryddlvdc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2llromkfy.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2itnmuywo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgoejdc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiwiphz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmiwrxp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmucbrs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mojjsnsh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2esxbqsze.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqqfvna.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqmekjn.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlxahsu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tlesxkka.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaspanmh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchwhnzh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavimmpz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjkaiqm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iovewsno.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2talcomdy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsoklfj.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2akgzevaf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2monduqtp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqluegq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2obbrsuil.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dohrmczf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjuuavf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyrrtho.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzdhoee.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqbsojy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aouvxcnf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaxvunk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjvlpzp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eclmlgzy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2apityyjd.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gcewtgiz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxlvpkn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2frtqtood.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iclwcbuz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2soivuelx.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoropfn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvecqftt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuhwkai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdspdod.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqjotpl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2byqypiga.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cngmjulm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzbeaft.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eypkfxbh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bowohjjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkhuioz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gupxhltz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fninvubx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2faafghwj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2afxoeywo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzokars.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gptifogg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ruezztqg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2apfealdj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbotggz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymniuroo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phkvkuqb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjryafx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2voujcvqi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuuomtb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fguzcwxc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmzqygk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hffwonve.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsqbohm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sayjbnnz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmaqldc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwmepew.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2noadocyu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2twqjjzsk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpsidnn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbnvpzv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrbfsko.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wphfdmyg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsvepho.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhvicll.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyxtium.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oemxhzak.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2eobsdrgi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvzieqk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpojezz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnossz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxeshwz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2medgjznn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eskccncm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtuxtzh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxfksef.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulccav.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkgciiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmfgppk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpmualq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvwtstp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdftlhoq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fctewnjn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgaigwl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuobsms.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkzfojp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmoawpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxaudei.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbapilpr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvbqdxm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzqmisq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2reaisfpz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkxvgt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxegpnq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqtoihq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdduqvo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmezrcq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzatgcst.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2atnblydx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ududxgyy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtlapka.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdnmvpf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxqkgyn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihayxwd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiowgpy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteajowc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizgemux.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqjhvlf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jipzpmmw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxphcazw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnspyran.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrugtutr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqleext.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpwwggv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjugfan.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnrriqw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmpkxvg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nobwychh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2igakzrbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsxdjhc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fllncyaq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kazrbinj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqatmza.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hksbrghl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxvasss.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvbrmyk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwexqyd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrovjrlj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtmfzfh.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzlzama.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dogbyszj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2blbxdgkv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzezruze.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyaobbu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2edfbrojt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uyczyltz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphgwkk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eudwdpdt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbxvmov.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuktbudj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxfqobe.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lssieiwg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsgeits.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fahbfrrf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2foheqvid.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvsusuj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiudrifc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjpkfnl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdfcgih.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfdmmfb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2shlwqudw.html


<!-- 参考信息 -->