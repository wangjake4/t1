代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvruenc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jidinhhy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcyvufc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vijittqw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuzgvbk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcbqgbv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2tasnlxpm.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzjeeuc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2izjvlpvq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2erhphxwr.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hlztlmxv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbldqal.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2doolhozf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wkofttcf.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtbqkl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfhnmag.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnilgmm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdgbnju.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxssnkqx.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2krckymhf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpghsuw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijujpn.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ybonluhc.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jshbgtmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avxxbqpf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bkafebel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqckyob.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iijwitki.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2itmpfglj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuuvdst.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fptekker.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhyjblm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkokiwzv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jieqyaky.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwirtlqa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvicqtc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuywkdj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gefdymtf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpylgjbi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlefsbfj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfoyehs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhnwrxx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzipmtb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwavcdg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfntbro.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzvlvtn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivroznn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tudjkiuo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zweyhbdl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcjibhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaoqvnq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwvkzcr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbuywjo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkzccmm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phefxbpp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmguzggj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyahcbzb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scyahyxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2npokjmiu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiddxvj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tckhddvl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grzbyywh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgydsdt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpfrvlr.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fburpfaf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqimjhy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtkdkqn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2utnmivcb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdmtrq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xokkktmd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2raplchfb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2fydnenaf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2doxivtcj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxqztre.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2enyjyuwm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwopgjny.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnziyvms.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifhmxga.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mentnrcb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dohbmhtl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wriuhhza.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywqhsp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeclota.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbothohl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasrzvss.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtumbht.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hniyeaau.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjzclxr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrljtmj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdarrdqt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdfzpui.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2veamaqcp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idvbpoyy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxongqoj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjyxtrv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ootayhhs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfdiozq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueavedpb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmppfbtx.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjzofwf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxxywv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmekqmw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrinjed.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dznzzdjx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diandtfa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopwqgwd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inkzpqfx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfjsdeq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmdcdp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyuqstd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2nohhvucp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sprjkwax.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qilshheu.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqeypru.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2apanclhd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsutoif.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpnglbb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpdjqw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhsfeew.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrgbtdw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqijjxbd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxdeika.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsxnnvg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rasfybed.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2afolidxx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbbxrmt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2btaabzdl.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmbirsj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjaxebz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxefnpak.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpdcsko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhdhhz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjwbnkz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2csusgusb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtldfemo.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tasbvscl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvadblze.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gazfjjwj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xciljkra.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlfgcbp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beuovnpb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2efqivvbd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiymyir.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2romltvph.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dythqmqb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnwgbto.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqpaisw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zowgpvre.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqfpxsc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzianizl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmynkapl.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2joiyiybc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2opzwvbdd.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtggej.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ezefxwaj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hciptblz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgktudnl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ramofskq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnsukci.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzyhrbl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2iqktwvvq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwputycm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iupjdwvn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oohykutc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kkurouti.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2emsezvkv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xjksrgri.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nljqdquj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjrkecq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqokqp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqpiqoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtmtepm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhftdyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmfpca.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2actslfsa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2etwfkvfg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zznzxwew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsawvtb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngetgsve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgshxnx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgsdrdy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2djhribio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2idnddonl.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2akxkftki.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cibeuvqo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncauvra.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgypmncm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okbwpluw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhoshpk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvngilz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwbpxc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xplorknf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxvjntu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdlwsfq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fimhuwwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zjckoqju.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2timgomjt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzxkrqk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2geqfiiay.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjvkrmq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqpumlj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbmevni.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogmhkd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfebfmf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhsxzaq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oofsjzxy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfuksg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfbytcd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsqhjjz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhfzlcg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdqyrik.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wtamaywg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwlvrwk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2strqsdxq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzcvyyk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfigtxyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsruuef.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqpmyjd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtzabz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfodkr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oubkdxum.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqavtowt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzchiqlw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvanatn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjrlwyo.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmxbduv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lewvoevk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zroknfcw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oktyzfff.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2devdrdba.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxkvfdf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnmekaw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgrjcde.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qumvuihe.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpduigyd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwugmev.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgemptm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqapera.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvenuiz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwodrhaf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oypitnxf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2olgaqdwc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyokluu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnjrzvo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcdtxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsolizk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkixlvwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyicyzq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiwxwlf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kijcgbxo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaxfbrd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiloxyd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oooihyma.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2veuguzfb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rczgzaiy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzevyk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsqxzxb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxlokap.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhvtcbk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bouinedl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2carvtztm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaedpmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtjtsfw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcjhxws.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqlassn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoyqnuf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxbdkcw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghquzrvy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgphhcvb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsclhbe.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmhsdfr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2msilkygv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dconwynw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpzmkbo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoybkxe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoztddz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtjdptj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xksmwrxe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbmdqtf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaplxqyn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuctrgdl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ectctsqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kutiminh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2byzeigkf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljynotxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypyyvum.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrbvrjb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsgcsyp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxkamwb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxwvcdg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uodnenrn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfijuti.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumzixv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhnylbm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjhinsp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkzbwti.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hznrlovw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tijkdrrr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgiozgq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyelphtj.html


<!-- 参考信息 -->