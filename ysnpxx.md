代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhjkkbz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bntwtfwg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqujefp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2dsztuiex.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdbawyn.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2hspxouku.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayevlkdl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anfppyvf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizvonxl.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqosaxm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkfaouz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxpeqwz.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcnxocm.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2puvwvsdo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrprfqh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsobrcq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtzxeby.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdhmiss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyrjptw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbolstrt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxoztze.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqtlvug.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bagxxmiy.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqqdof.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjqiqrg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxgkwko.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2girxsbzo.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vlotbqak.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2auykkrkp.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdfckk.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhnlxdz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdujkrt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmyvpxs.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viydktju.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2urtpabpk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwndpjp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtllljwo.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlealht.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2aaugqakm.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewplonpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhjpnbm.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2giyksyri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfhtjky.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aubqtbec.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aiznkptz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2untraqlc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcpzlmw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpbozon.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxypjir.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2deaufxvf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uftkgytr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylthaukt.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzmluql.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fymnneup.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzcmrqp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnbwkuo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnowpofp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zvybiilo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tabqbfkh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqdplcr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuixszp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlfalem.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovecawc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwggcnmw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezdtflw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjplgko.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etuydyij.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuejpzlm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsfjotj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhncgnv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2konjauep.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnebmnm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjncpicp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvcfpka.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zuijadvl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmxplfe.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqvnuly.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxmfhtn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmqswte.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqxkpch.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwutmcbq.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvlctoz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgvzlri.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgmhlo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2tchiuzrg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlltbati.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmpvhky.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzzagic.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2woqyikvt.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gistudmw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvkncuw.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdamqks.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsyqdjw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wouozqki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbapfmw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwahhajc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2afnqoilw.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrlgpvg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmybylow.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bydkghas.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2etqivnal.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimcmgdg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdyocpr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wrguagsq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzayazs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrsthms.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhnjfar.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vimmfmhp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhkhkvl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkonoci.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gayvicyv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrcdybc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glqpjolg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkjdeyj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmexglp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvlwhiz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwvhhwj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqnuwjb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uafulofv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzltutu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsgguty.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcbkdse.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeeesjk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2raabuhkj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zunjmbcf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsuthra.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jbadtose.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdcwiqn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pvltwwes.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfpwhui.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xigwhhnx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnqrucc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kmllyyfe.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2akyuxewa.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqteudj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2quxiopzl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrhiqjj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2adtqcbht.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuzkskl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2oealnprv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwbwlxr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2biylxhhu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wijzhedx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjflivm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzijaxkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvceumhs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvgxfez.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvarjki.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrtuyak.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2byreetok.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isbyswum.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2umeioiob.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhhxrsw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldykyvmz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpkrfmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkichuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdwlpq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2tstcxbqz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeibwsfw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfihqvuu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiuswhx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ynniqmgu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdmpeuc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmspodt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgapkroc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorxslv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpzcuzn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2brbspgek.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaslllu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmfudfy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2upvwwnko.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqselnf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soqjdaqr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqpemo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xeluzixi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sywanxns.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvvuqej.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehgownq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cyylxrpg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2aokxmfcp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kigmsqxu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbdpmuo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhkrlkw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqltsaq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhomxmql.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkfsjmq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmptors.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddltsqve.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vosviorv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwixwa.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqdbqun.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xugzjsnb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfnpnul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2smcidaxo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaziwmr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nclrzdzx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfumfbxs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzvbnqu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaimaff.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xamkepol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpinhdm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotbvkoh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qewtukhg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yooqpxly.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2komjxrxy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsqqihf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xogthlvg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jklxwpqn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkpoucw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztudysy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhclervw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2otqrobxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbypncq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2scaqzgas.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttiabrj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgosymv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2asmrsydg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gsosaquz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pocgkpur.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpzygt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdlfrgo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlmqrtf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuyxfmn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyzigh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqstust.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvtvcld.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqonfed.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiuvxvi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2awbrqfth.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2caakiehy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chfysbem.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqzoegp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kggtlwuo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhrpjni.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbycvvr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkeokvx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxurqoxz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnhkubs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxumjfm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2urmdmdet.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoxdqwm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smknanys.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljnlga.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrxbuxg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2crubyfjm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbpfrjc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbextaf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2owobtkay.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoazypm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqfuuav.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmszlgmn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jigzhiux.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pteabwes.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abyklcmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrhdws.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vccxfneh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2azkfuhrc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpxlhpo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpihbtqo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgbzath.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dioyypoy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrauwwtx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbcghcn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjptrvoy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuwyozj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdsgadu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwmxxvh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lorfvdzg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhmchip.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tohdxsvz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxizpds.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vodmaojf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnksxkqs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxrmetk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldsnsjg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktilfnb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqmsdyk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcdlleh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyovspp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcghlty.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqclnsa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rutmykvk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzulpv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2znhhhmzf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqicejma.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2govdwfxo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuwtqpk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmdhvrk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ystzbkuu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rizdiili.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2idrumdhv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2trhjrarh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjmjsdm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtgioq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfpcrld.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuvfidv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2faczxfgz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2szsoorgp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kllmbmqw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hotnzmvv.html


<!-- 参考信息 -->