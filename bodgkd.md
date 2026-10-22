代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kwduxhdh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfotnvx.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbfzzww.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orasmyan.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthvzsgh.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjkzsj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2umudagvx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2yliaqaej.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyecbt.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2faxhcazw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2isbazsgu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqsbzau.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmctcrpb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzmyitv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqmpct.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjzsbnj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjouxhcj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgohjejm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bncpqnpx.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2wwidrmdo.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgwttko.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2utdiwxsc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtnwguk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwznfmm.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuqjzun.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqbswau.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kzskmlnx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhgnvrh.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqptetz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrwebuc.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyriqshv.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wypytvnn.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqmnvg.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmajjfc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwfjgrj.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrohbtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keoqxbpk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iltfycjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhborhp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnequea.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuhlgrt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2covbbfax.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfgpqmc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asbhdvhi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thzasxjq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsbsjum.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjfsyfc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zubywvoh.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxxeozy.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2flanwhjp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtsvrjr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnibidm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabznoe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tckrxddd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxhthqu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxvfmww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txxldguu.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wasukycd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxogips.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pargmitv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtqmlrf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okashfpv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frbttkiu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2obkfamil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvwevcl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnesujuh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsogpofh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2roqcgfox.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwavquwk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiskzijr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqpbzay.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiemnfk.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvissseh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvoaxec.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkektdu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzdbpps.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbthhkk.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2efkonbfy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsunsiy.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzczozdg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2juyfimgh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkigwict.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2exngbajj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2aizaqoei.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvojlgh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fomdvreq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eugwsbrf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmocjkwv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsekxvo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2roevpvgv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxstccok.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcqykuq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpgmpzi.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jmduwfqw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbdwlzn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nupdcpro.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftomxwas.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfibwads.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyluzcc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2furykikr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfehrdz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2womciktb.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhysgd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhvrcxo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieriqlbj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfhuqje.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpfvxkr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmyakdd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmzhwzx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpvlvjz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avpmurad.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdbeapp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncpqdjo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2focxsrfx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnxsofy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwveoom.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mngctmup.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpdsqne.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxnffp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhzkxj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qoactoqa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zukcrahd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2shwztpqz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwiiuen.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ejapikfk.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfoond.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwbgppf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbwpztc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvsamea.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iauyrxcw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nccuauow.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zozfovvt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkrogic.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftcxvc.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhshxfw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxpwlib.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2aykytgfi.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplzhsu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eogwlwyd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2avvxycky.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sejwxwjb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wawfqenb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2geqatpkq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvcddim.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ochbwsav.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2psqsphcp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snocwwjq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2haxtphpo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwdmyhl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shamrtqk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvhmant.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xokuulhp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzcjntn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgdyope.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuwtvia.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkibonn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shqvdyvs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ayltjpay.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2walczxcq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwdpokr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvumlny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfkfgei.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2occuqgog.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsuiglx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qowbffwj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvlbxb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsorkff.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpiryfs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqstezlm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pycxxyhs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2axomionv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2novdulik.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmpmxba.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcqzbvm.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfwvhnl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxhxlws.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjoxxa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2itrncdef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oadirlxu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxoaccg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2svpibbpm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eadynynd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxohirfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqhjgku.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhcjmcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyzkdjb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecruzsju.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2szvmhskf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfdsodo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtnxnuy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cujwvepp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlqicvc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kppxtcbi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmieumm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2svzqgnwb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtzyspx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2azwnrslz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsdbeah.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiorpurc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrgyenm.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbroceu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybufap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdchtcc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzonqnh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vfshcwhz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcthlrn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkvcqxd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2djbozsjl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvibftgx.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoijblod.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2spifpppo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnctdqb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldijxyrj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhnsseo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrlqsju.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynowqjyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpogegfd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmdrwmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklcbyns.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oufqonef.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafrstnk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqpaxzv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcjadgw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtdsgj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2budlajmi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mswuewhg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2axfwhbkh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgjphsz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gvujfynl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tkllsfpd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2brjgtntp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sstnhwar.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnoxmuj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2islibwni.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2veawzkmf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuohpow.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhnjjnf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2supiradz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2juqbnhyu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2omstpaak.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgkwxzv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2skguycqy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2klbkkvry.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mscuomiz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2konipxsr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfzsmmo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gydzecgo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qevgttiq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrrfofk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqihlxaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbmlldf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ragjdqtg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdxuugo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2luecigdf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjgrij.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiqanmd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjukaeo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vigjaqxu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnetmfu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksumduyw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvssnnyo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2yghyqmqk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfkrfyb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2piogkzmy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdhpgk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uazkddmf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopjfki.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2thpanyiq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmfoqwk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrdsdhv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolazthd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzsphfc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fdebblrf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbskfgyn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvedikyg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjyegd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ppucvlct.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyieima.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjbyksj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqqswxh.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnwood.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kouuurkf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzdnxcu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzjkziu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2melfvkgc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gzccvbgw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tjehhmwj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hywnaerz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2usmlmvlu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnolpezf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykttgkms.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaiyjhv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuukcqm.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qumaoaiz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrveobmk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlfxmn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cljdlpje.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeyjese.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzyxxvj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mokymhun.html


<!-- 参考信息 -->