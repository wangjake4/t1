代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icskzmlf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyyiwcn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcemjiq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2epazjpgw.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcdoqpk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlydmmze.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlypuoy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxaepzw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrvystq.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhiiwhe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxtipla.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjkuxpp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2evpnyaac.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxvbxrw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2hohnndxu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulotsrgd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbfdvkm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xornsmsr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtyxfac.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2evnppmnr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbnnztz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2adkzqztv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2slgbxeff.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsgfmut.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwffsee.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyeqwav.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xojzrbqi.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zysvzllk.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2splkfiix.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxsdoky.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjjqone.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oleirrwb.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpjqpug.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqzelal.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsgtrdk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhoiegu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnqoert.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyofhigf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlypkzs.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvheovy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuauqwbi.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxbwuor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzamfeap.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tamkwcak.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekszmins.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuydciya.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlujfjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqoharz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzfmhsb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2csmhwvji.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2adxxfzbe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnusxpd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcenrwhj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjfzvvb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiopjsuf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncceoaif.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrgszha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qktbmsxf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aglododb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2anqyqkbq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2syunlkcj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dktghvhr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydigvjau.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtoqcoo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlkboqf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzvceef.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbimdrz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqakrfnl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjsivxl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlaxvyw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbiinbw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqpuvsi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhdidv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncerbkcu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqbruex.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwrkuyi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjwzixw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudrhxlm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfdqnri.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkurjynj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrklkrtc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvfsdbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2adxrfnum.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwflrqyo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nbquennr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqsptbp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rknabylq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ymahchba.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kefnwnew.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjlvwor.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeiuzrt.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2krbqtvxq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhwzhdu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjhfdox.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixwsekj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbcjxlk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tolsfpku.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeibguw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmakyre.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjgjqxc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hryvkxhm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwfesxe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dougqeet.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuezwi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnycqmz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2midqmwjk.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2otqdxfhl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsmyhjx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoxkpzr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lialbkeh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpebwfmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2tzglcjen.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggvlfur.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqsfocm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huxtjvsw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkmpzit.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qssisocg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrpanmt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjqkqzl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqrkcuv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otqwklfg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lousoejy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjlgkbt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2erfmthzd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qguykjov.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfghaqi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2flunygvk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2amvogtmd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ihakygot.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zburilsc.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qefxugon.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2acdhbkja.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqbqzbr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2alziuzjd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtkfvac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wibdznxw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnkwuol.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2snyddrxq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyxgjcd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xstopawr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxenntpy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgycswu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2liichyfw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gboqzvbk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uiopnlxt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nluxjach.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbujhgqi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qurtymky.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2udcunhne.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvrnkgw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hedjagxo.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlqoqfz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwpyone.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyivuohg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqcoqsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnmwrox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxpbqkn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gplaxlkg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrhzwpg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2guuijtba.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqltclkv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wncnfnxs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wokdhshc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaxqsrw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbazlhkk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2heitwbij.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjfbwgo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyfhhfz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrxlstw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfcmjqx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcxjcyj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jklisdcq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpocjif.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqtszvs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzbbzm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2glcqkqpl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dvswgisg.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfgpgft.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfgqhws.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fhklnxmd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcbfmui.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkllod.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhhtlyr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmahisq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2blrgniql.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlffrnh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inzyrjxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkvwkss.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzpdhqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2powjpiqu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeahtqj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeehoyn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ettpbsfe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjonein.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcgekri.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2atmzhfpj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mibjopcc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eewdegdc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gznqimuq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jgslbxkg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2drpuretf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqslvuqa.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvphxvhs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjfbrbz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlovvjh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2udfmaank.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxmtdbi.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gncfgerg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqaxjni.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2isddooyd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjmfuds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgervmm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2anyyurzk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovsxwqp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rajfcfjh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewyqsyf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zutiryjk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vehphlnn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsjuuvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaqbdyp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2btzernad.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2izdrfjig.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpszuwz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgggftx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkksodde.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmmegav.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2crxkpfgk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmimmhd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2giykumuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzsckga.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2obwxymwx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjmvkla.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jbugmvtj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vrczbdec.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2telwboof.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsekmpfx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2damjhfow.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2finufebd.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaiysqp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrjtcfe.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtngxlna.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkzwsko.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ganbhaja.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjevowts.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qifqadwb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yspqwsei.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsrbzii.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvxqpvr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2asqjlrek.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsmcqyg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqzobe.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdazczwh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2obxjlnxp.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrsxneu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmwtjpt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzutysmg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwyizjv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ifobvlfr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2okknygzq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksracbrq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpzdlnh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfcoizw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrdmkxa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2loptwrlp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2niysqkez.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgeejix.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2debdbebx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2soocbsoq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pclwskhn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yecdowfe.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyplqxk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gajlmghr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2whztiznq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eybtmtks.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipggqib.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2juxctutm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmjdzmi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2eirvzbtd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsaipzx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxccwcp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2woqilcom.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iraacpid.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwmymsr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscijate.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfywcoc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2krvwzcdm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcqtmpf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kolhkriu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzrados.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2iauymbzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhcgpm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnohhycm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqtimrq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwadwsa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvvkwdm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zifevwmx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrbnchy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiebjmw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsauujqt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxwtzsn.html


<!-- 参考信息 -->