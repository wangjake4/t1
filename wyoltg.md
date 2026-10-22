代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2oanpnuqb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuazxqw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvyiasy.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwopngk.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eltnaipp.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvkwaea.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhsgdtl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hugqdinr.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2losilpcc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwyzmre.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxodjyhd.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2itqymdtk.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnnlxh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhaszpe.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2totsxrxw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2clpmsxrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbpmzvp.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwfmti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqywfkhg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klddkcfp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsofccpe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtohzggk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbrcrsb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkeesxd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlkjvbp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tddmvlxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxjhlxz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcacceo.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txkxphbu.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlvdirj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifdxaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daknxfou.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgvscbs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ausvcaat.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tarvpdhr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwsqrdc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sishpytx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbjwvps.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcmhysa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqkmzfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzacipxl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtmblcj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aklntbyh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoumbni.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2weagaxsv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2oroezjvy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nplgtnwu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqaslev.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmjjgrr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icridmay.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vaegcram.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbdagae.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rexjuofc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxchrfe.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfkcmde.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2neaesafe.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvymhrwm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zabiqzay.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aioafjiq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2plxdshht.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqnfkmb.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdquzie.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvtuolp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2paigapmx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jagzfpbn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jqijxdsc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqqswqg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2usfzcgyg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqopkbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hljqzaue.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2phpnuexs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbwcweo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbaglwh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfmerqm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2iftxtrmc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnevgja.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zowewlqt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbtukao.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdgsiba.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkeuwrf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbopcms.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeaasyf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgtcbkx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2iyygmlmb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyekpnag.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkfzujp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skymnpcg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoowgcv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oluqzwku.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsclxmt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskdxmjl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdkhonn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmnonty.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeccbiq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xcknvicx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2shexvval.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtseoteq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfxtale.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uysmrpxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbezxjeh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnilnnl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrrxcav.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2tggrtngx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wqteusqo.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtsadbh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2osojqhub.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lonxeooh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyfkgjt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ttalkpry.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qudksjqr.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqmbrvq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaoxoqu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2otihbuyy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2edjtfzbw.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzmsdak.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwylvzq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2iblynomd.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2urbvehfa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqzrarp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeqrkei.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gasshirx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjebkwvz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkandur.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bcakabux.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvlqscc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzmrrfw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjllvcwu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2minjdqte.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbwymrk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nivcdqpx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyioyyz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzegva.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvspteiw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqojjsh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2iraxvavx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2veumtxxm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebvjhl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrczwpr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvqjhed.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2idkomzdi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kskgfnhd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqhsttj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcepnbb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgguxiu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2joadieyf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2plbjbmxu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2afiwyhdr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyagvoz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htkalloo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aimqrbes.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmowyss.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwmvwg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2aricrwsu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2toayxxxq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhouwij.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtkestl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nwylxhbs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplijtw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zegjqqhs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsfepak.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbhlaii.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhwomfi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwporqab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vietcras.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2modwlywc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpzgbvo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xdurybyd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dloxgtls.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eraulgnt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzhrlhx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmxakim.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2eonisrou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbgkhus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzdjtxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrqkfda.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hajxlmot.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzcyhoc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2olhuabgh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2byukivqk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkczjjq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmbhajb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxplfoms.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpxcquz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkhgvyq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqgjrro.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucftkkbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgosycwz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2liusxkkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiusgeh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkacxjzh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfwufli.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywocvgrr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlpyfvd.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxxjona.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdngzfqr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kszkwdwr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvbdofg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2blkxomoj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hascuzut.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvjnktw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypaimrc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfqtvii.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfsjvpo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ndajhdpv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2evxlnkqs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvdajcr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yatasofi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqbjpaz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavvelw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbsmlpf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxntdse.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwksefn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjycorh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpptecmz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wtonbuyf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjhhklv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnvhtqs.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwewgcuq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bulbzpft.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcrtifd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pfufgbso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdwrcvv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2glczsbwo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtxvlll.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkkybyd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoaqvbn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkeyujh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrifigls.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetjcwc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmfhvji.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoltrll.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazpdnpu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxqzzl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2manrickt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcujofl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfntyaj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcqtiy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrgycsl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhujrfi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftecddtk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiqyawj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2svbkwkjp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqppgky.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsiqecr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ildaeemf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lijmgaof.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlrpcn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2guewgrjr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vartmjda.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyafiwu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2suhfadrw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsontraj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kymifvup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfzjrkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyrlqbb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jreorhwc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lidbwkzr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpigexu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2falldodl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2eubuyccf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2evvlfkbk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vphyguwb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyduhmn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcvlmoi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2obyvqaxu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkfooos.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvuhrve.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2deconslt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoxlycg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonorogc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqvapxc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhggamrt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whsqxtsd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvieheg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiagndzh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2krbwwsvu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkhienl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthglqgb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdixudeo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oktfwbgb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2lflkcgmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vejyysfn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxofokvq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2covutlej.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2elkglmna.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyyoefu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswjhgte.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzplps.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kznflrip.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwynvet.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zozomslv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knshddka.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2imvejeus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdjyfhm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvchqvrm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2snabhhqx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbucynxc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhctcovm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbhfcbm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiiadkm.html


<!-- 参考信息 -->