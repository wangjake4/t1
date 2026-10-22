代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcgfsxl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdmaigq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxbnnwt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwoppxu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbaccym.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlzjqyz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktgjvbj.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clqgjjzv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2htlefigk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2twwsedai.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymhblxw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtlpchu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2foivzkvt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knarmlvm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oriyylen.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2sudrycdh.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnksflj.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbmjxfo.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbnxwbk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvznuvf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgifzne.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbutkav.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfftizf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsoszfv.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxsiys.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2gickodcp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdktjh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvhqsmd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkanaqve.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyrgzjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdkihsc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakqrgi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bajffufg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhfdqib.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdgvqix.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2raraljiy.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpytbfs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2okgtqrrx.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xevqshfv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdilvkbx.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxixwbh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvxynhx.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mojyjxsh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphheur.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfdwtvr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfjaihb.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fohhxwki.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xekkbioq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bljouwtw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2znjkfkxj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhntpfp.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcrodvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rymipgfz.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjouxzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igqccvzh.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsuhogn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxwiscr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxxtnsg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbbuwoj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhexlegs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjbrkj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmefqyq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzzxzra.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utxuvojr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lidzitlo.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ekomhcpk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywpymjs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvblaph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtxjkan.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gtygxibu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avnuhcdd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eabkwscy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyezjnes.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ounkxdqr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpzohvk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgofpyi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjnhnga.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyobbyym.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwhfvxl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2djromssc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gffemlqo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgwaqsq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoalqit.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeyzwft.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkudrax.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mflvnvwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzbhusk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvvghqd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2slswrngw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxidcugh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwstrchv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnauhsd.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrloqpt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgrsyby.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfckgswy.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rldrlwoe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mclyjrjv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvhzdgq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnizzsji.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2igyhnmou.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpedhhg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ettuxbph.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsmbjgw.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cizivcun.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2whwblllj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2acvqouot.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kugavxgw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2reqnetls.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2drpfwjnz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnlsxhl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnikkze.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdgfqkq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtjjpmi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkzbvoi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjybwt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcxkoej.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcntzww.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2zqedvdcb.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzabhlc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwddefi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hussjrty.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkgyexb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaemqxr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2hybgitiu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiztyvj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaagmgy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcklrze.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yggznxxx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxourtho.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gevawliz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tljrpjdw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwutzol.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkhmqw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjdcekp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2purtxfsj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyagzgn.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzeojju.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbbvrou.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zkouwjpz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cibugfas.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2apnyadmj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhppebn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkuttkx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzgcztn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdvvtf.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rutwzull.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmmsav.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2spusnbfc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kszetpst.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlnksgd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrrnzqo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cmytzxwg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rekolxrw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzjxvdy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kawoqjia.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvjcyzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmftasbr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlsthoa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2efytydna.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuveurf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyjnnvi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sdipwxvv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhvuxba.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfhelkv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2druhxdrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voglbgns.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdxkztq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqytrljt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsodqamj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uumsrhvp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqiypbo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvuvhfw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtroxnxi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hekiawzo.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqfxmet.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewchsdmp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhbiqhc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhgusxg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2efmixpaj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2epojmksu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lutsaoau.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfchtfz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdggtir.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvjoucm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqootpqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeumizc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jvspbpzg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqsbtro.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcamuqs.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqintsg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmwfvca.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lnburhze.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdnrqkb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnpkbql.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkyunii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrtsqjq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkwnhlt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiococm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qckzbvqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wazlsqfh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgxihzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqongcwc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlulrrmb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbipjca.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrzawg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2absfkjbc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zksgvexp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2stknrrsh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuzgcsi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2musslmga.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvadghnk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2szuyqkbp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wueksacv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpzeclx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjnqxup.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxfhnt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikekhngo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzjbfbc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxpygax.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glvpgxho.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjarvkek.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudmcjlp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfllsdys.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2odyftkjj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggayusx.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajljjtzx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgdcmsn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctppshbi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxlsxyv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yekafxyq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2elfrmcso.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzvspq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqonkli.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kckzrmhw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bycggdru.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kspljhst.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvbgpgs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeiolvt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fgicypkt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwosidb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2llnhnqch.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjepvtkk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkndjag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2urjvpwtu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsdwouu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrboexu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqnkzxs.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuzgeyt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgatgkfh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtrmiho.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuxxkzq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sggilmil.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmbypq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqerbfbf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrqdibm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjzvgob.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqzvwmb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2hptkbdgb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tihhwwiz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrlpqgy.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsllhsdk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdafgjo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrgrbg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiabssr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuzjtez.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxwgahl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puhvxeke.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2invjqyjh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdbbaal.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvjeves.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlibqwn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaittyz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnthrkxq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbejmho.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbvyrzb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2expvbqlc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrelemv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzuvdbn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wajhzygq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpolkdl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2buyfqrvu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbukagz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbxpzjq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2pheeobrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2heghgytj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2exmqkera.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiovsmpr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnjbcqc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzixlvj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2syctgmlw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaxfqus.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvptfyx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srkwivoj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpftptx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2saxqosym.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzeuhqo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsbafqo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2itqkospq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2idzlxvbb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2usdyagnj.html


<!-- 参考信息 -->