代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ancebssp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qokzyein.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2istlycik.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkltmdb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2frimkhxi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2livuncel.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lichxnwp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2rajncrto.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlaonmz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjtgncz.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyansm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbnjvx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kltorddo.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2kibyyhmd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2pesifoip.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhfthij.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2deualoji.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2topvhmnl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2eemhvkms.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlkvnqe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjhnrmu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwweqbv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mubefxhx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbawswju.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztysctt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhgpjcz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2upvwzcuc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qvddwxpf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjipqiox.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qnosepyq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkbcurs.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwsaqh.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pakvkhsk.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjadmcw.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqaqfdg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sptuguxc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrnbddf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msuffnxe.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvrvmss.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfrjscq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2inuhtbro.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojojqfcr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoezpdx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravyouav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhwsmvd.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2brqlvgdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjfyli.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjceppn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgqrtmz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnjetku.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puxieaaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmencfg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndackbgp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfsyere.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfqgezr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvxwxx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qazvzint.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2cscaurvs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfewndua.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxgxghr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubdzbll.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyfvpyc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tglhxsng.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjgvzij.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcdwtxx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lonwtqbv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hruplgtn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adqmoalb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxprcbav.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djumigqb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hivmtosp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpwydua.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dfskznuu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjlfury.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yshbfoml.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxrassf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kudpvolr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gddbczub.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2srcuvfnr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiirypi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxeihsk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znobzzyr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumvgrrj.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkcwdxq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qkshkbfx.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcbcnhl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbpqped.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sczexzil.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2waqdavyk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqwbclg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdndnsvr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2igxlryvz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkhbyzh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fljrswxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbcnzos.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeheify.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhizwlkl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2blkpmwgc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqphcug.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2necgizff.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevurdb.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2amapnzku.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2flcgibji.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjrulbb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzykwmec.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqfjwty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxfoufc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxujcee.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxtdpxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2odgjhxhx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvuyvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2naxsrlxu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdamnfk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnmcmgd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slalvjia.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzjpfbe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooerrmyv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpuwnca.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvogxds.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbbijqc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eghvyuxv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jazxnuwt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2awovxtuv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlftamaw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsjrtcg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2abliynkm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugedurva.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwyiat.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfoftgt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqehwxi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2larnhcic.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmvjsgc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuswnou.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcqryuz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jfslfadi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdpqorx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjbcaio.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvzdupf.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqzdfgr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xswpwsrx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmddqqyc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdynkump.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggbafyx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qklyzaqt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2eylukmlw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcusgenn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vuteasdk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaazidst.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtdnvs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdqvczg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvstlhb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2luckpesw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmnngmp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tlchxorz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwtxnac.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpnwoco.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyfyavt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxermpx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjdylrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbgagnq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjpufmd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lloqihgd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjusvxw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2omyrfrwq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgtjlca.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvazetp.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qcczczhm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zpivzmsk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrrtrvv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxmuymu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2akoiccqn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2upoevdjq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2citnndyn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsuomhv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lklszxdw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqdlroy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlffddur.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwczszz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmfoutq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vywpzajg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbcqfk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zechcqyg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iwabqoal.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnqiqlz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2izqxhvst.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiwegvd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2psllmyaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krckgcbu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoiryor.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2snhpwyee.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtobadcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoopdum.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjqlcyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plwwbipb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkavgqg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cruvhcnz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sswebfbj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyatqta.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokgvhs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2scngqoev.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbphdfmg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxjzaqw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqklghjp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2virqctvs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2baejmpeg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyadqdtm.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rypuvkyh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcyuwez.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbjjlti.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2afpvcwnc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdraufn.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jikgsres.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2niyeygta.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjgdaoq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstzrzwo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ihixobsj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkowkbtd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfypkdjw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dypctdsa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgdgybx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2poujuqyy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aubthyfe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dttnxgoe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwkamnt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxhepbz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsmagxj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdezfavy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvuguxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzchkts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyrmfau.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqhmrqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2manhnvcw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvnxyov.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zawkgufz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnenyzp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmflnpxu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiyqcno.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2udmbyyet.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2owznxkhh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwkawma.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmnfvea.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzzmslm.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzftfpij.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2huszalug.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbimxu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpuqppm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rlodczru.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkftyap.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2giiyftxs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tohkself.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2diasjfiq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrlxuc.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuukozsu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhstqse.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwdlrjt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2httrqimf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjeavwe.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjknkogr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmehdod.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgnrbs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oekthkzx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjshjfwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwuitn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqlnodw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsgedbb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2naaomwqk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjkglwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2efukzeji.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpneyja.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtpgkjv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymslklau.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fugoslbs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtjmjst.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xugybxjo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuqxnip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuatupcp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxifqles.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkmhsdy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzotlk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yugkhacr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tfezxrgf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2czenpdxn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2thrvcdkm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeqdjen.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2svfaqcvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmcuypa.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjhytcu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2razkubji.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2amgxomfj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eavpztcl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxocfxd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2frtxhkjv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnshqzqc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2etafinwi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2obhwchhz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odgwjagd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqlcynh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeymitv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2arbdkcsx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2worafzxr.html


<!-- 参考信息 -->