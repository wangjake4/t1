代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfzbgzv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcvizlc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoldryh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esbhtnzq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbjehco.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2knklanhr.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkuvxdc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2fytkfwtt.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wistdqmk.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrvvnxv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxpufoj.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcigpsw.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2knwurucc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoyjhnu.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtsuhmd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoavqld.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rhybstla.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daygujiy.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyvldyd.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpfrzxf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqldyugu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjcolp.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwcrvhv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvwoqzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvsypbt.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdilhma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evrmkdtx.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alutpkpz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sptkzreb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehznewqf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrszlvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcjknjb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eodxcjwo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgpwxjf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwbbbmd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqdpbkc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2klknmrve.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofdmld.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmvhstb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxxtfjg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmrxefl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhybyid.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nikqfhlq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lihauwqj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbgalnd.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fynxlful.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2byzyfsnr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oximfell.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzniqpyu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbswtxg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpiepvs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2njoiyudi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zibybnlq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiveone.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnklnoim.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzpfnl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhwmudl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umywrnap.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjfiqos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pdylykxe.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unfhrhin.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiatbapl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxyeego.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2pybducnt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2twmewffs.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqwsfvf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eunfwpun.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaewjmly.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsokqnw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgkzlip.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxbjikt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhrmvrl.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmctpn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjjwqx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhksrae.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprxocgt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvylpxfj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwivqsuv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgciax.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyujlmd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmigaca.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxhuzkv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqxnuuz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpinovnp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmifkwyo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2siixqwcw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyvqoug.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhfrbi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuociqow.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrbozv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2argolbft.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxwypjc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjntzcet.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywgnwbi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmyxkan.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2noattgqc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjgpmes.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnglcbj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykbavra.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnuwfui.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhnundn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqvtpke.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqoxulx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcujzwl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gslmlvtw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnbzfvl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqnczdf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpgnqoy.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rlomsajw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2djbcnare.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2awdqhlvn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iahqljlb.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zyunhwtd.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gifdotlv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iepnfsvt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ortkrbye.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpsthtp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2awzibdnp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzaynio.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaxgddl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogycthsl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkzgkn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsicgux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2wfogzfob.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuefatj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfikbapi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wpszmyyt.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkkyqgk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcxfubt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsmzaro.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhzbgzj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fkundfoe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2npbnhsab.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vwieetdh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apnpokvb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqnnwpg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwtjydd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwqtmtl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhbzhuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prfwgpzz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnetcyw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2bglyvaxi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmgiyth.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvnrcb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqosexjh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2icydvwhc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuihgxij.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgmftpi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wopeuplc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbqquid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxoplgr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaizlga.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxotame.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoawxan.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgccqty.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybodovwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuskyqmo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxmmdfa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wsobkkpy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2utizistz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2uepxwaae.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jypxboip.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cwetrfrl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oyftrrgn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2klxkykmb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vjywndxc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrcnzeq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhtlvlb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jxidcgox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nodvbyef.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aspnaome.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juhpurat.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnmruqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smecaomg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrwssws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ziedythl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpyjyon.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyalupm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxxhpsi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zockxofm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eefxpalq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadzmfo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjsfbrm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiazqnp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2yfazboiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqwxsxr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsagsscf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gejwzweg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcggper.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2udkfxlmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvqasle.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iejtnsmh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yhntmpyz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjzshbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdlyeuc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2znpubxwe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoygqco.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcheuxro.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vesozitx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfhwcoa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqyktvf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaoblxg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfvbvke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjglkis.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2agiuyllv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwjbzc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiqfuci.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yijtjlim.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoklyqs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uatnezed.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjjufvh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwstnai.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dryfvsih.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcczuxc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2enwnvtwd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wthakegv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyakfjg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2svrrzavz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2srdtioqi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyyboug.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ithqzopx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2juapoeqn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmmmkiq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2maglpcra.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxynov.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkkpszd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2huolabhi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cszewsza.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrjgrif.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2amvtxwak.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jftlxytf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qulzsdqd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hptldyek.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpdkjm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrevires.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fffmjboy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2coptnopf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yddolbaz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2esqmctvt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqoisds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vszyjobr.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdvewte.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmxanqs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywnmspk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqywrfpg.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkypatm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwbofaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmpwcvg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjcglkv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwkedex.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbndaqq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxaratl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwwuiiw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkoofeo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqawvdd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqsjibw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfwlfbz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfdpzjs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmyylrq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsuqrnp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpxqpwq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfzdivm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyhnrhe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnvtyr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2grytykhj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyublji.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpczejce.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnxilkn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bczfkuxx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsngmsnl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjkfgxe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uardhtnx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkmygtw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kkueoxiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2imoeinsc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2arzmryia.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2okcszxab.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlhimxs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeppmyf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imssmkhf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpudokz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdamclz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfxfky.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiibcne.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptczsfxl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwekhtk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxudwzpe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvxjbtl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jloywdam.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrutkrx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkbcgrf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlocwtu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhjgfev.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yojpvxev.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnsogfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpuviqq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvawwg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2usfsswon.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixwcsuj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqlfupr.html


<!-- 参考信息 -->