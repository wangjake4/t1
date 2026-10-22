代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpwqzxu.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuacrydq.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxsaigd.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iocxodra.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rawvtwrk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhgxjzt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olbvkcia.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpkkdcg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2cicdbpse.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnomvrsm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2afydsdoe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnmvgwt.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbcfyfg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjozloez.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyrjmhe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2haamycya.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2mitescdr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2luzbmthf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmqyunk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arpsfwww.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srnxpwim.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjxpkwd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijynplad.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzubfab.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxclvlm.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vydfzhrk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjnociz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtercsy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrhcykd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2uchgjoqe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbwrslt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwezexv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndagpidp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgeapcx.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2temelrig.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgqbxs.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrgvgql.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyexwdw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fngdzamn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlbxypm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2usonlnjm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwegiqm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdomjvry.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjfugu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2behgvxpt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwympte.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2esxtklnn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwtagra.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxqkoww.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdseall.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2htggxvqb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2duamflun.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvwhayh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsdjqcu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwytbej.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjoeoy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrztked.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjpjrvi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmqldsl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2jngxumbi.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsxvsti.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2cmojtvcg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2voalzjtp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhswirj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwuxhoe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuvjbfr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whwtieme.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdudriug.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhxxqhp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nssiaabi.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuifltt.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2oojzccxa.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxvkokq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvseuni.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgsmxdy.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2epvneply.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzleflz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfxmsqn.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuhzfwz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2usbqdcau.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2uragyozw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgxpofv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2srcbrsfp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejncuwve.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwjklf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2geplzeda.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpowymn.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsqadpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvsqnrz.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmmmpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcucwvq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpipxerb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmzrxez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ettwhbhb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwrlypg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2depokxkt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2putckjst.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2voironfm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djyncnso.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqsgsbi.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvsxwap.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2oosncbym.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uytxkimx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2komhgzag.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vejtclng.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nseltddu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoihrmq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2troorjht.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2evmfiohs.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wagcxukz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatowzva.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvarhakp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsdozrb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2niofckvw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moitnttf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiyzxhj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvyfhps.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2pakpolxb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eycjnkfa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxozprx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmipttlj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptljuoow.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbdyyxa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rokntalr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoojyep.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfkufis.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjufsob.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbphryn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayondyde.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uktemesw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2totztdye.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpfaukj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkddgtf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uettgddl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtwfnrx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkvquku.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsozacx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hskcybgy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbzomxr.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtsvrqs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzfwwsl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2butqgaao.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2feutasda.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlkqsep.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2byjcdene.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwctjssp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwfjnmb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zalltsjl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2obvpijxe.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxxjcff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtbtql.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2srhnhwpe.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxnzxyw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjjxygp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbnsmuv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvptytb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphzbpfp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojfjjan.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnkutez.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dsamxyoo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhepsdmn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnfjxpa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdnmulb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfontccr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqpqjin.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyfanel.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2iepblnxh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rugwhnqy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbtjpmi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjelcye.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrqqgmr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrihabhh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ovabcftn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hoosaozb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqmqhgp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydgtra.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kufkclgi.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aszhddun.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2baknyzjr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaoppiz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tclynypv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ughkyzvq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvngrqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2svmxlbhn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tythqzes.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrazpvz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuygpffa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiexioi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnkaolv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2haulfstf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuumath.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgihmgc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2flewmons.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbuzgtj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2svufitmu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mnclappf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfveavei.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2asgkddof.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oscbyiew.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vevufqtg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtizxaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpdkgms.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyttrkf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdizafv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nunwuryo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvjflks.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kulujimd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwditvvg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bffcbgov.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fockrzyv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdkgqay.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxoygyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpfcrcn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqcdhpj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehukmhn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsflury.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fotjomug.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owppjhfs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2pssgstqy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfarcpm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzvjoxm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2linhbsvw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2innzggmj.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhmupik.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxhvsvs.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxgdyit.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaahybw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gzavieof.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sljbzdls.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2otgaygqk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbpyehm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvxkvbv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzcuuxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2osenrnmf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtadhjlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udcgvpei.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzzhza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvzndi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnvfaej.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgiockx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyhxldq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otwouddn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqutelve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2woqfzdgn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2btjbthvk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgtvpjy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvcqqcd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bazikhit.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmvevey.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhqjjh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhywcsah.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpyovxl.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnarhcmr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxdvjur.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2htlvdkpm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okfzlkya.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2arhsrxpm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcfnipw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vptybzec.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwovsny.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eywrfzgr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwmvlc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xojhfmuu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznbttyv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdrmtor.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvcugpi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ialfvxah.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlvtmxi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwvjdnm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qajdedmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2omilamsm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvixwzt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqicyfov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phdopmch.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpfgiqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qksenrux.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2okojmcrt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnklsqcu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zewnyohw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2habwogcb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxrjfvh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2havpbvcg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjgwpxu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqswbrl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhslylxi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyddeiw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzygnwi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrktkyh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxmfcbn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fczsautb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ofloqbcx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvybseh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kphbqklu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaybbxg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgwhwti.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2toehccdg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjpocns.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkqtvdl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqmthnf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hoefxeew.html


<!-- 参考信息 -->