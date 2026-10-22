代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2szvomuja.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjzcmld.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llhjbdjn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfylnayt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsqthbv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2srimrsuy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qldudxzr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2aexpwmwk.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaoqvzw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2rtceafez.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoomnagf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2emsquixs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufknacsk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiieasga.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewkowzn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbzitbk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvtqqbu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybyrgdq.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuxaphg.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2mowjvtrg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvpgwzv.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdkkzxo.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahutxzdw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfovdmv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjtxoof.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpupkvx.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaizdqm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vchbodtr.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cticizjn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrndkvd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoovfgf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2okicrckd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiapkzy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2guijviyu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrpaitu.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2whjgrbfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvieqztd.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhbyysc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyahqpdb.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njdsoltc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvunckoc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwwroqx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaysrba.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytziaygs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhuikqm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2szziedxa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvrclvu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckuxxdb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnglza.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2teyubhfa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gypppyjh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzssthkh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epgzxbzs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwbazbl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdnnlxb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpvuiph.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wecscgrl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rakecroe.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhydtlop.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqhuzuz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtgruqk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmalmqy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hotmkeyx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2didlwxyf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2joekslpj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbtjmns.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvypxjvw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjsfaec.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alajrrnd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aharnjcj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjfaiwz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpgqgis.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwnibyg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytlrjoi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pisdhyxz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzzrabm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvxbiul.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2clodvzhj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnjuipf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtrpphm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsqtjdk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2glryznle.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iakptkei.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrrlicy.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uvehrxqx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2njibtnlj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbdtstu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2prmkrpih.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2frloabzn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gngkaeof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2puwtsebp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsnkikc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzbjlp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrmmfna.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmulciy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzimhpw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2amldoola.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfeqtv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpppprv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuwbfeb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2sosrqzwg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxchsnw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yshqxpdt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kglzpskh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jybgxswn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coouwdzy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbbkcqz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrytrrh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyhcsak.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfglrwjt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qezuoohv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgohzrx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyyusti.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlzxxpo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoxmaby.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uybroybj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwezxle.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzalkkz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrxntvv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyleauh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqvcjdn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxtsxx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2apdsywje.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lurbqitu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ftznzvoj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nciujcfx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhatxzy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqeochu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lvplfzum.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgkbccj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2uqukbovp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oglltiwj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oolueoap.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyytpqma.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyfroxk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcglbrn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcukobta.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxzlzxg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbdfxol.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2abvqhapt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eerygzcd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2azpbybxn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfgkvri.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlmdkme.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mssqpjqk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gwznvmcz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqtzbys.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2crybuolq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzouaof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdpelvw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwvxooa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwucewvc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaivpml.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuaqppk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2psingusn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetmduyv.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyehoat.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpzicbb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2imbzxwfq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjrkfam.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhinill.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzpgvfp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpnzpvs.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuhcqro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2svhokidu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wadzfqbj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnswvvt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcpunmq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtrcbze.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wstzfeij.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtrsxbp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tkemamri.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ucobbksa.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnteluo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlqlwrr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vswinhel.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavopur.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oeinazoh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdimyio.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2empcjphg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qyamxify.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xriredcq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mahlfjrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqafhets.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zcminrou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wewiulje.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvcoqwe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqcgapv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgenvbmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpixliz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpxegwz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkdonrm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2smgqerud.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqrzmxc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfroxiqc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjhefuz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvxsdtl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyquszl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvwayov.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwghizt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhkddhr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ritdagog.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzkegwg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2spfauxmj.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2avvicsdq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwadkssc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybatahif.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nquolkhz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2socwvols.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2woakidkb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhsbtf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyujjwz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaqwelz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzjwytn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2brdoiwle.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2simqlabt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbwkrsl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfubqrg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfkfrim.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trznbgbt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqgcqft.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uybywhqm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cutsymif.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhjkvh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jysgcwyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxrggsw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrowfn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhymamr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2epbzozfa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gamqoeuv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyonrwb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyiceov.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlwnzvt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmyjemb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljetiyqd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zazlnxla.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wemwhwhj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdqkabh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wszhnfsc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuguwzji.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsvzoct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwjdbnq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqnjdkc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrkrqda.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxyonls.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjnxtck.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kujeufrc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvofddhn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiumyjm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrmkgdk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzofkdzy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmosjyj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcfzeqt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pduvzcux.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqpewqm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxkuzov.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbazraa.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgfokeo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpuwjdt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2znyuqprl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlksvjcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2stfiizqg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2thlieohg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtjncxu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twjcauhv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hujmbthv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xedrtilr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyakhye.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kermphpq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omyjthjc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsalcpy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgktsid.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxceroa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gbybbcad.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyrobuo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtzygqg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbcdzap.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhezqml.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpeobgr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwuryfq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqyujku.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2endjcwht.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrdcdgw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhacild.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2teqvptgx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxzvjui.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2miorhtaj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sehqrvzh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dluhmfnl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmifdxvn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsngdeg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wctrompy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgyjxco.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sszjhwqe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhusarns.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgorytb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaqptke.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaqnbma.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2geucpmra.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvldxjph.html


<!-- 参考信息 -->