代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucsufve.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrcavw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pritogrz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrmrwqt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2irfjhdeh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2guccvfgp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceapvqll.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2errehama.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsnqrpw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmzvsvo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmxiqop.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieatsdfj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtunuag.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhesyuuf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2twgayjtv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2fepbuihg.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbitgqv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2gflourpw.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrytbmt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfaivm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcemrrgq.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhlyirr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjepyye.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2drvkyizo.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbdxgj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjhltut.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2uksauraw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimatmry.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvgrzw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnssuzua.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstcuvep.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnfocnl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuzbqho.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abqjdhhe.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2niiwoyqx.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjzuvzf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxgxbqs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bupawnvy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2udebuxfl.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyamlrcy.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlseboi.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqxzhkk.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dmljrlbq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrirgaa.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsgtntw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphhwqxu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqasdpsc.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2axmqatzd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiawpxys.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nekweqfd.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbfkkgv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2soqzqtkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbzxsmg.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xpymizwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhednz.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnsiszf.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjebgfe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duxhzvow.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmjsktx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuviusno.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrrguwq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbbeepo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aniwaspd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvxlqk.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itytusxo.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2eyknoffs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2latvzpwe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwykzvcj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwhghyf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2olqodwjk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evjipnqg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwgwpdq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gthrcbmh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2clzluwpu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2moxylznn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqphqnzl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2almvnjks.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiglkzq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yficpikf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficbidlg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbawhvpp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvherlfu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crnaorih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnnzyxj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkghrg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyvwlnn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdyernq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgtjdus.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdycaia.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcprxecf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuywhvly.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvepljm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2teqhrhvl.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rltfevud.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fonanqro.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfdvxgr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lycjkxeu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwccowjq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpodqeo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2svhjwxgp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdpedzt.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2arvqgutk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2abrqsoqt.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2spoobtos.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjraqau.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhufkobk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2harbtzax.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lukemycp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2devrmyow.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dszbicaf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2piulkwak.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpynxiv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqiulqi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrxpijz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klfncqfl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tazhoarm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2najbzpup.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgabzni.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sanrljko.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2szxzzlrr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpebrba.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxgdfyo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkitxsvi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpfxmct.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2swuayunn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsagmgjw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiulruoa.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcpxhua.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpddoeyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrlbncs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2useghbnn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvtmbyu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nodjceuf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lamzleoq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agccdywj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khohhhop.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2daungokp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2fobhoekp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wbafkxae.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2izoqinav.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxqezsy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gisboksd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlopinc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqrdxsr.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlxbqvq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wcadrqsb.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2eklhygef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqngfcx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxilsvw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhbthfs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhduyfg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fweolcbx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyiwgwy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhdemoq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2azipqrmq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2agmymine.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2maydcmeb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsynage.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxpaztg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yrreypri.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfgzash.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2icywtcsj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xupyfbjb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vuikmoqn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpslxn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuiviui.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2arzhzudm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anleskjr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfzuxgv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfnhfph.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2frpelyxq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lasuqapu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfawqll.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wedgzkca.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxklpnl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bptstjvp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvzwjun.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfsztqq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhvfeco.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjflsvox.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2somebwhf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyecsmj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fhalcbgb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvhqhuc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjgpgsg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjmhpy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxurkpp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwbpccy.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kewdkkoy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbimwke.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cejaoaph.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnqsaac.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2oewkinkn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxkfixz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qetvxqix.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjupmk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qimnindf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsdimty.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crhwqded.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnynifk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xfedxjrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgebbxxs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxzlnte.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgiyorc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2spmxmtsz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiprbmc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2uudbdzdk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbutrcg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkgprbe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlbmqbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqtapjf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2owkialyq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hhramtds.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexbutx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2viamhwoq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmtvudk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbevbjw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcdgzwj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2prufkfds.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzqqkoh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2orbanshv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmcdran.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurwhxwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2alpdihfw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sihlqiqc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzdaoxl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvayyzry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhlvvka.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2piwlbpat.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iydvwqmf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2msykuhvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vltlrzdh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2glcmnlvn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gskldrgl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbaymxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sckizned.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcdwdku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpbfkhs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zkviguvv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oertfufx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlutplja.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mljghzjh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdecibf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mstsegaz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qldyjnzm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2irpcqvxs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdxygih.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjirxva.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfpyzsu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2apmlvbok.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwemxnbl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gslwjucl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrpoqgi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxvyyyf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrafgvt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uesjeezg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfqyld.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2melivhlt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hihcqiuy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhhqxpt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2puhflvun.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pueenztn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkntfkaj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzvibt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsccterq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqionnnc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djqwtmcr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tabavezw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxolrvs.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnozspa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bffdolgg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfogpyp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkggpxj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpeogei.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzlsrfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqticgnx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvacyar.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2emwffehl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2swwjziry.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2caecwgcm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpaevhx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcddlfc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxpimba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2osunmlch.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfyefnx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2koothifv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchguzf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzruojhj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvytogxi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2esawcriv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfiwufo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkhleix.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2euswnbsk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2klgsfhkk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2npemcudr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbjrbz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2coswspqi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofengeun.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrharhx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qngjqyxp.html


<!-- 参考信息 -->