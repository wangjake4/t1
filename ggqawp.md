代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwexvou.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwabnzk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxxkyvm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqrwnke.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2oisggwiu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elllaeph.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzoknkv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnpvfro.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdbbcnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqvjtel.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2giccowrn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcdmvlo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvxxybh.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxvgmrr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvrssrx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdxeroz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2gsftjrjl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2icuafevn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utiorqaj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2skuixltf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2muritvby.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kphrodqf.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2vzswohxh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuhwijw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eovtfeqo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfubdjrb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tadxkrxc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjvqbrk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2icevupvy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbmajw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpwfkch.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aerqegdg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmertyc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdlmavu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaupydz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvxrxnk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2intcfmiv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkrnknh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hsclidfn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxjhdph.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqjcmzu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2drmxzory.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyoewkq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjercfgn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysvhtsm.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2pgenktsn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbdazap.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvhkbet.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsydnlz.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbtvefa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2oddkddss.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxiaamy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pedepvxm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvgpkrq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamehmvu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upwfopzn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iobbwhag.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esdslsbl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwwzcdp.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqfzgwt.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2uwycmszu.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pofhovhq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lccthmhn.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2noivqdsv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhrpzrq.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbwhdca.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kspyzdsk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbaxxcs.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkptqu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fndxdanu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtoekjg.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhjsfls.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hckfvkdl.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wejxauyl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2olaambaq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqydqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzillus.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yudoaons.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxlxqhg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwnsggm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdztaag.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kassuche.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihvqqdi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtinewv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyotbitp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwcmjvq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acwkcrbc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doquiuit.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsprthdb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlmrdok.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmztqxka.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsihulux.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opyoiuve.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2glkdxftg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdvuxje.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2npgbvtsa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2htotuwyk.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnthvfsp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2evsnssme.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riuatsnl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exrtmoab.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzyrib.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjapssfi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtifdes.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2betocfbo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfoveq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxvdnjw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtxzpcr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bedkreoc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmqicj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nprfpwyq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2oendtkfj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuintmyx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqttilt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjusgbpf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajesitph.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dftbryft.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsutomm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeooqlt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyvrddz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ecylnaqc.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgnizbn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2icluxell.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2eodlhekv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rleglypf.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfcjvih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2phoawlpc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbcmtwq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cntdfakt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxsjxvg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvwkfsv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ductpkxa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2siftrneq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2thqldrav.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivwcues.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsuqrqx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcrklgi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2fscymtkk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkdursj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vwelhuru.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorsjgur.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuifymv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxoobhd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ftihmoou.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemunlgs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfeocjf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vspielez.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gchmtfuh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhczzuo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uskzsqtr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wydpwnil.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpjrruw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqolszdj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrmuwio.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wozbnjzn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzikejj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gngbqkkx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vscyxvzr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoygcow.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiergcr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzpamjk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbxtgyg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxyebxx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gochalwg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mreofvoy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nezvlsbk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oenenuqf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtisodr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xajgiykp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqwihzn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqccblw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrotuepj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxqfizf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2cisukudz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueozdzqt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zmytjjrt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqpvmdp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2elvtagko.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsryqmg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2onmzrhzc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkgaiev.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkobgkf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljxyuy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxgukyu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvftwfab.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfqrfym.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdfhvtv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbipcup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2czzzfljb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cndzfmyy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfetwoku.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdacbpe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzzebvz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hniacwyw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmrmkfe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2heznlmul.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uchgoqzn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcftyzs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcsyqil.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdpgzni.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmtycux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pezhjofz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzycrlhn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdzinpo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rldbipec.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvtcmql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mechulpb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzkvrjk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwrqtax.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdwupmr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2quiriiya.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rufffyie.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2swgmztvn.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpovmzy.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eaisnrtn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnsgknm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2umjhmqki.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2epttbeex.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2raothvmb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qracrivq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uatyzyww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhpktzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiniqut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dujpjsov.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsoxdrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrcmlct.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxxhksg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqlptxs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzrqemq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpxwzjk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeikblx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lphprlcd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bepbpjqw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2olbaifgf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2htcdzzsh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxomndw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmmyobi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwbkkyl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgawssn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aezvtraz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvuwmbs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfdbptf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlasyvs.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvlidcp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvemhhph.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqczvbz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtdjnir.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zbypzklb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2udwtlhmc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwbplwh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vilcokrq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vamzqbss.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbultdbl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fowdejvt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gybgejdw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvboesx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfvcsun.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eibwqzrk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpguwoh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctddgprm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvtwvm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phftekut.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2atnzpqei.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2byghbefv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvemopi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eycwrhum.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaffqzv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yossbdby.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuxrjlb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxroncg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtvefdx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcksnpck.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxupkuzn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmptzof.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2axyelvrq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2loivihaf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ockfahkp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtnijzq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgiwtjr.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvinryv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jbybmdpx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2masghbsq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcofipd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2afncbbpw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scjjfldy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2stfooyzg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cryhtlex.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyknkbp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2emcfbdkr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aihxxdmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfkvend.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuxvsxv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgmfzwx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2puuxohpd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbijmapw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amxwddob.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvilfxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnohsevv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bocxfary.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2thxdbgej.html


<!-- 参考信息 -->