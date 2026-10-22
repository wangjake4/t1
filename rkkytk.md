代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkbnvdo.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2tiekyxkd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbenosg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuljszl.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2tqajjmlf.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjqyxnq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxliel.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpzloho.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuerwne.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrotqvl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtjmdft.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyiqviy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jesvlgme.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpqjhok.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2diimuvoz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrbpbap.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ouypccha.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdmtpez.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2syqfgqml.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ioliqyzk.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhcmdwk.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2izrtwiwo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2azgfsgwk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2immevnca.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpqhjur.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deghvpha.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iehddzof.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2auhebtqu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2stejakdf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwqqtjw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2brnwiolb.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwxsmtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvrvaqf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwzzghe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdluvrt.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuymzxsm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xphiutop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbquvuuh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprwmopk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icddsuhx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crgbtdsz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltajbifu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgfxwor.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmnizun.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbkdeqs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsppcai.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjvulgx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqpljs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oebyigcw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2axusybqv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsqqpgh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oinxgwby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlrwkup.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqlnlvn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvlsgex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkooowt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuohknf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkorisgg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrafwptx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujlsppc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfenmgk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmsrodc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obrygkdx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yneccsxn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjmjthx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxaurlz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gikbbkho.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ioomginn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njbfzvfx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogflhmr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnglegfc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hluezboe.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyhrobj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhvrtzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdbzfhv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoifaqg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dzciounh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lateqxfd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltimasiz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2avgcynua.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgvgpa.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2btdtdhxq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpccwdv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufasripd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2okzyxfph.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkljpcoe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozcscwx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjwmjxt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxakkgkx.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2woosrgbe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktshmys.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdajsmft.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyablgvr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmcgdqh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnxsxyg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gticofrb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllpsekt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbajdmgs.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoplxrf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vorwnjzp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyftwznk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vweldpse.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmuhtlk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyzovyw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwezrgq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhznyiy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwulnxn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpgvuxh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdoubo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqqdyjn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jhndjxqs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ksznnwev.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyqmosk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdivseaj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegtgcud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2btrojmpp.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hooooodz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hlipxqsv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhgdks.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2suciglwf.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2udwumuei.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kftuxguj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wddnbjzg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnyjtex.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xybwhueq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbawzw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhoikab.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjsdanc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafrjak.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqatuhnk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2epudwigk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2kcluegdf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoykcwn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxvfmcp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuxuopv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbasqgr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpblmbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxjfbem.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkeewqa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2msaoqqsn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2onmzgnhw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpuqmxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flhdqihq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fagdtpvc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzhxrdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqpkjck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdidzs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odrpqsxx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxidvv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2binyrynl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfudklw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmzfvgn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfussx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrqsfeg.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnssuzml.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmzehsd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkamqmdw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfrmst.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvqrdni.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfsukxb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyqmqfc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sukudqkb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nacupoay.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrylufw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsqodlc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqddlbdd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2awxeuwsk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqdxbny.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2yyframba.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvfsivt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2abqbzrfj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ksadvcty.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ayccsiic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ajknwviy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtrewgc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmxkvdg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqjsyta.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxeplbe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utvnivgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elmvlsej.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvpivpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oletxyxs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxevfut.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gexczgfp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2griqtrsg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbwigal.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvedyxjo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uegchpls.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2iehkyyqv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2beltvjqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjffgaen.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkfdwsk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2trdymhyz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxynalbi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxjbrmr.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpckxvgk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trgrqwzb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdsuygv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcttjvw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2foprcskp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kngpmxym.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2seuanfkq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmcyuph.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cwokebfx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hifcuqmp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxuvdpt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkwlkqs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqwakwy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kojyqevw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvirkejn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azbclstd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbiuftx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kenkqkwd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydmbeob.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmgtdxt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2okhwsffo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdwpymu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhsnuyw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2djjheeyr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ckinucsf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jctmewip.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhtfxsq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycerfm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvnwefo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwtihin.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2muapmont.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkbcirv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvskall.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilolggcq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcrkpwj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoxtzjf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjyzqnc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gafrfoar.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxirqdr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ryilogfj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwenpbzf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjpdvu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcausegj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2soyxxhhp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgyrcmo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgdxqhy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tesdkrih.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqbjrvc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwedadm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpaftmz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2atsterld.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhllxli.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatgbzw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomidjuu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lerutqil.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2myodysyc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfatjbd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2irbpjsnj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqluwdul.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcloaiyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzclikit.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jccjtulw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hyktpduj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtprbma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2clqypzbe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsizxip.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dlexzoyl.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2smpccwgs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnmtolv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkbysct.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxohkdu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvpxyah.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhmdvai.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2stpvydvq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdqifuc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfghnha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2btvxouke.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmstyny.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlnamoi.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrfrvxi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnnqegd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2absptdra.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcjftvs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjeszr.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoluhbp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdocrsdy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nikdfvfs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2thoioxsq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbfkgpf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqpligc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgodipv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjcoeat.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqsszny.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtzvuav.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyecyaih.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2relduhbo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sebenjbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnlfgyd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhubapo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfynzshq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaotzpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nrizvjlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyegteew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qijocnpk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwczezon.html


<!-- 参考信息 -->