代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaynpmn.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2wawifxva.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqzappg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpjyzvm.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2irinjefx.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfzwuwy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvhimbv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyvxedq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtprbzti.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmilum.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptasyric.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2quxbbpjh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flhqajkh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjkjcmz.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeuzczo.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwoqxzm.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rumzciio.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cazwaftd.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vcilxwch.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmaqusq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pecejufa.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sundewjh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgadfwz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfkseeq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lpecqykp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzfryni.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeatkwk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmzsak.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2regojxno.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eymcmcpf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcnvbt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjhypxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfexapcs.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzxjzoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmdhwgy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtpwokz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eeibrccb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywwolql.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxmnhq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpyrdzw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnxjgjh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxtxdis.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mizrcoon.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmdhtwn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjrsgyz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvknjnc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgolqhri.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfnrrlc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhciumv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mqalrrsh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dedydedr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ditzjigh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2itfxfnda.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wozzwfnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzbnunz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iirxtrjw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhnkgyl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggklgicp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edvtpgvm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2asukjjrc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyfopgz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnahsil.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhptmkn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbqrsea.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ponekpxl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dorlvcnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxktvyz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2okuczasv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdocoza.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhyjrug.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmkdeba.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvhbijp.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzhlvyc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqckygr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2feywzzyx.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywtjnf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2jeelbzey.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cpukptgb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpyjcjn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rillrrsk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2feoftcgm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2symtmqvd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjivpjop.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ityooijf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsucumsa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kosysrnr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zarmmxfe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcpjnex.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgqfibp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcwdrrt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjychsx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2krkhksmm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwxjlt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibzgwrn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2weuzhnfp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwujxfj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkmfdmi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wnldmcku.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsgckjk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2olpzocro.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkpwbiw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhaumwr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpyfdlw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2udqyckrj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2soggblpx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodnazd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgyqofc.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcselml.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgzqwbw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mufmquth.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfslynd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvruezu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obrxzsjl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2phqfcsba.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umwsfgoa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjulcra.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wttxpedu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jafszukz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2agyqlusw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eweehvxe.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdoqbgx.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eyedwwyy.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2evmjnkzo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtpidey.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfdncwg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhtepni.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbldhwe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnerpskb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zocdkeld.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhblswc.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hftuduro.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ueabyoty.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcpiafn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrmrhbd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jzshyfqy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2cemmnchz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuwbwcj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2udhvxkyr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddehxpfp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2elbawkaz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bowsawqw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdewqgo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apurxmbj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxhyzqv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2djakrjsh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztalxrfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cllmsiwb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2camypfln.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgnyfnn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2oevqursh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoqfvzg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kamicdxc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcoqmme.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlyhanz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbtpwlf.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rogjchtr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xamwawfg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grmcdphn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfrpykh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2abcdshau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxgprbg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2syejerby.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2plczxjtq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jacekyec.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odtdzwqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaouleli.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuupqdb.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpalvtq.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzsqeqd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoyxejd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yalgcima.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmwejmi.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ovemdvlz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqkmrgp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2agkvkxgg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kagsisge.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpzbifi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwcxjbe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2almwakkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtcbqow.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvcmhbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qafbhpxb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upthkxae.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaqoamc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxodapgi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vemjtctf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2flibgbvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhclyyp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2abyajbqv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcjccbi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtblkxs.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzsmerq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gthdbtpp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukwwcqf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooolizsg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoxpdyo.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npkgirzs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ravoogzu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdebdoel.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2olhgeris.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvczyy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyvvskz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fikiwvmp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mekuqbix.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pklvxnfs.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exybvwid.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdanoih.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmgwlzd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvitla.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iifmycpl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpjndpi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnxxbhf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhmcvtu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbctpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hclbeewa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2igxsokte.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjquclh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcbzsyt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtixayy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nybabhmt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkckueb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcymnukh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wawoawew.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhylvwvr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pratwxip.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhradhu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqzpqdj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdkkdnh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbqnqpw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnodsprg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sleeojfy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfmtmyo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2thgodids.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glrkuboc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dbajxtvg.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gryyqgmk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fblaurww.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaowrbx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pothdcwf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhyzzq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mddnbatw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixanxug.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nilkznin.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnvzala.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzijhcu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyatvuv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtmxsjt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcellvvd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyekwpl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcrizjl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlluplyy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaflkdxh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedqxfh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rldvxzwj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrghkjot.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2upwssghv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2liswtquc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvetdowd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiiabdt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ernoaiyy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkvhbwf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qifmmrkv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gztgxxkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2guvvnmtu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2islpzocm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhizfpgu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2abvpkkxt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2asimhfhm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wdorkkox.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2afjtuzsh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuoyaki.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqcqfro.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfflvvjq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlypibi.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrhmib.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbdysid.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhvwdr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdigrtvj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqupxjv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlyhoai.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhureftr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjnovdc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xaviwnmg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkjxnm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaoonvp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkqmhtd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgirnme.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwklrwk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxqtlje.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbbvyqm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahvlyx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvehiz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzbodtq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoidnjs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiidugt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2isyvggqf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2niopzxvr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeidwsd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjmgdwq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeuskmu.html


<!-- 参考信息 -->