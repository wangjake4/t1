代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2asfwdirq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtwptdm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgbaobu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2eebfohdf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmmbnwm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmswum.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgtzhbu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnslwib.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvlafgp.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqfyfvv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aiylfmys.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyzfwaz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vakzepbm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjvtjep.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2usgnkajy.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsacewx.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfczkpy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtttzepj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2lswnraph.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxfbynn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzftohuy.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2duvcscls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjgbncr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgsnfuf.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkjkgtf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsynabwv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxbodlz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doukjzos.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkxltus.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqscnzgi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ivchulsp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjtowpf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2juzntqrl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbprlusd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nocvgdst.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koeyvldz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejoqunr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2egimxkut.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeaxxoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpemhcx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcpogur.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sucjwtxb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywimypm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfujzob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijaqxf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnjnsea.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azirmbqa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgkaqhu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghynmhjc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhmlvnw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyxpzun.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcdjha.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzahzeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiceujf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxxgqb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcfvzoi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aafqbabr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kazzwhxv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuppjwmy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2noqitizf.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjquyklp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxncqzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvjqfeu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckokhbeg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsncyov.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcjwjvu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vddqwtwg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pbswjycr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mushsuyg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fottdwhm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyebrin.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvhqehs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahejkx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnethlpe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeykges.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2funsaawy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhvafgr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzynoqz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rddoddrf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwlpeut.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutrlhxv.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2npfihhtj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgizwvlq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwtrggq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjmzpub.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vyruouqq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzevkrv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kzndjohd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zodbmktx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbotnzf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwiefze.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdtmkn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cogedjtc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnpqnzc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llycwuot.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqjsneb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hturmvye.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zloffuwl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdrtnob.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2urtsbahy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urssssyj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpqosoh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqpmpp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciysbhuy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqousmx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuaoatm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2farygaxc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uisgawhj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkhztqr.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2luvuberv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcyniok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2yvulfwpo.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aohzfclc.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkkvykl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fsljyevb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhizxgwd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2izlsjwtp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmkjeyp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmenoeex.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgzmndg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkupxqn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbeahvx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2trxxqzpz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfgxkng.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdhhseu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmrnisz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yybwmrzc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgxzhtv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2msnfggoh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkauosy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weecvnfb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqsolyn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqaixbv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygidyedv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfllbtpd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyotgskz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsjqkxw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wclotcdm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohotumkq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2paqxugtg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhkfekj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnvxcbs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlcval.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqmroth.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrastpii.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesfbuog.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewoknqz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dipviifc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzygrdo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfshrvp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2khzwqrof.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wplxkyoj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wubibufu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfdltxd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gglpixec.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdoushc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqvfsmf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2edrcavxt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrzqjzw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsjhqex.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaydrrs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwgczq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkyvapj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsmoxjw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rybosjzs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxxhumh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzqizvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hagohtjc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvarff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbrvhbw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxtucpl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhowupz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvwbisg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcbvppl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vshpqdek.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbmzfji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uywvuems.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpnvxjz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcwxgzq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pymqthvs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdeawdg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzhqlcd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkfowfz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlejidc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecabxjkk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbcmrjr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaijzhb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlpwawb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgboktd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxdepln.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnxrub.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpiyxxs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bluqcaud.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgznwpxg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwrhshb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuggmvn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfzjvyu.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oocpqiwx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2igazuzfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpevxzfl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfwtqcs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zotpbylw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcqrkbt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjxdufn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzsrrcp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmulljjs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmyjzmq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mupgbycr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vszjhlhy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hllfkcpj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcciaztg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljwomz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwjgyip.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qedqkjys.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqyopoi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xdroglve.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcxyaqe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkqyntt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvibpuy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2osteofmq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxiiege.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlypew.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaaswhb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pktpdwxt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2woibfhhe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcevsvl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzautxql.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shfpbncx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaljzij.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2noifehgm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zouosomu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2neivkull.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxrajsu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yaghydpo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrwnfzo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfguqmo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdccucku.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zueraybp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwcvjqv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvxqffq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpvjnax.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qibavrwn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqssxnt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2irnyvxps.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jedgqhnm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhyqonn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwzarfj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcavuuxu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyhpncj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2urhefnrx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2enwdtpfa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfqlrcb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2isfrmqfx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2huypbdso.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2iisruoay.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqccjol.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eneslywj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqjdxdu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpxabyu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjxrrgx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apvshnai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwwepuh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2elnlxlsq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwmbmdg.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2anukohaf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dooeswej.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmiitld.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzbtrxv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jieugmku.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2iywzamsj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqaldw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgparfqf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoxvkvx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzluzev.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2imrjylgi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrhzigi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingjbwbw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiomshc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqikchlo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2izeegcca.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcfzrfl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegesvgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vasrytds.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyvinkg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdnxnuj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirurmpo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbturupr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfpsbze.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2itlmwwpf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2daciyxix.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaakgtd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmoyhet.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2komycbyw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2beygglae.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmogoil.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2stuwgyiv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwkfjpl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2clxtinhe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlikbzg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrivbek.html


<!-- 参考信息 -->