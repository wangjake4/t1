代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdrydxc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqrdhki.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njpciohb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqiqlzz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcphqxwh.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2jognomgi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpvgxwo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqsmybb.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2qsirmsng.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsoceuh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpipouza.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgohtfhm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zervzyza.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtafmsbf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2naunmfyg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmytnkx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unmihbrh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcjlpif.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ialobhcc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgudjis.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2omihumpb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pltvapep.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2edkqswsv.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzhukeb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvjqri.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsercqh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbaktvr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hozbrkuq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2thypuyjn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxfyula.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2agsknfas.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2daqdnjyo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmcbxap.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cshzcpgj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2htzlboii.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vulytapo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfvchms.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2drhnsksa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owawurxr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qobwnbpt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdipefp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gluqfrxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymneqekt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmppemk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgdclgy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzqtlbp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzgpxxr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbncyycn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaevcgk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhbtizd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhpltnv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkostasy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpxxyvu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zimemqsq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utjkjxme.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zavnjsei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxkbwbm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cacvavdo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhcdwue.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuntxdlh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krezabnu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqchgass.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mosphvrs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyneuphs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwjehvj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxenzir.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oposrzcv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqcynf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pklpdrqc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bydrfdem.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2foaltpkr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvjkafj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obyyrvnj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfveqy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuoqpul.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzilurof.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjseyco.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnaytka.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbaczvz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxaqpkq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2btpsttku.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2znphhlzw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yulvrvsn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzbgtnp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2deteejab.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkaxlo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdffbdqk.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xndwrptq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuhitjj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxonbgs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkuodyy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2toiryscf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsevwbg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2asdbfbei.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvrbpsd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyisfkqa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gntbijlg.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjnhjeq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2omevlthw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2zewifdeb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgxtzw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjhunym.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zxirdlbd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2sypnlajs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsqmovg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebtwulv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueogbrth.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2pasnmgup.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwofpbk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fgppsaom.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elebgdmo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwtjsrd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhirvtuw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnorct.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2enkshkxg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyvgjkr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nppfpavg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqplagf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrecujby.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hylcitrs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpbqezs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzldxbt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkusqya.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qcugvaec.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dvourmne.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2buigfdhf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmanjdh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2etprnyxh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksoleu.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsvdtuk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjldvky.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2irxsgwji.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2drsyfkdx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfmftcr.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2odogsufc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2slzlzfqk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvfqhxv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmboblo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zsphvsss.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2eciqklyy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrukvgg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqjdyyx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gawfyhjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dmycemmg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpycgtcz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xrebopvm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdxmltu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvxyllc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlkduti.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vacsemis.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxgvgtd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbzeyjq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klckpiyg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrcpyjq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdpsixf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjmqgve.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoykecz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tpopkldn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgldluvy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2prjkgmib.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngndzbna.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppckbha.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2echxqgyu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfhaxhm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnsuccz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zacqjdoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ukugiolw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnesbiou.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxvhfag.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yowlqrkr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnmhjxk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvtuwbs.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkmyrzl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbqkytu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiiuvth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxidiaa.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkgxkvq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfcoku.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwvqgjo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfnilqi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ldctpotn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhepiel.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgnshmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inyngnzp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzbhxac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjsuxi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nshxpvqo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2sebjptsa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjydmvt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaypuyh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2tievfjwq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdlyseq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yafhfqof.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjjpmgm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2veqevehu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyamdpw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwupkpd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxjacfk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtqrki.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwimadd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2macrsbjz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsrzjqf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuyiczg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqcssro.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnqhsyh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcmmdeg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aktvkide.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2uswbjslq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdqrzvh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsyqbch.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2svpjjudc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfncyoqn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wshuqybl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htdwcdno.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmlmfdo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyqrgrb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikznzgfa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnpgduu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qguydlee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qniqcuws.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2naonheyb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfojqdq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdtuatr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2faubeiss.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvccrozk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2egnyprtt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjaknpy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dphwbrig.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwtcbnn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgvljd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpkvanv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teybmyer.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvybrsea.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnfdjor.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbjouon.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zsisnlrj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fohsrkyt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cifwdrdt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpdcezq.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcwocci.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfklwlqh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnspqnj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nginytpx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2asrmzxhs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzutzpsz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwyqqog.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyvnyhh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsrohwl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drncbwml.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwytjsx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbayzv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldndkukb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcwlzjl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbwhpus.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgttave.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqxfcvt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdvkygk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwopvdls.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2asduypov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrxukok.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqpqsak.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxidbnw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfowidzq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvcyvmd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iccnezes.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lvudikgn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpcroyx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sunflnhd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcfosoy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtqbtky.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkcwfwt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqinlrf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdtmanj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hslisbmm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlyxajg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gsumfrjw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbucxf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnkaadx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwitkn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjuqbww.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2covjepel.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2adaaerar.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuifbfe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2obvvyhua.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sznocbhc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpgbatr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjzuesf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyurnjpp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuicrke.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqbdeoe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiswkps.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaubeer.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzkhsg.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvbmmxo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nemdktrh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgjewtm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebntvgli.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaphasz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djoawhqw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbarhxr.html


<!-- 参考信息 -->