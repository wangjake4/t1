代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2duawqhxh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2oplovhtg.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbkuvvq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxpsfdc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskucpim.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2oiudyuhj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2cavwnruf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqjyymb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmvnqim.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ekasrqgm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfvagnc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2imviqhxb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhcmchc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aobbarzm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqqbjmn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiehprv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nghvrsaz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjzlkno.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2zgozfcsr.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzolyihn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2szuwhyef.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwyiwvq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrmuzha.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nigchdcr.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwylbpj.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgfuaqy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwgheu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cfspkzqw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkpggxx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhurrwmz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2blihdfpf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfvwomb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgojonxy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsvrftl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqodljf.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaalkbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnedcnob.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bffeqvpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcpkttv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfekvuzj.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wsizwzww.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoupucun.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2belpldgt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srnybhpj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajapotr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gotsrddz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rttwlrya.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pspacpyp.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcbrlob.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2autrdyhp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okskoznv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kundlhga.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhbcqaw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vichzbom.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzzqpis.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfgabo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmdmnww.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2daoodzss.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtygqke.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcotrnw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrlsygi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwbnwbc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfocsiu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgvaedd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfayjsck.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgzbfza.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgimclg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjqdhvf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gubabmgo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbausevl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2odvsejeo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzvcsv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaultnb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivsuvl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuoowpx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdigrrw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qukpmkpb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxnddlz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cokotrqk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfnzuci.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxpdumr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqpjoh.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uttggywt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vntsmyeo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxnwge.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mvunmrnt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2flstxnfh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aycaavyu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2znergbew.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gffjjfvv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mciqoyie.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaivtui.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2brawfnjy.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdqgsiz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wacycyhb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oelousbe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zijafkli.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2enuluycn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hawtjkmt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zrydvbmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxccpqi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2kojipevb.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sklqkvpu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgjflij.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhndeyz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgaptzy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwhoauv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wunyjkat.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2muilbshc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tskemttd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trchwlol.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvtvqnp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2arybjjsj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoraiub.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dbosvucv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdxoxsu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeszvfsq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbykhxj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2herwsymq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuglck.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjdueoe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcnpkns.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdlqhva.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2scxpymbh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2huxmurip.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuyxxgs.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kamabvdp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrccvpk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzwbeon.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcahehl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2laskiuwb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2spugdhde.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bagvmgeq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxvisvl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2yblbijvg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2liayrbrd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkuljkt.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivstcog.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlzmzex.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdpwdpx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2loezanas.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uefotgjr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2upkqnggm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2umbvodaw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2sysnjsfx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnfvysi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2morjfgjv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqamawq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbkhlky.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfsrdgw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzhcyi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcvamsz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgwtlip.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hacwyumi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpetuwu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnavslf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlxrmxv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2odgvfsjk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2emymaeyj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyjuyjh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atpgrboq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcvhfhz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivljjtqc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxvfqvr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxjwjpn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htdudjrc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcytdbq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqmrhfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtioxwy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mheqzlym.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2syeeokfh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcmdwvz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2evnhchxh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lckkcbnx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yrilhadi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ajifafzv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkbbkpm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqrkieh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pebfukxm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auclvzza.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2otlearox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzmvvie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxgiodu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpfksjg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bsloiwix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqwrjeq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2efklaane.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzqzwq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyfmjjw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzblkhmm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkekczb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaquwsq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcauopd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvewztk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmrjkxy.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2khjkzxui.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtqhvla.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfhvezg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfinxcc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdwflqz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkrkowl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpoffcv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadivuy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2drskotyu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrodjgg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfacmzo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzuafrm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xigpsifp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjvlrhl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeusdul.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsgosfk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdydfjwk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzfdpmn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnwdxib.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfkdmcn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2saizfebu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkipnld.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmghjvrn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqedcreq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkqsfb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrdjemw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjwmenj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sykdbuat.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzscnti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyslihi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpnuapc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypycjnyl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkinizu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eafpjyfo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kssrezlj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2loaieafg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzuqrtw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2peajnmvu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxclyhyl.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqpwdxf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnvhfgb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyebhbgv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbxbfcj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvcqhuc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkohrrm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fecsswme.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kanwsmwg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqfwxyj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsjtkjp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htdkiesl.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eswbmgtq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2kirzofnf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzvqlyp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2adendbwy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2chxozovz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swglpxoc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjschwfd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnzjcps.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aoonsgpx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2chpjkskh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2juozqhcc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmrhgan.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2embmiuph.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblcfczj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiikezi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tskbhjkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jccykkhi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxpvssq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtnmbek.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yracxper.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ayonbenl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzevtxyh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2oezazxto.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyltqpcd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vekwukea.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbetoeuv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2haaicwyl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgmypvi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2veeuvhrh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzndnniu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpdaasr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wcubqtzw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwjzbyp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2geulseuc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnuylvy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2foorwowu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fskaqkrc.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddirzrw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwkaozx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjmuhvg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lyftftam.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uowwgdah.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iddlkkgs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyllong.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgycdzc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvitsyfs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpfdnmz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmrmcx.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yijbndne.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2aamlnuqg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2irvzyjrg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenbhars.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwkjmii.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2idywedst.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stmojjfe.html


<!-- 参考信息 -->