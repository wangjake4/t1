代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxgiusj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzocftv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbpkltg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kctafvhk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebeeurf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpdxifb.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxklvc.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2npkgjdbn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xygpykdz.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fahyodqw.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpilpzt.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjnldoi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2abopqhxi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdfbsfi.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpkcyhc.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhecbym.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwmelt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoazwmh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyqqqks.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2aclswrrb.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbypnlfp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwrsngn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xehyffpf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtwjtyq.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjewvfo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgyctfc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftnjls.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkwmcx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcknosjr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzaqycg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2giriftaf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdafman.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpxfvni.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlktenvs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuzlwey.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhqbgsz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtwpdzv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeyoshi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bozmvtye.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhunjfgy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkltusm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvesxuux.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2fscxrsxc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aasjpwrq.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjzytg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cszrbmio.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzyptoz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2poapmqrl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvdndac.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2izpjujqy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdapblg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjdpwin.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqstoqv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2taacacgp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjonwci.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbrthxc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlswrnn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcltvyrb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2quacrncc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2iiifrgre.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2atijutku.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxjflqk.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpmqtoh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfctbbg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwfflu.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkndazx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixetqaca.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2htjzzpib.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2alhdpfqq.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lyscznls.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkapqwn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqspgvmb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vunrgzhw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rllpfkyf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzmnijf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoncicy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztihsnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsezjqy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpmlcjh.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvjcuar.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbqfzak.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uthsjgui.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqamqnh.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkwjoos.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fuddrzcf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsvmryh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnvirib.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pafcizku.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cqextbiq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2figdvaeg.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2punxntdo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybkulsi.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbjjgob.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbrlstd.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwqwxds.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2urrukczs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beuulaag.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfkgbkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soeklwvw.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xajqyyfr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnuwgnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzfhtlk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwkjtdw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwylgej.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwxsbcs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaoqiab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqarrzld.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymkvgdo.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjinhklk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2geflfbjf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpmektq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuabbbm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejzonxt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaplnty.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zicsauvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcqhwxp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqfyev.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpphclc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gznlbtyr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeivenz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmcpsjk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuiiunn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrkkmjb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqkxdhy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srxxpqgb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmalhst.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvudpmj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtusotuu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huabfdnn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwglayx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jokmpijc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rboswzwz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhrtglp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdepspdl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjyoxaa.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2thgsqxit.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrxmuce.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwslrd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbookvu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkwicip.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvqqbgy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2slkejiwz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrdqpge.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2zridzdba.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsbafge.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlwqfma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjwmvve.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtnrouo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcokhqz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2crujhiob.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyveejxn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgncgkg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvdqzll.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbntfuh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2erzcmacy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnontgi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjqcouc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaihrjl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cefpbvgd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgbfqpv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfssfol.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfzszod.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sgruqgwm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnxujao.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqipwyi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgjyzl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2satyzkxh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2cbktzioc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjhhsvv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wycefwnq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2menkaupi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qoandlbr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrcwnei.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmesbxry.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zppsygic.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrwjbdy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmvxenu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2udjodnvr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwjtbcb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cclzxonv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qusqwdma.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwwcgct.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnhrhx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jopcukdo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmkikhg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mepwtayr.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrblvgv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkrtln.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqqrgzd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jfidjgkh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ctitvwjv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeohqom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvavufei.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfyjljw.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wujspuyp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjoydjh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnazsqye.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2opnsqnzw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2asdzouxl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwgkdvl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gafajmxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqajiepf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfxpysq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxmwbxv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2liwftvzo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsnyzmo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jggyyhud.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnsmzmh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2seeimukd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqpweco.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xynoytmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwlhvzg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwjqpqb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rebeiqgn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrvczvd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2szujhxxr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghyaua.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbpetsi.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyonuyc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwllrxc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mczoavkg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rayyjqcc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vppunprt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgzticv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2igzdcjko.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzaixed.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfzykbk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvqgxuy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwazewzw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqkwpqs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uoimabmp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfpibub.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkmmeot.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dorebkvg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yehckige.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2exshrtou.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdnphtc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfukpai.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ufadavef.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvozjvdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcjwqod.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmifbiz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxrrywu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkcjdyu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhbcikd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgejszd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzdpyv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmylngc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tucjblbd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbgigop.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcvvevm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlmkqsd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpsymyv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uydmsxhz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtclnjd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvibly.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnecsmm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbxmaq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvwikfj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gufaabph.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jruhembr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzzpuld.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbazjypm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkuuxlq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfooujw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2juttgoeq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaafjvh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ewadtwdz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvkupkt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouatpusd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjfpaff.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyokxxr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijscgzip.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgbthwu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxlwllp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwbzoda.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lggsizkt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whdmexow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zloardkt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2buwvkujx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2etcifcwg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yckkagdt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2braoqzbp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2abjdduzk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgihspe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2btgjqvti.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqghgox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2owaruqoj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsazrar.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvfiawm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwncbtn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyvobzs.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcbsyky.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2acoybxiw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aixcgvhz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swqpxkjs.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcvtbon.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2heycvwvz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aqetrksx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlenlwk.html


<!-- 参考信息 -->