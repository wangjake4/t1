代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2smkslzte.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpgfptk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjxevrp.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaathku.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvytjar.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfdkidj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyckblf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2icsteueg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaaquvg.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigjsqgv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2psecmtkj.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohtdcd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hurhrngh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsqbuak.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2cniivurb.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsmbkgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfkxcnv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ywowstwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbvkebu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jusxeasu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgrjiic.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqcafdo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knesqsre.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jydwnfup.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaquxszh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cceuaxvb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2klgvvayg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaqdiot.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuampqm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yucvqbwe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnloinq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubsxyov.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dessbcdh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kgohuuzx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgympybl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oastpoav.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmblzo.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwycmxfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykuembl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmiwxng.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ituldpsy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otzznter.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmembxku.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2htufkpsm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhktgijh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxhqvp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsypxdb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwdbuxa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uieljdjb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvoilxc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxynbqa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrrbknr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2istyrllo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqiwpyy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqefhob.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuyompt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yonisnwk.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilchgxif.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnplgix.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgxsppy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2eaockcgg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbjudna.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdykqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wpipdiwk.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qstmqhkh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvmqjtq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvixnhw.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eduaamli.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2matyatxc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwuplci.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygntmui.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlszfhio.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhzehla.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2vizsdauq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzsaaxm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uktseqjf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrfnxu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2magdpmwe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhukrsla.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpnvpee.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxygmaxm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ahipbacf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sylaksik.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2adcovzup.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldenyczf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopniowx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjgffou.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvocptb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whykdyyr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhuzfpb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuuxvko.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdrfpdw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nllibdkq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvavgkyv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hauglthd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2njwcnjrz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjepoqi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysijahxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuunkcp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaypmil.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mraozlnq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uzovgdut.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhfxphc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmqqxyd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyrvppi.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2adwldqyn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ideiiiaj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2vboyyzsl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrkibd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyyrtgl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tezvgfnk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkltyyp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhbppjg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwlpxvm.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2kznivjai.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2emfsdewl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bznnckie.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzisctb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2uohsggjy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgitrdtk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xagaoblr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sougiqjo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkedotwx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqioeas.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpsrmfa.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnrsdir.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfrapkn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2zllazffl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnnweot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhjufyv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejldrlxh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnlewpi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyshxlq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwhalus.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2arwgbqcv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxojngqa.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqrurgw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ymragnvn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2psnduyqr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2szlzvdnh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufegxgsb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnszwlxq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwffzgy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcmsymf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwramdr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzucmuhx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadetlr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qikavhyd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oovgguaf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrslavs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmezvap.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oytfqgkl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvufbgh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcviobcg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kamagkgs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oygxavqv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ootnincl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ktylodjk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxjsawd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olgbakxs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2etirrwta.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knetewah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgvifpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2munqgfih.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mcubznjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jineaurd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfofkxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2psdngfeq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qblmcmpd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2svvdmryq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sczphuuo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsneeam.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2czsxlrge.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcnbqhg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtxewdr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyozfup.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pbucictx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqndvpmz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcqhpxv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvlsoy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhttjzu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpuszre.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2alicbqbf.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvwacla.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2saqssbut.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewokktli.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgsffaj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkcqjyq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtudyie.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzulfqg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvkhhil.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2twuscbfa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfgwhuq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnvehge.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqjtraf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwbunsl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpymggeu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwlcacj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oomoyfit.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgcbeei.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgrheui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqanyqfj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfhfrtg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ubruwlnm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeonksi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aahdmkop.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onodfsfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nctlffug.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqtqxgb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfbuqor.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2foqtrzwz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrofium.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvesslq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvlfdoq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsxcarp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2strrjkrr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2einmgczf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2suhmbnlz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfsgtsm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgudsknv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkvxtl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltloepbv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuityffy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yasldmjw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxlxdmz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiksjjtf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2edrhzwgl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmwahfw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqcrold.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjtlsx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfaozan.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2klmdxglj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bacfyxjg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2isfkxqqh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpilmopb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzfzfvi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycobguzp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuqdbqz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvuepis.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2urkwhleb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpmxzsb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2avzbctef.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqxpgm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcqmmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mttpqiix.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2epqmewih.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2quuananu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhsyoas.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcphveiv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wopxrkoh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eneflsav.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2udoettep.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvttopm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwmvncx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyubxbs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmaryv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wowrqcef.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxhdmx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jucebwvt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hedoumbe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zksahuoz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqrpuim.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlagewif.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxllmvv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2icvqklkx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wfasecxx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2awskrngl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmqkpao.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aichhddm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqobjgwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkersww.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2undnybff.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfsdywk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgekcuhz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwzbvmp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvpyvoc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axkykycm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfoxnkw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxfbiji.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaweecaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqcnpqv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gliyubuv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnddzimj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjgdujj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nftslwsv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttxtptx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkkcaxe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeffrqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oumoodof.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2duvglfww.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpcftnl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxisrmui.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdvahjy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iukzoomh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epumanit.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfjwgdj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqhqbmu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzkwzc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ombyatwe.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lexdewub.html


<!-- 参考信息 -->