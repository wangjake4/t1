代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoweism.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhlscfm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xuymcaxr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2egznuecr.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwhxgvk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjcsmmt.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hujmdzbq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukswlkn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2somxbyoc.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zspykcgh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdxvgrt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnreuigb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2wthcfgvh.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaxwgni.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2unuahzjz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqpovqz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtafrsl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egilnpod.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgenpnp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhgxxod.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zogvtkyq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znutknoq.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlucbgv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkxwmkk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2bfslvwex.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2spdyqtzs.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlvooim.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwnmahe.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjuxaf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwatdieh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2obvwepao.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nrahtvvs.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnaullk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enfnomvq.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwigarje.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsscfic.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqdnacq.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbkdked.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2exemnntv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jouewtma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfmmigb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtucdgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usnxtgfj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhhchik.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ernxuasc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rildctns.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfedsjf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcqwivg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqazmhxm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fktkudbo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rolxxawd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtntsll.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzcedbs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2rjowtsnz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqwdjvp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djzjbnbr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzskzskt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ienuxzkg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeueqra.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqsenxb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2czmimyif.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lysakjev.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjrwpjs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsocjbsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whvqcjbi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arglahfb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyytvqez.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgcnny.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eeytqdrr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ribhksvh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtappre.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnozztf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elresmge.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmczdnui.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjnxcrx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbahcwl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxkzkol.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsetoiz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeokswg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhefjxjd.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2goyumzsm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcyfjcg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2duaqzood.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2apuoprgh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2gvofnlmq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2idthhvnd.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjilpdpv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nevkraew.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmgalhu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jffhjvbd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziadorrl.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnazbnfj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtrwnfi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqyrsft.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nolarjcq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuuctug.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2enewtgny.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdubkwo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuobzof.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkszmhf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqolacs.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrnplmn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gesyetgp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnoapaa.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrviuqt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrnkcdt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmgwoam.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqjefxd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfqfpmz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlpxuvl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tardokeu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2laucxzwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfeuekw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shyxlpkp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsugcjjw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrsyxou.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzuzmzj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjkeayb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaqydes.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkxafru.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjgncst.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mivzjkew.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtbzesn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnxbkuh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhybyjf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzypflv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzyrpsu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qozgbrbh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxszkj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzuxewu.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjqbsip.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2skxdblue.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnwcvbm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsochpj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyluwzp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2supzkney.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2thbfrmmh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2huaucbhk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrfemii.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxtrfch.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyumdie.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2plukotcu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgptrwn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdruxtmv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpezvco.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebendvnj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pluxrsii.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2sdspkoqc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2teccxpzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qyueovqc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osnawybh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgekwcp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmffvkju.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sodtelgb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgnibxp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yadnsocf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxahzlsi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjshwcss.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrswdaxw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdprtbi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mldtqwmk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2egtlxnkt.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxvjzeh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdisoecw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2injfjvts.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuobywwu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2laznnvjh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmpqeef.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eutgzaze.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2latnhlgt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzpyomo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzeozyv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqtidnb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyxkfof.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2daoqzyyv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngnxke.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmwnqgv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdconayy.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjmauhp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzsucbc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbwauxn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpfefpw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnxozjo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmawsbhv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2akoxbofk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgzpqfx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdpzhex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biyedjrl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2iddrrxxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdudneb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgchkees.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmubbhr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnepsvsy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2blonxttf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxavahpw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tfevbjvr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tedbylld.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfunphk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2objwvlbm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoawsgy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfpvcy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxivbpzu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaftabd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aticswig.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kslxynzd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcdegi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegsxxpy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmuaflf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nryrdexx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eletovnc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pedozqlj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsnlqca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjabnzlp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfflaqgq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmmiyjt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecxlsz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhyahya.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2azlqmbsf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpkxgrj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkyltsn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihopofzf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2czmalzct.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbnwpol.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxeluas.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyycitop.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycacbasj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvkzrgt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnuzqpo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrhhasz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvesctj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wivgcbiy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgexuoe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pagclezy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lasburcs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwrbdx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhynfkcb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskunzif.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgucgsvv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xywfdkgf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzoymch.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzofild.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykadmcrw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sknrznjf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrfcngb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iljcuebz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2reqcvsov.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2viryeicr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hodkuvbd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vworushx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2duztormk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwdvjno.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzuducu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcplonv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2efymzuxm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyjlka.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kezipuwh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2knaepymk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgbjpx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2udpiunyg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykholhm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwojes.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmjqjaw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsozoest.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2walzjjgh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kndovyeg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zspqwcrg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbpmigq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcpkin.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfykvd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwgjtpa.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoensex.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfyyfjb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrtmkgq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwdgmmw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkzoefe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwflyszk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuksjws.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uqphtjxa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfszfrl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwseafg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fuawwpuk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2izhxzpkk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdtfjqa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gboryznx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrophdx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkczvjsm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowxfayd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjqgxte.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaoxuiw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyxmxhu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jwexokhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlpjyiy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjmitbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdswncrp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjtlgls.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpwacen.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfohkpi.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eftrpejl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuirdkc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcmhxhy.html


<!-- 参考信息 -->