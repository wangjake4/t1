代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwoxwgs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlktuhi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkoxyuu.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qakzefbe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2zfghaflx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gkptmype.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqeqknm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoclzxad.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxccpia.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2othvyzcz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sviezwcn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvixsqp.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxzoqgf.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2izamzsvo.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndgvig.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrsgoan.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2elerbscp.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2jxucjoka.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2adixfkfp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsfvvqq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnsrhjh.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2fowxzxls.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2dinmarzx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxdgtli.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqbyara.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrfsvbx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqugtzx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavadndn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trlaynkh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cerokqzk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdjguln.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbzmdwh.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmlqgbm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2weaguwbw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ymakupso.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbkmkdc.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2guwykzzk.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2phojxloy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bawpbnnj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qusyeyll.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2gydpicyt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgbkun.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqgbwk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2odjdvcgp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kivgvuhn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2awkiluuz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vksaeimt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2guvwnizm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaovydo.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvrnqmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvkpncr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwvprkm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkdvese.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjfolm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxhsgv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrqylec.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwljaxed.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwvqwmi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcczkron.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyccgekq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhomzgg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ceahsrik.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovzvpmm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abysnrzb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otexzybo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbozmtb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiavelo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zjczwena.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxevrfg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bohqtztn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlxpqcj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wninbwew.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrwbzwj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxhlnxp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnsykki.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2atoiahwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfjkzsm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxliljcv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjajfm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azopilni.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrafqpz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdktkboy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pomillnp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjoastz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxrvkgl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevmygrb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2teeltffq.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcftbpnc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2eznlwmwu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmmelux.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcxvern.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2toxwgkkh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjrtubz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxadcddr.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qszuniiu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mnarxfjr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dasvfoby.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpcekbq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpwkszl.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkxuqjx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucrcrya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fupetqki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpplitb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhucmjx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fszcmtdz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2inffokdx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2teafxdcv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkvmhzp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxdyxc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2stggqolh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprigbz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdslihi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfytrso.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbahbfm.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfyejh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mdohdrjq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruihljix.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kddfvfam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyitifx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkawbjt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2huurkcla.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeyljva.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvhaxnv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjpaxyd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtojgxov.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzibhwvz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsqpcyb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaiujnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vieqfrfy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoectld.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlhpybb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdcvbph.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwsybvo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbejpvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2tubdpphj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wvetisqn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gorcenxl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojfpao.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqdgmza.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2feevvbwl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tabqdpvu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjupkjp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzefctt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgxdyir.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwqdqnx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2llsmgpge.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmokldp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2npisrilc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoncmewn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ansokkew.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbmdes.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2miwlfwbz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjifhjaa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2texoxwgm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xygiwkuc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2elfwyjey.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtktvzz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bigoucla.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exdsjjqz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzwupxd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2enytysgo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqizdhy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmopatq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyzbxrp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smcdodrk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2isoyzmpc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcafqsu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggxtyqw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oamivrjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqqvljh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpqeqvr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjxxawd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxewvln.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmilhwik.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxwwypb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvfazgn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbvfiph.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwieggv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlawwaur.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxbriq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klhrzxda.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjfrkn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kduttofs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghzged.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2avvbyzcv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnibkik.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqjczvl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2thojtntc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2amjektyk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbybzck.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ouletknd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxfgipf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnruagb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afaetwyn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oblgcrrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzantls.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yutuhijn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmdzcjq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkromok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaizovk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2psnpejse.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtuibag.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2codsosio.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2krgyoxvr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpzjxcy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpjixp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fldetnwk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gditwtqg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzuciab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wegfemjy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkduyoa.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2czbwawio.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcnctza.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnozosr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiblelgo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzadlv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iassmtwa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2horunkoo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwydhchw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2adplkjbf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtnvkgi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwnrtc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzsbxzo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2geucxyqg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwmscpx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfubcyc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2igcveonb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfcgjea.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbjxvvu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2meabdazi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsgaemv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcszswqz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trohinai.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyczkmj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrtkokj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kyutgmig.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzjihad.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aenhbmkh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdmdbzs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2drfpfwrt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbwyfyc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjdpqib.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxuityd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmclwgh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2razayodz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oafakwjt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ckizlyvl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaajdna.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkawrbd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkckeur.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xamujsll.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gikpudaw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2slgygmhh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyawqugm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zombjhup.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoglxin.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbomfoav.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izdgnkcl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cllqoopk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cturuvou.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2galgsfgr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtehzei.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlajaze.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkevgrju.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgebetfx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2txgvlwjg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsetoon.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qesuxixp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hckjkzjr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcsgtdx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqnkwte.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtwzlxk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eagcyngs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsjolxv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvocahkw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pohkgvkv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlulbkgf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvkjak.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hybufsfy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoxryhp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2whsjxwxy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2siwjanne.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpyzcfl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttfxtp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfsmdpm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2archcncd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbdexzo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kytnolho.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mflitjmk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfufdgj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2libdkkjr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2weanvnzu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjunzci.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjiezfj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2naxckhnb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndjvsp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tknnzivm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjpwfho.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rteutlxk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iftluddc.html


<!-- 参考信息 -->