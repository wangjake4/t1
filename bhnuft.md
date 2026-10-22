代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgezwua.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pluxwahq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxrhynr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqpcsvx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsoevzk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfvywkz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhrcqc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2npllxues.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2didqnkut.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvnows.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkmdgvm.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqtneq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tymhjplm.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2brldaqsq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zobcfwwa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwqiwgn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2gppilazy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxjkzsd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zerdyvsq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfprejm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gobamxus.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopcatrn.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2fslsiqni.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdknqxsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdwsgqc.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcqzkbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtwekcj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvdusbw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2slpimskd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdtvsqc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezuhktg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthouqtk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfggnbpr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2garpitqa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvgbaoi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwpjjpr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbamacy.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqngewj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxbkjk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pindfmlg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhxijxk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wzchotzh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ninsnaew.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nbetylvv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zabtymvf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhmpjzh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2njbeahrz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgyeqml.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjatohv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juppxxvw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiadjdzn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlomamff.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzsbkae.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytocqzak.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmibswn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qacqvdfe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiytyzvx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcheqql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vhycmmao.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxnpkyr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqpnmog.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2piwcjyzd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcbvgwn.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdylfliy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgpsigb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmyywnm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aktckjhm.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxalosk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvwlfsx.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvttbfo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wztwpker.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrsnyaz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ohspjllf.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fszrnuos.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshysdra.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tldatzts.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgtuioy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtezktoa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2escoerlp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahunwwfy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2smxjksuu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzdcslr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjtkqea.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hizkjifd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbxvgnk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwndivyp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usifkrun.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2haiecbrz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2sekjzbtz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdztitc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2waxaskpo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuytkpw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzffaurb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdltcfu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfsaqvy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolzynm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqmewtt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edayfxck.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiyanqz.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pcesfpmq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvrbgu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlxhmdu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2foblbywo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ximcgbqr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxagwjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowxvkfs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hempeihb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrykzmc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2caqmqllj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2awmcuhgp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fmryodnm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aagptmkk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltwofv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oejtcfxs.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iucclhws.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxiebu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbitzon.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhgdxsk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2defuoawm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqthqkf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkppicz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvalaxld.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcllerl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpqmkup.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2htwkphse.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppetzhn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gmthdupa.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxlnrcm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xajbizyx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyangau.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqhhgph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2npjdlppb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdowrox.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2crwiwuay.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mokbioqs.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjwprzk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaocfyl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlgblxa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxisyabc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoqbufq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwjogkh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vfikfzmw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bssfbcgx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxidinq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnqzvnu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fyolomrd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qugxpszk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxozrzwp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfupbegw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxklqyt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprarzhc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgzjaui.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2snbojswc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stpaeqcu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhrkqcv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnojueq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdnofrq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfapwub.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxzwuao.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iclnaynw.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tusvkone.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfmrdaw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bovtnsxn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tcovliuh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkjzdss.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqqnmci.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhbtwel.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odhvyszf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdqfppv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwjpiut.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amyixama.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bngprzrj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2evdflwpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnqybye.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrjlhgv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dwebxake.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjwrwtw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudckte.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmbmoxt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaavjq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcswhxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyymspcq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbrjilx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2azdddgya.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyoqncu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2saroginq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kttfvloh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gudnyztq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xifgiegs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrecjdl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvssmfps.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2drxpoaaw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xinpzuau.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxjqlnv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmyelka.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2phfevccm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2blhfzpwn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnivulb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkieoeu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2obigzkuo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2arsplrke.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uroarnxr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2axoqqzpr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izxgnqtn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jctmfxgu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcnhnee.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccojho.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktubugj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2evpnxzfl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgsxztz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmvslx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfracdx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvcpvpe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2icrsesge.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqyojii.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cymzmwji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pxudjfyd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqaqvvy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjupfnkf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoqpqeq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejbfzwi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxvaieg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2enazrplr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjukpni.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zckntdec.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhflxue.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2brdfogal.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnofbfit.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgaqvsc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2isstefhg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gagoblxo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2irblmsgh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nonrlpbo.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vammzpnp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2omwczpgb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmsoqmb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yugdbnmt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bzllplcd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrplxnu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtpoknu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxlmksd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjicrvjs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2arpsvjmf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnadllo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmurvvl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogngnmkz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoowlobd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsrgkqp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxivqrqr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2otdojsvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmtdew.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhebogln.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcyduhr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vpreejxx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lghdbesi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgoudkm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhvistw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvugiis.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmfjwnd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnyscoy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtdfzjo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpellcr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbrktab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoairjf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2titbguob.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpnevwa.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrklmbe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wucznrqt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnhonea.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zunuongv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urdyijkb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2isyeuiym.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhrwfmn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeeifhy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2djznerpg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2stbnmlxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgeziof.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pactmtvl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkaqbwz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnjifyn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkalifmk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2llpbnhty.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjvsmez.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqgppru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dssoncqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhalfmu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyzkjeb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncztvpqa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlibcpr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aolvxxbp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfcmgiw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxztfqi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiggbvx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkxrlik.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzcbebb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfdopic.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oedzejwr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoyriei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpcgqhj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnpzpfd.html


<!-- 参考信息 -->