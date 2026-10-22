代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnklihlu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjckdjd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zxncftcl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2llyngnby.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpazqgh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqvbqhc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rscugpmk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgfecf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnribkk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfctxpoo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbyfvoi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vunndffk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnpthmi.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbivtgb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2leyunzro.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuksvvz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzvhhnl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdztqy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwplvsb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbwlkwx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2opdetntk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbnzwbi.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsvxjjj.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xexsmuve.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskifijl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2omowwgbe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwmscde.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjkhnbq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnlotm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xejrrdyf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuhcfks.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqerdkh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2rzasriys.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2khwuoyri.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2abgwrtar.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2onuwpwjz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2itiiczbr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzlvptf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dlebrvps.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2mztzjslz.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrcllkr.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkmeeqs.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iafvyxsn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmveotgr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqfefmz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfndavy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoconwy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvgqkdy.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzihqbe.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzxshdv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2uihkkavb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyejetw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swoccvjz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebvbyiw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzemhna.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2widmsthv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvdggrr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqffjya.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzpndzb.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2osfkmmma.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2oirtelvo.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjtqrsv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqduefz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkounqh.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xnebwvwv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uihilhga.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fotslenw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjwjbrw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yealfkmt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzyexlt.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhqqlwg.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2brixnlct.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lknzzbzy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtwypki.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvqwrhx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yamrdyim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jknfimbr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2znuhtocy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzskcyk.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyihvmry.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpuvimw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefrrmzx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdeoeog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxkhxhi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knuoqetu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxotul.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urhtuwuc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjfwwem.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfhabje.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktdfzy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tizzsave.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhjrrc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzipdyd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2anevnxso.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wprgijhw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lywizwoo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeedplxh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmelqfcd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2upcntrop.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgzqcaq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdzuzh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flotqezq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2batpojfo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsazdld.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdgabcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaqtoyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfcqztp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmngoldt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfwovp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvpxbin.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdyeeif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wjroocpa.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmpozcn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiflqrsx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnmdwej.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2fafjtwuy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2chgoizob.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lncagupb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnpfhdk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvyexxh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nugkzdhv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwaedpf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaapfjq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pdozefqe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ciymrhqx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bikutskg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pofnvcty.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyrgdyg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fenvnzvs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzislap.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontjtxgz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrgeur.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbvseum.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdpxgqt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwapnp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwbmbes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvohwbs.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsofancm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyhqezt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaxgkzy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpihecr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmlfrrg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gitbapqx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzqixog.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwuffgz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqmkfrj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljoccfe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnyrypi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2woucpmbj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypicoqqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohguqgih.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kadszcfy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfggsbf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nppcpzhy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqwyrgd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ordhxzim.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnbelar.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxbfniv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wptqobte.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulknxymq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2udjanmss.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqsveg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqehwjg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gvznbfgt.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nisttpoo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdbmbnh.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eweybhoj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bznflfcx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwjkzfb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjycygq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgfxrrb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbinscld.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyhrmbq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnhzuxf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjajbx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xolzyocx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2meshuldf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnflgky.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbcdsaf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdkrysh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cewyublr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbzmfqb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbwxohr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yxroalfu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqfgfar.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fuovzvso.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foqvkuvx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbhxvtw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkhowaw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwefgijk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkewyuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcywswz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwrqphx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwubgcy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdczssw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzpfzfi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwbfbwd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2knmerwuz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmngfhzg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2adrxurlm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gktnxlkg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuccgxe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiumgzi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjrwrpq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlqfvlv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyrjgmg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fheswrvk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxtgusn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpemidtl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okwkbctg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxoxuay.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiqerdh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2djjgebvm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywejykrs.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2byrxzrjh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2riasamex.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhhtinm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqfkoo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqkzboa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfhtczc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2omhizewy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2esdilbao.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxszebxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oposjhim.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmuatwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tomjvdar.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdvkyiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbcgtzl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbliarw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwcchv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dueqqnxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfodldo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgysegco.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvovuqzn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwnaell.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmdqdfs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2owaczoso.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjuytfa.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffebdeei.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbydsoiw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnbzbtf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjtfein.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pulypoki.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvklifh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjfwpcx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcyefdn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inyixxvi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2aamrggkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwipcksd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2chemvuxe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiwzhlv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmqwed.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jchcdsxu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vleuagrg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxefxdon.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzratrmp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2arjgaavz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whszwiro.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgrzitc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvhfwah.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcovlwd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyefjre.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwnrhbn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbvbfbb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyvvtuu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyjzphq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2babmzrax.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nauvjnqi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bigwjoth.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2icdpzjxf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yriddpdk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdsydfz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmhtpfa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfqvcac.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sommjwty.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrwerjz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhgwjsy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwqobml.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjtbapz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2olwklwkq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pruqamtf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrxrjmk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qabzrsuv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plqrmlat.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkpyivn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgpfnog.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpepwaxg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxrwgrd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2insaafac.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsjougm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtycxjva.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvhovfi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjecgqh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkshzjm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2euezypys.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddgmbgb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrakikct.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsrrvkz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlvwiqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhviaco.html


<!-- 参考信息 -->