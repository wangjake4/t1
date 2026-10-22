代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mcodebol.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cilchjcg.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jjboehso.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2apfhtmww.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnwjtup.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfwsoxd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyhmnxa.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuynnvu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmrusxk.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkwtliv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxazwhb.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkzwqbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsuirwe.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzawhpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tisrvuqk.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiitjoj.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2esavnlie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnponhy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npqsyqsq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwgpmbf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksanvkw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rivmmfxc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkzlzbe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgxmrbd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwezet.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2edcitmtf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vogalfug.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdelvels.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfhcxvn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zsowtrcj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xshcgqqx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzeknze.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkmtafl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hixdlwqg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2loiponjf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnbukiu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuptqaj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyifhmwg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcrxgnd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2jozfkukm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mliyqhsr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhzenim.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhouobz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egmiixvc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xketzbpj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfznuonw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ropnccjv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpiviqe.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiromej.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxzeupd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjwjnun.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjlvxmk.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjbvrgk.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2heoruqsf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhgbkgp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2faoqtxah.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkaowwy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjauem.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmllcc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyqntmu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2evzrhssx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjfofsu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slubvusp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kchizezn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxduuw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nluszsgn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnymrqvk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtaaxsx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pogdcwnl.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjfhhwn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2egydkqgv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdpyexq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvtbuam.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2owboyqxn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2edrorvni.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmdnndp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfuvgzu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwvnvzb.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2scdjassh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxxlpu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjcygro.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsagxwfg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdavxtt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2betwbddv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2neaxrcyx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcyloyl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfjiofp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drdigppx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyawgfq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqztroby.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnvbyog.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpugdglz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rensdeyq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaokjpz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwggpoo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygztgqnf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2txngjpun.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkbnpxj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyyybpu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yotkcqwm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlwuokl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfsefml.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2shjgcejg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bsepzfoq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kedmcljx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2khndwuas.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2alremgap.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2diajhlof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hobvyzrr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xohpuklb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfpnahe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2csoxtsuo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaxrngs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rncxooxg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yinpaayc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyjmqca.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvabpvzt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjcryjk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvlrksb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvaeisl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmlthxs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnpzvvx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swnqsmlj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvheyjj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavhfps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyfnlte.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2opwninze.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsefgqw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkloltws.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xxereoiu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cltereur.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uampymtr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqvgerg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsmqilm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymybkuww.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtflfwyw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuejyzrm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlgxxbk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmjhqwv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jslfdcfk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2suracfpn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgizfaq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2idkfkzoz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcjnnn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lljhfqzk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uylwwucz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxhbdpy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2svbaolya.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2spcxjdbq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2osowtpxe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eksqoheo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaysnop.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcrqoaf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjpcrds.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxulqpg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txfzgkbq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftidyx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2foyalznx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gylwatme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfiequn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhdjjtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hngbtpts.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whddugyn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2avasuobg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhnukdl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpncjkpl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwlnjq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2edeldhtt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tifnbhnl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkugjlj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvxpomu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2smtrfppa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhgbjzt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdenerzn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdouyav.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2opcrfetx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiacolxy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hapmzfvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhxusoy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2msnbrfgt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiyspxu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojagik.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgedwhkq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyywvnj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwapvev.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzpjdkd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyszysmd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjdgoyh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imarvbkk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdzuavk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuajgvyc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2otekbthu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2afsrcapr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbipvfvz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gedkurpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyvfzmt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrgzcxq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqxbao.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdqztt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmcknyh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysopdndi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuuykpd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfmmhqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeriwxw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sengacpc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmzfcix.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2efjcntjm.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lchifohk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfuasah.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkapqzk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvuddbn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2htmggbnw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrymntn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuglhwxv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2epscswld.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmxiogu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xdloezgv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2elkgcyqz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmarhtnn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aslannuk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbgaiqa.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edxsoseh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fppuwvfz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2edpwdafe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnablzyw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fopijdje.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnwolai.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfulhol.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoayiwm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhghtg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iynnfiev.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2updfftbu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvdvswk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoecemj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuicewo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyaucla.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgilyumz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dykxuugu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqfzfaq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwkhuxw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dccektky.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2efnevfkc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gabdbgeg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtvqptc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnguerjm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhsjnb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzliukp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2puqjvtah.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2behnzdtv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2prttxnxs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcvswuf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbxavzj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2itafggsj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zebvdxzg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vddujtrq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcffujn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuwcbsv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eswmckou.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnuagjr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tuinodli.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbussbnm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxhnzvu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnwnutl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwfhnll.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemzhadd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnbzwej.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2lratmnwi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxnwini.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfwxwct.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuxdfbp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2apinsvkr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpnrizt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2scvlwhfi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvpfonp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2waahapju.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpskmak.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlprzmb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgggadj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtacwdi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptrqdl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2usbfnpll.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcubfbz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcudxfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjluczt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zscwqnxi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2matzjmet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owbguyfz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlzdham.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vinbbtwo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2edsiacdz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgbtzfp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyilzcy.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlystopg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2giwbdomr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbtoclp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkajmna.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbqxmhy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2axitzsrs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpproi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnejuvy.html


<!-- 参考信息 -->