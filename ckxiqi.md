代发 wailian999

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrwkrrr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxblygr.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjushxrz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaouvkm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwkzcae.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmtwzgp.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfcmyyv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgpiykc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2miaiwarw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2prbtpiqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhafeyri.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tljeqpbp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2csegylqk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xndavvlc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycyjnto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvogir.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbiimwq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cioylpyn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjfwsaf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuryfnrh.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2naiueoea.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2jscgjoiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvqnxpy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmerxu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtkdxjt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwnenk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pokabbtm.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bivhnwzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvguxcjv.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnqecli.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvyyrbk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plzfskzn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkfhogs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvvthmi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exehmpri.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfecejbv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqafsnd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2cairhkph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeuzxot.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eduitlse.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idneriaq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbqmhmd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aqipodoc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyfovcj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hettorig.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csrzkptb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkldtkt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmplwum.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2smxwvuoc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2miehhadi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdppphp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2naqgxlhc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjqnts.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pepiocsn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzjxlyo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdqempy.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2esjdvgwh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpapuet.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2crxxagfp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdhvxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dddryltq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2seezzrfd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkulgys.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2plrwgshm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbagboez.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xpydpjyt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2csqsronx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjnadpt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyxxivw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvglot.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmgggh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsqpbmg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkbibq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeqoyux.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mugzfadj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aomxrzuu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxutrkr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkthciml.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqptdzg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgthscn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqapfljk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpzxkpy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkgccea.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hpehhbjw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykmfvjd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbquyei.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2adsuwfet.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2echwfgae.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wssabcjt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihowjaif.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhfluia.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzevtla.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmcaazv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdmckve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2etjobncr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcixuux.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2comizqxt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnupjvo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2luqlrrrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqeucd.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiuwisz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jdapoehk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfnhycl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgwlipo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2juvvbvbi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgsvglb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyxvxup.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwdtlt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjuzqgf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2sykdjcbi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbjdmzk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlrnnrj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqfgews.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2opibkhea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eywqxxqw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfwmvyb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbagmgv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxcqtyz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcedlf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2unvdieul.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2opgjcpdz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sseuzefh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkejafr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhccoknh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uipifran.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vykdrcho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzmopwc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgdwfnh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbdvwnw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2adewrlxv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaixknv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuyigrp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udgnimef.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkshajy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgnuhze.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aetsmolh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqukauq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2krhroqzy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2whfjkpnz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrksiek.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlmhohd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stxxegiu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jhabmmek.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbrvfws.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkmirwe.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkquhszk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnqbgbx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2itjjbenw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnhueql.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2agjmxuiw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwzwlnc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyucisn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kqokigtq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bafcaywy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juxvuxbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjadsdg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2sflfugtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjpuxjy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2enjaeobb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaioapw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2opvmlgfr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2igfmoqho.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqtttf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2llmnorfp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtfgtog.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeghuqm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ancgaijr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvgqzzt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxuhase.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtvonlv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlnufdv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yugrytrz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrgsdtn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ermeydgo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2byokxrsw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwwfvkm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfilyt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijckpxf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqffbmsh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzfcnym.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2soglmabt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfzeyjy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2msycyuop.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujbphs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rryrcgty.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eldcshtr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olujvprr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwwhhtl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggphmsks.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2looidgow.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcddhkxm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2smadejij.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iahnjtuc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdsbjcy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2euvpewkw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzpvvwi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2owbumjoa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvekhnw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofussfox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lusgckly.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqagjtb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkepgfq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvckmdw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rirrtkwc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqjxvat.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqbexyp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjifkrqh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kazezudp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzqnpcj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqfdlcy.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgyfoyo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugufyzxu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnlvhkr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfrdhkt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeicsrwf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsckneyu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2havoeisb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdshvoq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmmkqkv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjfvqfh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2seueaogw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2damynuct.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgupbuuu.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfountij.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkhyibg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aewjvrvd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxijmvlz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcppbsff.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrskzlrg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyyljdq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivhgurh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmwoswp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2okkpqipf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jtitvbbu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbbnxgo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwhspho.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlgutjl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qycyjgdg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzgncuk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnvwfnt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftqkljf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2boehppgm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkudabw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjvkooe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaaaath.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsswlqd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnndogdu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2diktrcsi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2muumamdy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpzugxb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqymrlet.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuhlvlu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2frbnonwn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvkwzqo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbaugls.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xerrsnig.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnwgdgb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hldkkgvx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuubwif.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2utjnavaj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhqoynl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfwdkqo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnpvfa.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqitmpw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganzvkgo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtuxooh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxpilyz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qellvksx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqoqbnj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvutougx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnutwkqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nozdsjxr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2inzfzcrf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2woioqpmu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpizuqew.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbckex.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khdsynrw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqnngcs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgakfdt.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbubivlz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2syhjhmst.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjriwlrd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrndiqal.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gccvvlsd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ytddqdxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajakvtba.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2khdaekrh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhysqpc.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyzwmtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mastxfrw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2buifwzbn.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zonmakuk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdacsiap.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwmroxx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmmczyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdjslus.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwecthd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvjkevm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2acjgjglu.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbitufx.html


<!-- 参考信息 -->