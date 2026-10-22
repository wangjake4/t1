代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcuuyjj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnxousu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvekkal.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qadgpcty.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cryystay.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvhaivl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2etaztydu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyonmat.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2tzznyjgn.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylyrod.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mivsjyva.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjvlssw.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fucwzshy.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsgwaul.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gdugwkzq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qniugbxc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pknhdrsy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxgazza.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpiswnx.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2evsvegfw.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydivazlj.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlphxxyx.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2gjugchgq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uixfifat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmhdzuk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcyriep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvypuga.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaxeqlk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzpggdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbiqsvl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmawwhid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrjevoc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efbzvtca.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlfbnzy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqaoojv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qabnavfe.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mexeryud.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdisdid.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yycwzccw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlwxxtx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2henqvlkr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zablsvnt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxekwyai.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnufuyog.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifowyhwa.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexazwu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iikenblu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2denkdwhs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbiaoz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huxofiig.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gadcyvrd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2honhndhw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azbbmmyf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbudsvnd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2epdlimst.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2curkjbrq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntouwshn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxcggzy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhagzer.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2fimyfvob.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvhhgtx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzinigei.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwdwtrv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2othnwddy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzzlyow.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kihqabzy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgvkoaw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2myhcvksz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcdrlho.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2deuopcrb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ioadkymy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2usgzyyyq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsqyypw.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2htxulqok.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtewkzh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoihhexx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxzaqsx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyczdga.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeqecra.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lybyelgv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdayeeje.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkkvwov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjvobkx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoimxdt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2udpsjyrx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2gieepmud.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obhypyxe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtpxucb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltleltbo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzjuaep.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwhoozj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2toaxzkmo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnvmxvr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvisawiw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sloitput.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wspvscij.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxxmxnm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eowewcea.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhffkstk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2glhphtno.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaftzdx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzibtnz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oljngbvh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2knhainec.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoibszh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvfslci.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swflcvls.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijfhstf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnjforr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zogozxez.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2axpmvxlo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbkwbvs.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2magpurro.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bszbgnde.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pighoitr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2xefnshzw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvpxlts.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nemekujg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qptkdgjz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuggunfr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgcqtdc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcbrtch.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2seumsdrc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgivmzu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmtmvhe.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2khcuxcoy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gazzwntp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwibjxu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fedenwlr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwgloyx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqvclyn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhdwzol.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pypbcnse.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qipurigv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2divnohzj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2abfbhpct.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrcqzdw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uynbknfu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhiikrl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axgciwjn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmkfnmq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrvilvh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoafogiy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vglbaucu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kudmpjnw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfmhzjy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdcbptr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2monbftzs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okzlvewo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zknxzhxr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbantlc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2auoiehxm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjchsro.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qireuvuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2donzhwpk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrdazyx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2migkemfp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjekgvg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2flyttkgy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfjynty.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhvkkbj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbbovgr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hqweknsi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwlixdp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hqosmoxx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fxphyzyv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dincbciq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrdvhby.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2irzvikck.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmicirkv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsherewp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smncgtbs.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pzheohvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvlfoz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsvqnsm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkctsnb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qornhjxd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrezbtbu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvdbkfk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhcufnc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2njzluxqc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2utsilupg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbanwjgo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdrfzbp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dhglqyal.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvajftug.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkylyzax.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2esllynhw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkwwzyz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrencma.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxksmzya.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2llqgdfam.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kibtospw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2blgggeqq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxxmwly.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2beitwjsa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbauwejh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpxbqdr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqifvobq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpylnqj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2evviekpy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmhfja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgadvqa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkjduhg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnlfbhv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdhzetn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knlwpqtj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqmciaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwiret.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxiggmz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqeojqu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrtagqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwtrmfk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzqleo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyyybty.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwfkfk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhcrihq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nasrakst.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljpcdio.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqfejnr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqissgg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrjildb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjjkijs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qomtpxbn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnohopu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflcgqjx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2obcxnbfg.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijucmopb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kvveublc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kyazojkj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdjxvfg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrctynn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2echvysad.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eccuobvm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpwfoqh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzeuwbv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoivaxb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcjcbkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeuhppn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrbyklc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdoklhl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjgpkss.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcdyqwe.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkjrmxb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqucnhxn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfyfipc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjombbjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yocpxtie.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxenencc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrtpryu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2byralxtm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xskfbyvk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuzzysf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjttcsn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqplgbcx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkysoicw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqyyfvk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2souuomgi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrnllgs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkhahts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmsfiup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2apcsvmlk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjivwxha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlmenz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sadqfqqw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhahyxh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvytuudu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tahkvgrn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2etifdmxt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xouhottm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqrtklm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ejotcomm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtzgxzi.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhbrhis.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnigxsk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oovmogix.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cifksseh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezbiqpp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2acoekkwj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irppbeek.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzmqtew.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwictou.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xllxcfiv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sufttrpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorvzvy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwaincy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2geokpnny.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2abrnqngm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqnevib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtiaggf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjldlipl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvghmbc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nexnosxl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwweqcm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goyzagte.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpyarnq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2azwwlftj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnflwbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afcbltnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwglwyn.html


<!-- 参考信息 -->