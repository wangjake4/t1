代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2pixvmngy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvwzkwc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdifgjwn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgycqza.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvxzhvf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfkzvvs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epwxopvs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbbnuvo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oovrnvro.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2guikhsvw.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2hryljkzw.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiikzgt.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtlsral.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jyonghdu.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fxozoxnq.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxduis.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjtwkfd.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjjswri.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlkamuc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqhcxg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpthusg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmfunin.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzbpfgu.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihgtob.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwptywsb.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2laabyfcv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2myyglsid.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfahspmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuojnlm.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iswuomrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvxzvse.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2peopfkmf.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvebysj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwamvena.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvymqjqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdgaemb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxffiuq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpinoant.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbkxakz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yluukqba.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeglnaum.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2goxnocig.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljghnqrr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrfieop.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sriacjuu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmiggzw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqqbnxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2timooucb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rddisjyg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtyoleb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggghbsbu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzkdrfn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oviqldrm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggegqll.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtduikbt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsfqsd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjraiw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjwavv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hueuiyvg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcccywf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzfzjty.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrzuvqm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mjesayib.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdezkld.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgdrib.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfybjgwx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvizayn.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkbrdcv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2klgepsto.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nshzjzwv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zynxkzec.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpuazlp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bayesdpy.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncawrbny.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcqrmic.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2efdqcpfo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeuqajk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2wdepfegc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fawmsusf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhddxfxm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwytkknk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2haiplzox.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwhmrav.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqscnkrh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwctqkn.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbizvrd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hryqazov.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhmpzcf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkbebsr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmoklp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzxysk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2abujrvwu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgypzpic.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2iowechxg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2toxjxljo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlmukkd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzflfzsl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfycbuec.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojplwrod.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcmiqqz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjkmopo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agebvyob.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwabmhct.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ongoiyfr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpbhyxq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icetdfvi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zemvjpxv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgopfat.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgbafxm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielgfqqw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnrghvc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jawfisls.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gosxvgud.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2chdntlrc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2eenkrtmx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgzjnna.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcrtmqa.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdviwrv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbayfac.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqdfshm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zxahktfw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kadfvfxy.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuhdpao.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeanyqdf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qycxvtvl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwgrlxu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqmebrv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fxugfwjr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwjpexr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgemrayk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqanyff.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bipezsml.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyltker.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqynskn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2upqdyaxi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xastjzgc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpzcwxs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtegglo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkujvkzm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmmkefd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2twgcdhgg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcrxddt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtxsaew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkxtnmj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kojnnzul.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlmjefm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzegre.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhxzvhw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qewizsfj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yssjobkv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2larhcikm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgmcwwm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cynhskpr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koyygopu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2icijktnp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsbusmm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuraawx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cislfbqd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqvngpv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2txuzenwb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzapoest.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rizngdjt.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsmrfsm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrmxbtm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2csuaegmu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyafylg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvvaksj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkgtnvw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2romckubt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2elmrslpv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgttvwa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vweojrsl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2htaxgnzq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjsxpz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2payqconw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqyeffs.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkabpse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxqsofr.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvamgjyr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjjjmyb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvkfyhw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvfggil.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gskznezw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpbznyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaebcbm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxhenbt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gztmgiho.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmecnjy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubgign.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfldfja.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnnzhgj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbrovid.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqsdcdp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfvamzr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffytpis.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqocujm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqtyfby.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fifpqoxg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukolwhoj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaqlkna.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmjepgi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyvzirq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdhgbnp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgsofm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhgluwv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hgifuzvl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkfstqp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcfeeau.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzafnqt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2crbmggqy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hodndpzp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmqzyin.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qptfhtid.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufngncn.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ouurdtxn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ediukgms.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2whomblaz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wloomcfb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvgthsz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvssxu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdinfzy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kxueavhk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kusodxcr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yeccgxoo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfekvowt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2txckeuvs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmowmuf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhmbnfo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiqjoiz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogizygck.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dutegvon.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2chlpnqyc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ianaoqui.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjitejs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oihpjpox.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vejiqxmo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odandwmk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrwlcxv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jyudfadg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yevkkswi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcarabqf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrqvsmx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkogtgtc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2voqipfvj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsjizsg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrncuwh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jetwqwjf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fudrwcce.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2taaezfql.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2amthwyge.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmesaivp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnvptg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqktvlt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzwldqg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuartgp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2udtimqct.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2njoitxlk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzzdkij.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tthsihyy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvccphxs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujynjwfr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbaijiy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzcjjvn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlucnjy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmaljwk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvvpfzb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoqcloc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmncuq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2utceqaoc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwszfxu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkyfitg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2faraishs.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2eboldyic.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvwlanm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djiaitin.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yibxazgm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxbnqcf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhquzkj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kqokeprp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyjqkkr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvkubyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxczllik.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2djnjonjx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxjzezu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvbtds.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnamikjf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nloaukfo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjaghpq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiptpxrq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikijorna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrqqivs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjeycg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pthfimqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2beeqtrru.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcdiafr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxggicqf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdwoeif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexezmi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynervhs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miqebfwt.html


<!-- 参考信息 -->