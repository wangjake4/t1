代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2notdggyn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyqmcmq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpkxkrm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkvouqk.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyorymq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoiveqq.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcsezff.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcyfnhb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzchlj.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgwzvdt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrpvxrb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmgqoip.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyufztv.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzaiga.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoljuidc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2grijpbkd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiirvxv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkixzqbj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omyfaniv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkwpaju.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sszppwbd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sskwjfiv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2cnttexac.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbjrehk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvtzbss.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2szmpyoql.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiugzrn.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvzodaq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pevyqamm.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2etqbyucg.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrdgint.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mblmvuff.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vyesdwet.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyynipje.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kufodyhh.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmddvyl.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxphyypn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrkgqdk.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxpbdsp.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sskexkas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npqzvawx.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaniqfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbzobyv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pobcetcm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjppohjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzavbcl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltflohxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egpimecy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yelttgxz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stqvylqt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbjyroy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrtpela.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxnlwdl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpswubf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadssayl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iasjepwr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wftkhrhc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ahatzmvi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqmawvi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2myhvemox.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmqwwgq.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjuhdm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwyyeep.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxgxcmk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsoolru.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arnuelvj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmqieyf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2olxjwptu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsupfwwe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2yefutrxe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jedkljpi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2whomoevn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrcvlzp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llermyyc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqxmvzo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdaafiv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2weszhvok.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnromku.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopkkqhx.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jaksyyrq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrfckuq.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uataboch.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdwjedp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2quovwwhz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmsbaam.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedzave.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgelqcg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2onwghbwk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrfakzi.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcgemio.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2owbtxtzz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlqoccj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhdizvf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmyxauu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfvhhn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxxsvpm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszdahg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hywznknx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2prerlijx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlpnegn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyzoamn.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibsecyh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2munpsctb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsnncss.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjbzznd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vemqtbcp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gahbobpi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2heueiqmp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cykiqcwm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dasezmvp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oamkudlx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrmfuog.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrvzcqk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kelsxpzi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmkhsyd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wzstijep.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2srdybofz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvnviax.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xecevsvj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2aeygjouk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hisycjus.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoghidk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2caqpqgsp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbynhrlh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dddxgqtf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoksoio.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifmuud.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vzovcgva.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqygbxo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zwndbvbq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aycniwhi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2grauoowt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzmghsd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yyskyvzw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtmetto.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuahtdvp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfufnyrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwcaxig.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxczeisg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mtikxdbz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfwnsrn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdgucb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtlxxdr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsakamn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2csavxkog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2drhqdfwm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yznphtxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2glihnabp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbggchz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgjaevw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svuwxkoh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2becoogkj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hojgahnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthwaqml.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdgtqmw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyejdpv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgseltd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgzwlzs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaakyqo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpxulye.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fksdofgr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhdiqom.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qprtjloa.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vstmolul.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwnakrw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagpzeml.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2anfgizvv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kujrvnnh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdoyiua.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlsjbfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmemxnp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefgrzqy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eahpfpgi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iutqrvxl.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pqerzinw.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jypiyrjr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ykadosyv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2imqutuyu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnsjioc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwdjghy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2easomush.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrrmozd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vvflaxjx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okzdfrni.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2brsvvmqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwgywi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggziyfim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvnifde.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwyogb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtehgfr.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmumnryu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmnnhpx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2msqmmusf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkeficb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2brrentts.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlwqvd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsnintg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2alhyoujy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbhkaqz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cowevvhs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rontsnqf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdszwljj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsrrpxf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2itreunft.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwrunsv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mouyaiek.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfqptoa.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqejqcue.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbsmpx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pobothkg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2orluyzyr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2scapscgk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2udgjtkyw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzggozd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pujyecbu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifnnqlo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igtxgvhm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bunqxztp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bghseaoo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxacfof.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyafbiv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2coozrwea.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbpyskd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgccqdzj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjbndef.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsijasgf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cagcwuku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cigqqluj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppllwjpc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wraymlwu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnphdxsb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkqhybo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrmyzps.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjakutg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfveddpk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmddwxa.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvcmtzd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqmfngz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iduxwdzw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2epqldapd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2higqphdq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfltplhj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuylrge.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifcxxxv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkfbtud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2aegldqno.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwinbfl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrttlps.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yawawvyw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shwkpkyu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhyxuii.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmqfynb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotztzl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmarcdvp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuagulvu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2atgtvmzq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2omdntwwb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnprmqwf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kndewisz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpfwkdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwbwqgz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpjwbru.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjvvnye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtnhknp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnjhuzm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2onibyxxs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpdehoe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrdjft.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbopdtmq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vsexfmnk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqevxob.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvozcvsn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqbbqjk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryakijur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaxwauv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhycbtgx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdtpysg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2iwamxmvf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvzvszv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oundiesy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ravxcfkh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vscrnjnr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkaejbs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dafkvfsy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxchwxv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzrtzhb.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xckkbtge.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gkngfhlw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2artqifxd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyaijik.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwcucv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhgxsiv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmojqqt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaaegpm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2edluoiht.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awbpzfoe.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvuficg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvohdmlr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpbieap.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkolxr.html


<!-- 参考信息 -->