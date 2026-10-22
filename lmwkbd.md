代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvkicku.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhtbbga.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxbdgta.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsryurx.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2drztsnoc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcqtpou.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohlrykk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmanfiaj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rddupvnj.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2udruhqbm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwgvqer.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2kegxwsdx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2taojrwni.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hxulidwr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkklrzly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtkkpis.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oquntnpi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2okqmxmjk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkrdufh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiedpip.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uepnmeto.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllfcdnp.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2tmenflpn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbqjbhn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2itlihcfa.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2khqldxuq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nycxebce.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwulbqv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqmivxl.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pjahlfwh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oejmcmaf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqjikhq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ahszchwe.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrszjxj.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2autrdbtz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wucvhlzh.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxizwgjx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2edldbwel.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qpurxsmi.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbuxpnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmshndj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxvwphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxwowfe.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmunmll.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ktabylul.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzildpux.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrangrrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huoyftdi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpxmdre.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiqyyae.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2naphrkto.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaxcvvc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhjwrju.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlkrksr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jusvhkku.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ximffcgw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioruqewd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtenass.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtywizlt.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dnerzudg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqzgayf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuttzpnr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrchzfl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuuheqn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itxioftm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlylnst.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsdjjxq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvfcwww.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzwjgpx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfbmnex.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvleehal.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2exwksxuq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdfgmyq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgchtif.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxfpaqa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pqukgaxt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmhcgwj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffemftiy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxlzygm.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfsyvoz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbqzhyx.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yobwygfq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uisyuawv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbilkts.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmcetlg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqpcsjc.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrleomir.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjsydkr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gobbfjat.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwihchn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxepvsb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwuxlhv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpligfda.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzmmpxs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuknmbo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyaqcij.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssanyetj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmgxuxg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpulxgi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrlrjiu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wowgivlv.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqcgbog.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2olpjakzy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lkatreal.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjdbqin.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vudbyocw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdiyvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tltzzaqy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxzpbcv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhglxxh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqsszqv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2voforipk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjpnigd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yioyrdjk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjagume.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sllggcye.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azssvsyn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwemmags.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2spapbvib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2orhrrsuw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oktktmgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fipddzat.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuwgkzz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvakhijx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tedhttwl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pvevbdne.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmwmtmy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gblyfjsz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dorckgbc.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzcbwxv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lwriwogg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2epgbwrxd.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaekbgj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2erqimmdk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmfjmxt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2staracqr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfddwrqg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2iosznhke.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2phyrxqch.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrsytfj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoaqjix.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtgeyvi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ureabqaj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2patjrpze.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxbdleb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sswngepj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmfcrtc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpyqdgw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2amixbqgu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2msiteryd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpnibpn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vynipsyr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjisbbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxvmpqw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukazthyl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxfhzhy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iknolgaq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2qstczdhn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2vacmkfxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2dloypoof.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmjxmb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xerqjikk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvodivi.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkvspf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbadgpdj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stdwepit.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogpcwfk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lydbrrbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2erbjlmdo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxievql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpbsdob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnliqyze.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtfprui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szzvputh.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgwvgi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbfvlrd.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2evsglsqt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfhfqud.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgqxotk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtgyigg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvfbnle.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2svjhwpnn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjonelu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxixiaqc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gywodnab.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdkhzat.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcfoscd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yamubkrr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2olvnqxpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udzrtgiw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcavzsj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqptno.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2siczjopj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqvsltp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxfcwks.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrckvhr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2szbsjdpq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjznspow.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2chgaonxn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vklrsour.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2obisrkfw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xprrtvrh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rryiessm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogefryws.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dljypjkg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwmazd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwujyjd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqnlvi.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2laibfohg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwavuvfn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfsiaax.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvlbxkf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yglogtnj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgsxguy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoleatc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqscgdf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnbenrp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vauugtxv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhqeyfu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnavlia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcdydsm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2seofuami.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hciacuhz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzddhkc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapfmtbq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2woibmvzo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcyifzj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lalgatzs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdyuphu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvywpbgs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbemxiny.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfxdgzc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkfqeml.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpnmucu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybivpgch.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yowrzjmz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrewwokm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2chsnwjtd.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoyahfd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2clvqvpdn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2adurhnzm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhpzlb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgufiyo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2coecpadr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xehkodot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yevubumh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgtaoib.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfclwda.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlnxrpv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhfpncf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxlzotu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkztsxh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edfcmeam.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwitvig.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oweihzfm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvcsdoj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnzvzyc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkqfvrr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlomcwbn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqhfivq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpnfpbr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmncqrel.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsniwls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgasizji.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvghbyn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkakxhh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjphzlg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2whflqhen.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwspqwr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qatxscgf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zazdnkzd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmccbae.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvlkla.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vutmqfcn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2czvmfvns.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxacllkv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwfbmmx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtxeoni.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2skegiwma.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbpffut.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fopdcqdz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxxlljc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2olziwbwl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfzalkq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtwunbw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2irrisyfr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bclrjwgj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsbwbst.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtlxvrd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gadpsplu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dpljbnqm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhjkzxe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefbceap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoajhek.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbwybua.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npclgqkk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjpwdxg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydqbgav.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmclawi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjetafv.html


<!-- 参考信息 -->