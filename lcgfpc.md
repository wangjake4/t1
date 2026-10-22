代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyvkikp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkinvtun.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmbclsb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdgsauq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxborbos.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlwhcc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiabmau.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgrmgns.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqixjqt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqmctww.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwqurs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoizvnz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhddsvb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afucwaav.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2yitnrlfi.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zquxooot.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqchnb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffembouv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbmtzaq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbucldqx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfvyoui.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrnlrbn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmwvdwe.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqetqco.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbdjiyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2useleweg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjxaeed.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2joczvvgw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwvsiyb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmeszin.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgqqhks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2halogaac.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xbobnfeg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpovuepg.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esuvmxkt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxjvqhn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2syplbwje.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtbkace.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdoljjx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqvxmnk.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2eltrevet.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagelyl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gofcpicm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbixgvr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlmpafc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2feebnynt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dorfooeb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpuovsa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybffstwz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvoplpd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxdsjod.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgslmys.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmvjxnq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eigetrfk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lstnxdac.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzzzrkd.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hctzkwdx.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqmwvcd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tarfnsze.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcptoix.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqqnuxd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iepdyjli.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdbkryx.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqiieky.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaqxewb.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukubzwqy.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cahsxuwz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2djlnlrml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvitphx.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdgvfie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdusodsp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fclnwalk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqpvtwd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sveldvlg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomttass.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoelsuv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyfkjtm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwawjkdb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbhjlme.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmstginf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tajponel.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ypovvlil.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyitowy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjrsdsg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjklwciq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qspapusp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trxbqlve.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rzokzfnw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnntnnx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkagsazl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscpuuyi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcxuyxx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwflvr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozmuzom.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaeturp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlchxnqf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xedijdui.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbxymdp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzugkpv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukghweg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hepqrlus.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blxfwzvp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfpojdg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2esfpgvjq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxypmadl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrclowi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apzehbvx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhzsujk.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcapokbg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kswizqou.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpjzfw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uocwgwcj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbjjzbi.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeyclsw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nujwhsgx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2cgciocbx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrslclh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2irpjcbhf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdgnpdu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhmthvg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdzzbok.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzqukke.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntdrpod.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfuucjx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgcytdc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wahocgdc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfyamxa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgxprg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vorxfaak.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwwenef.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbowgaup.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2udgmqpnr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzylgvz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbclfsa.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2btzkaits.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrngror.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabsremr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxiqduc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxkvtiz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jycxsgwe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlksvabq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvohutnx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zodjxjlr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwnsnbi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sumuzmal.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruybeqdj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzgavcx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxocictt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucearunh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwennbjc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkhljaf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaguxjd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxfuvu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jcotorgp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pomuseny.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqfwnm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoyxllc.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrocqyq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2llmjujes.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2rfarsakk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvhqhvg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqgofus.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2uwawsrtt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrmcjnq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ystrerbr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtjdlgz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2icayyspo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmaiszk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeaatlo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjakipxq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2arabpkxc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2surhucao.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgefxfk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdloyfwa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjzqxru.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgujrsj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmjffuk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hcllzkpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpblryw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2shiupegh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyskwloi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pohelame.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hykejfnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakklrwj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaxrcii.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nnumaavx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfncjvke.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yopfhqsg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doynzumd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqwnheb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqiesao.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvuodvu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bunvpgea.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apyoymez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2skyjzndg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fibqwsao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsagozkp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxwbdir.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qudyvpeh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgszieew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbibuszm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnrcezx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuqsjma.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiksqbl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2swwrzrcy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbzmknp.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfjsjoo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hujuufak.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2aifetijy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vgavojgx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrzoqbc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqojgab.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqonkot.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxwfooj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpseekbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzsskub.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bujzqotn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfxapej.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyoiwem.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2anltcupo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdjzbkn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbhgmnf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgutdsl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhqousa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2syzvecje.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzcmrda.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jahzypdo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wffoilcx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrailrg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpffgjk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2twtmuksq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcogkjg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnwxrkf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmktugfb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2opytctbp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjcvooq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbpeoy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcrpvjb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmdckyj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bletjbfw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmkrgo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2avhedmwo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtlqxkp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqjlqc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhqssy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnbsnam.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmhijlg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmbrelr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyoliwy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkvlha.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kafkecdw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfsdfgr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkfxoqc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcsulc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrtkohs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qowxzozd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvltxbeu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsqdnqq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whbkjauw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxibnqh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dzembcsr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wzohucqi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcvbmjq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvngpoo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxspffa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcnpvms.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pawtgtxg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ravpevjk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbtnjuh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggwdblq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvkhhln.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kafyqahr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoynnst.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkrqfzm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2csbgjbpu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2henbdkfi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzeingc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhebkdzv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2grncwbww.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxwqsly.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vswugebs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfchwfr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqnjulf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2snojbjvh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opkoufbz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2boqioith.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkicarz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfobtegq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uswnpusp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iehfzgco.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsatshcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcfextb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpkdtfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlbjkja.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcewwko.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2samsyzzq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjqezmw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rucmhklm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2otfewhct.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tknsysjf.html


<!-- 参考信息 -->