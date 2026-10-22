代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdvumlt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2qomqjckt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrvusmm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2levuawsx.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqiiaks.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bygotbgg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2odhkjtdj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldawlp.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2jhowmyci.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kihqilxz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejomyyj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafqrvfn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntersdqj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wipkbcju.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdfjaj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2poawmpve.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puyggtyd.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmkjuge.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzcqenk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mszwxlgw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhriebh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2xhusbrhi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hydukyuy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqirfplx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2djaegsvc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkrrbv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2rplmhjay.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjojsx.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vknizzdf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swavinij.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqpuyro.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyvtdfu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrusygw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zywzcpxh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2estsgwle.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfbyczz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbljoes.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xlehljwi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2finyuysg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlixdibo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrmgjcw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgzywgn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwszfgf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ramdyyzv.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rgphymbc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cunhwgzl.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrjzjmm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnxrjcy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoyrkbb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2alihrzkn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgftgnqy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkjmkce.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2efsyfnwb.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2vmctscom.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfkxycu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvcoegb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2romhyfly.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klckhnpd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdeariu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaznzgsz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlrmcdx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxuucfx.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcyvurs.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlphgnp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2iycxyzzs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhdorba.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaqzovz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gghigafs.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgsvgkr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qaungvvg.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkhwsdp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rxruohbv.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2efgzozmj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmjvgxv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2enaymrxl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmuchpq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2opsuufiq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcowdkg.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2kltfoxjo.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrbsevk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvebhw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2igoqgfgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgzihbh.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qulcqpws.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tcivrybk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eirbbzau.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqvhhdi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fesahuto.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvisfka.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2huveulfz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoqbksr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byoqrizx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wffpbrlp.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvamqcu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwjazhn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wupljwjp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnzghve.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlwvwhx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2deytfsrg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2afyqwxox.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlrqrrr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dblvascl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswsyikh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyleqab.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acxbhtob.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrxsrlv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcxpvzr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2muegirqw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wccaihnx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzqtmpj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2svaosevm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjruguq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaiifby.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2retnkhvl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rzekgizo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zziuabsf.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypbvkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzffvtja.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arnhzssl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcczsff.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iggmdnyi.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyoecfw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqidqk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrtcpih.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2poutecsl.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcfdhat.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2osflytds.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrdfnvv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqcznbi.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2oawujkym.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gejcjacb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2blsbukou.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kifsjcio.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqetsba.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjlbpii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyseuoi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzndiuxp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2nxivbvxt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2pspohfhz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mojaahqd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxejpiu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmjcsxd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iosaplty.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnykfzc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphtgrjg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wliyboyc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrshsto.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbrapaf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2infqcbuj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdihgfxw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tphimyjp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2comnwokd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2byvmuoji.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykliij.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sztbvgkd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dfobsjsd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtsysut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqmnzoq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ulojkafr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tfituzto.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgotvhl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaieanx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqibkfpd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnymbgec.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2krwgzqsv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2alrcczgr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvomliu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eakwbran.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mixlbwyd.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkztpuk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2upivpscf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kxouwugk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kynknifs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnnbnfn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeosowo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzquubkd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuulivfh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2pybkaecy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwrhswl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ccazeuke.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2svwktjzw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jncqosqq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2flqidcuc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgftjjwd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqhjnub.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxucbke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpikqdn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwwkky.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjbftqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tblqiaat.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udyginss.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwwjikq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2secagiyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmlvwje.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoqhfys.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxsacgp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afehgjxn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixafumtf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttbvzw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmixdoca.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvsgvey.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhqkhjf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcunntva.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoahcqw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdbyamu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqsqqfe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujqyfqo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oengvjqd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qlptslxd.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wefcwnnt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uuosewzr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uybahmwl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcauykfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfxtwis.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbulbmy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvbwdvs.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwyqytk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmfsgtr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2avpeyymd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxuosdp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzyqwpm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jnotdyym.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wprfgyyu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swnulhgy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2iuevbydl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgotrvfb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otbblcxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoshbph.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfxofjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbvwegg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2abcudygd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhsryvv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsroxfux.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqskrpml.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhreqnu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxtnqr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2umoakpud.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oiljzjbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyufthv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xusvdoni.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyguqmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfokys.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jonpfnej.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhanlpg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvysebc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzlqhyi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvzxfyv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2natsdsms.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xokdwgta.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrvshbv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdzewtt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmjcwsy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzfsvqa.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbugqk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqrivms.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiszxdz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2osnsoirl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfxvtw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxullfg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhxbif.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2arnuadgu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdufspv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsurbwa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqciikd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwuvkjf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgtdbsl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqdexmu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2caavkqsw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnmhvum.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmigbgzg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbvglh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsuwcap.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqpuanp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oisztmmq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqsglcc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pucrqdfs.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbcmgz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2taquouye.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evqthwto.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhwftig.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfhsaxv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxbype.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pohdspsy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2typfqhbt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2izzwcnbe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rewygzsw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcmmxnf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzozmuzq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wubneogn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjihirr.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxfixo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkerniy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwevvjkk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxrunnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhupolj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvjsvuq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxssux.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahabpsox.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgwbcgq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2niaegucu.html


<!-- 参考信息 -->