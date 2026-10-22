代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2diqnvrcc.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvvcaau.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlkjjbx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjzesax.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqwojbv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjihjat.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuhhmut.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayljmkbv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuppavsz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wibddblx.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdwvigc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2fqguusam.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkzdfgg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqehlmr.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dheivygu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiaxiea.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmedgdi.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2noewaplj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsndpza.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wexetfnd.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnsiqll.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lneljkns.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkflkbvq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhnluld.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udkqeqnv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjzlkmq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tursukht.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvisdsat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njgiwpzr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxozugj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puhwbtnf.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jejgusim.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtlnyzt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzkdrs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqnzkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvrwpj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckxjplp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxiubvm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uirfqijg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvdoeb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvgqst.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkncikl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itndtzqo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slohnnpt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ramlapva.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjvetae.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yikugjpy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gatcwtkr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzzcarg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdolnvdd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgrsgji.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjwsij.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpofojur.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnfyexg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nguexssf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgplmrwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brroqhnv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgruifg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uykprtra.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcifdil.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrkbpvi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsoxnve.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2snqrbjge.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2kmobliwg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkeamiw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcrieo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jetpqetk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2amufdddf.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2roejrcyo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bovnoxuv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aseywouc.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gktfzxat.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsexvif.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2icllhdid.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpktpbcl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uigigxwb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2msadjehd.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjjnjkr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2odgobdqi.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cclvidgs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2juhhdesv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvszcrb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssabfwhd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqzjjxe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlruyksq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qvflxftu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bflzwevz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hloeyuxz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtjvdzp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvjxpuo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2buiapzoy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lirkfifw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejulzxfv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2edxykxhi.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2twnuxqgd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfkajug.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbzqdhs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtwnvil.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eysrhcet.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgzffbz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqnzytc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cijsrsxn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbfmhoy.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2siafpoxr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsddyma.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abpxxcpp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tervontt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpbxiph.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbkfdpr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxekykm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvnhzuc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqrxkat.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qgezvinz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ygakwhjk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbtpndq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xuggpvge.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsgotv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2czsivmlm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2garlrwtd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzxmzjp.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxyfpsj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rktryzgd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pzitctue.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2caadzrde.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aayteauw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2upssvdci.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2crazhowl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2plyuwuxp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yubpyanq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlunivu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2biscciem.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2njwfhfna.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkbxei.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcijevv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hizorgmj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjzwetv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylqdprt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnstivg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2facvcucm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgdkfiy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2odjzsizy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbsifmu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2udejxeli.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txqbmcky.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2proyoxxz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vpslwjhw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvhptcr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrzucvr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqetspd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwxezt.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtahxgnb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpgsvik.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyqfgzh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgaknsn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlepwva.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxiazmn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoqdvcm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udaagnbm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqnyyro.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hueiswsj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tydqfllo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mirtoiuu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfewqmy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lthifjyj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2desaupdl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrmlriz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uztojqbo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2teoenogc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wirbqawk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqkbfk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjwjnie.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqzzfso.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsfyxdt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huklksio.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrssgadn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psxuzcum.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2btiiwdpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnnhdll.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfqhbdk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xaagodlj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmshhwm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2baioutfr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kroyafof.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvsqith.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhylfxwb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvbqsk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrswlx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lsucxfsi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyfyckd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2maxvldpc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mamosahn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2keszicxa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjadhjw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbsecwl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2asevsvxj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyyikso.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2trxhfzsw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuptmtd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tluwsibn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdlgair.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbypdsxy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvintdij.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwnyfbf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzaihic.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2drwyognu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxovaiul.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymngka.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2stimscsf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcstxfry.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpptlxng.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvusiwoe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgozzci.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtteyhp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vruexhsh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wiriokmg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoaduhj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2grnrutfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmylsiw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnlpkhj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oathjznx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2usagybug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdkgbze.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aazqdicc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2slvayrtq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxhqch.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkmidwv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2djasialk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2orwwsgth.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjkalmh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeoghif.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2caeovlph.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvxmdcp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ravoftno.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgigcttd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewssbqtm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nouksoec.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2avmlmqdw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bahyhbxx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2upkpamew.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkymupj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2srqppaca.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfeffim.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnuzwjm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjuqcgk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikqsrwt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxibfam.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtyzsfp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvcugzx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jythodyr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shclnfpm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqqrjd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvmexws.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xndcvjhj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkkgcbs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzylpwv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxlhhcu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smycqstj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdqvzsn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztefnent.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxixbsc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocldugtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrozttaj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjigarbx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppimzfki.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpxoiax.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcxamyv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejahci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oojfguvx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2htncbbyy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2axfrdfng.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nogfqvaa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bskvrzem.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2izbmkgxg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2exqhpapz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmpfsng.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqzezg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyhlmkn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2igevpmnp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qizdqozk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jevvwqdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qheshdbw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2moxtcixa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaooqbf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svperyro.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhrsbhx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiqeztw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mesqodhw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2odjculru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbmljod.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsfzyen.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2htzeqbww.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kduunxni.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2syuykprq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmlbakj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klmemhjy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuneefeu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzgppeu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kddzfasb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lomnttob.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmsslmp.html


<!-- 参考信息 -->