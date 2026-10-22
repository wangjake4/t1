代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nljqqiql.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqjcqdu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiabbgmu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldupeuvv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xirlghor.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxbqpus.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vwftihva.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rajzeseo.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvaofnd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2alhwtuda.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxxsmdq.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpyvlwy.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2owvyabkb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2glmivhoq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfbwuid.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2urvngpbc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgynjbf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccefvtrv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kggeyjev.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfuzcoz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvjjpcc.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2towzjnno.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuxnxqx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlomyclp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjwvhfk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmftyhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bptccous.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvohxyuu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2maljvefy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joaycxxm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgqbmpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhtofsk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arjahhjj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnskguqe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgbadvv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgqrds.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrnfdve.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2evwxyzzi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opqsbzhg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pctiikfk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkjkngb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuujblu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oposboaa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgmnvga.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuwqvqb.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmzslbr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiduesr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubofskqt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zobhqsaf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2babhxnoq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqpgutr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrehrli.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuucbwe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2yusmhisp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmueenr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsplooz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzadqbyo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbjghdm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzeqkol.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rropckuv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurjunh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudridq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvphilp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2eskxmdaz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vejabgzm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsgutsh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcvtlpi.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bezaokuq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfgmoso.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ktztubrk.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpwwcxt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaaikik.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdxkjme.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhksrw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxazscb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhdwvdw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2flcbcesi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupqfytl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpcsmfy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rewuirhs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2inavisye.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2oiumjcuu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfuwzot.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bceitlai.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeyqvfz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagvvob.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2raojxkca.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jbifuhuy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2otgumwyf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtilaml.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuwamfb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuznzcv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgdzdg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njuvifsn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heenjyzc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfwqawo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyidrxvn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmngjznu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdkvpiv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hefbqmft.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeohkzu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntezwzbs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2okcgfjbk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2figapyvg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohtyykr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlvdxnc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqisue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxmubug.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2okflvvxj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhnwgvv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvxtgmu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tffudxfv.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2thmlsdfq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoebbcd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqrahcz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kylsicou.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dhprriwh.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kisiuvij.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoznwou.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqznqpgl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkoafuf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xthcqppt.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwphnlq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2owyndftr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmcvxxe.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gshhgnav.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2iodzdhky.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnbrvi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dulqlxrs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eivdwlbf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsqasry.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmfjxkq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhakluu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjqdobm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awynmfvl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hdavqsnh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnxoixo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjclfjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxltoci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czryefro.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2audjiprm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2afmragnk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpzzqfs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsekwnhg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzszfjq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxcudyy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwxsss.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhuppxc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbblumhg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmtbsgv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcqlioj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwnckwj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2saemnrtn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecacblad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fnchioxc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefzlqld.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtnndvl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtszfbhf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xomlrtnc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqrumge.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsxubjm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnukxmdr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2shwuduwh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjiydye.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjopivq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdlandt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wcstrzyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrbhtlv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bouxgbwb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2arptsqzr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opfrwyhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuclcadb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xxesnoyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxfdvf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgouezxk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcgsnwc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2paslesty.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjmyefx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpbaeke.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2byjzeufy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxygaoml.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gofqqprw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsuqayb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffqnpa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtrlggi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnzglxr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2siozuudo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oikgjuvs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxrkfkc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2udctawbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrqxbdm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pslvywcz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsstoxi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpptdccx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpukinj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gujasvej.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbnbpj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vohwnldf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2couyckmr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglwxcrj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iisswjfo.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2muxdwxjx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgibzmh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiobbgpd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfvtucz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbgchwb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxxfkhf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lukniwny.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2briyzeuf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxfpjig.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2usjsgvue.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwugxdw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwkveh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2snjqbltu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2idbdkepz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqoywmj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwceons.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlexqmw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwyleju.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pupvuidq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhplmky.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruybdkts.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsvltud.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjolmta.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnzfkee.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkbtbtq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jctweqxh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yccgvhlx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2snqewhpa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2euczxqty.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqxqlvq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdkdbi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikinczvt.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcrsjsc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvehygil.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhmtizp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udmtffgw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdilyhg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bobgeidu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmnpcxo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nluwpyqu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwqpsad.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqrbjpx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuexxxxe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfdlqof.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiyybmc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjkzqsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxfdkn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfafxqcp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqgfux.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uarbkcky.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwwuscy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdvgvlb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2amfeofup.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gewbckca.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhozhsp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqcforz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tacibbsq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqylczew.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlszjnw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2igiwfywv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvjsqhz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eodecsvn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzbxgcw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabgkqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwjvwgh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvykxzwi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqalisr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvjqwlr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lennkmjt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyrzets.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ncerhjkx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2arxxfrgb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ttltjewy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ijypmycp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjpqzih.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2beerlwaz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnovjxjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tynuomaa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtoymsf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsvdyyv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklkypm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlanqz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2efulkwfz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vymfheks.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rievwlxo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgohwmb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yobyqxqm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hzscoyrw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ealjzwsa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmoqsdf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qscpgqbh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xolaygkv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqlfhr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxineeu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apyaxltc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhplnom.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgaolde.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvpqmql.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnhwjlz.html


<!-- 参考信息 -->