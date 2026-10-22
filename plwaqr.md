代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2dedzytgb.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjbutio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2skqysfcc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxihurqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lluwdbao.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gealhskz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuhvzkp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cougxlfl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uipynxvn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyibtnsw.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbmqyfl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jzchvcxq.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2babbakbh.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fdowmuui.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpeibdp.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmjepyn.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkwhvej.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdbmlhh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsgdnff.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2txdjunzc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjwszph.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhseeri.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2crgcjafy.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdntdto.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhtsslp.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlnqyal.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2sktojkbg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrvulbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkihhjmw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wryoetyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unguqdcp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxwrqqr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qklhapnn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxldtjgw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eumlvjoy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emwnucbn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfqfptq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mljylnty.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uixnpiku.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxipztgc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mivvdafg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxqbkrn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtftrkac.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhiwmhv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcirrzow.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnbepbg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsmspqw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpoxsup.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbugllll.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkjccsa.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqzwqw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgqwpov.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anqwrldy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axikvyzq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efdevdjo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nncsufhu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fszokdwi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpuboni.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrhtvgg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuilcrv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rldlwxho.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsomgsx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyevrhf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdlrwtm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxzpegp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plinhexz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smoxenoz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkbgcfb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcyyhwc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wozpbkku.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2miyojcyk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzajjvq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwkodjw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfokxre.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kakovjwc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlmavro.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ailqyzkh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwyaphi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnjmyu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2leislvhy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzocrtf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeendvw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxtzhgr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoghgtj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuakdq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2efmtcvtt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwynjcz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnebsorl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswqysuf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2skownckv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzbnybg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2cebwlexj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxlowgp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ispkqmqh.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2svwzwcto.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mfamouqk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2curfqvyz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdntgrp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaafiyyb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2unvifqei.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwskxci.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhsfhnr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boplaofn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2skblkjji.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sadjptah.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrmlfcy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsenrcw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnyovzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiiwnhs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhnoxky.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvdhrbq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsrwvgc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2katwuxps.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmoyshw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkotjmj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2leoxoivn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2annzuvtg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzajfyk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpcczcy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2oriqhnbv.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwlvcem.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqlbdeg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbrbafk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdagsxg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiszgyi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjfwsf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2akvuahgz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2reuoxclb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhkrdvs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebljvly.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjzcdjs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2azgjuqus.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlddzete.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jeutdeyl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eufgfovt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqhovvl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2scnwzgqf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2csaefcpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhxgsjx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhkcptz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2epdivhcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqoowqu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2onoptuda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfkppjo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rypbsrvx.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2aoszsqhi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbxuhdj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2whiyuzcd.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuowalo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jpibhvda.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bibkquwz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bifnwafc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjlnzjw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnktvnzy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqqhefk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fywqoabh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2etloadnf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnzopbk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqmnyx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmxjfmi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upllclkv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhgjopb.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2modhmezv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrdusgt.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tsujnekd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrduduwo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdwzqef.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2npnikbbu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hkymszzg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2trubojeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfpeddx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrgqedm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqkkohy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsfpmvd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szbyaysy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfsgudj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwrnfxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alvtvjki.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2emnidrzg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2aqegymuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2grsqgopf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2akhtmtqh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2eummkimr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2trqrbjcn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopaynr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wugdvsoh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2scrjsbdc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbzztei.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2smvbutxv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdwqqem.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihojewja.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmiufcj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qezztupz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sefvqyij.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tszsdgga.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzxbhkw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jortwxld.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxlvaaa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuejkpx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2phmtgptx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rocdydzh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwmlxey.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2susognqo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtegwoi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2atiwxkoe.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2grxipaqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2prfqlyep.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfltcve.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgjibap.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkenqid.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpwfyuy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuzyyvj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfminsme.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgpjefu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjtdoqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwegose.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggsggox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzylcidr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmysuvqp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgqmmlm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qowkvwnx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fspypvnl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvulmldz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2snflhnkq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmbtnrl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiwiwky.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2syasfhuy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zeutpbca.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysenyers.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2grkvgbbk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2otgjvhez.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudawco.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqcsxrj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvluseba.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzfkju.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwrkfkc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfoxpwf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2utrtxrfh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwudlnph.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oybqckpx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwksalvs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2syyzksaq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuaqopy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsbcdwd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmnesnu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uhputixg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oficitbx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tolspzyt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2acsydkrl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xowydnmp.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsvvdrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2umvdmuup.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drrncxhp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmzssil.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwuqhgf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2irjfrzkl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ramjakkj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qblxqgsp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwqmgoa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2usjkjcan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtsewul.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcnmhac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlsytiu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbotfiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfusud.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdoycno.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2drsrolxx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmqbxsq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqyiubq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfrxww.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkpezcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2alpghyne.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyavliun.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ammtkukn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgigzpas.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrqvvup.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjzqfvs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mgldsemk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2curqqjeq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2etdcscoq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ridnjbeg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsgknnk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xytbwcod.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeoilrc.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lglehtoh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlsqdkz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpddzbpl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2boreqmgp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjapsth.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzigpxc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2timccqqd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxvbidh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwgdmlp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcermif.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fecntyvc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzphnfpl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtnfjlc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedpqkdf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhtxsth.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogockyco.html


<!-- 参考信息 -->