代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2pciuyuhs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtpufzx.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yppluxip.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yhutzwqc.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqmapnh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xagwhkcv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2neljaeuj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwwzurd.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvgffeh.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzwqjvh.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaziyql.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2plvilone.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zakqxner.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmvmbpj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfrrlmf.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rapcltgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yivzyfog.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzrkzbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmtoczs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zykefxpb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcdhjyv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkmhblh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uboqghyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbfigvj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uethomhg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwpujvb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhvjubf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyanhvc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrstyoks.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2xzftwvmq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoitkin.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuqfaks.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrmjfom.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjjrnof.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ristzauo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmbpxhg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhhzizn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vskpsxsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sndudyni.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koixbmys.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiizljd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaowgbcr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsofrfr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbgdkgm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwywpvgx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2csitrsco.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlugjvft.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuunwpu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unagdhzb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqxshd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zegxnngt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrolrlg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqoqhnc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbnbqdh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqcqpxf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmyxcxt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2adpfdgvq.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2easqcojf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwveoudu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwwgaax.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkhgahs.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjotrvae.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iufkyzso.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2otxmiugr.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fcswctrr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mndatrfv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnaibyc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhhrbxt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvsqulk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkfylz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngkgeno.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzivapn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2owctuwhq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2caucgliq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxslbmfy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxayifuf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizpxldw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbxogh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbjbqth.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmksbei.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhygjjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2etpewkpe.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuruffo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbxqusn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuljdysa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhhiaci.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igntbgpr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2mlozogzk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eviikkbp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2supnlmxd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqfauqz.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzvxhiy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxczmse.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlqhhuy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2efhfjbbd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsxrorq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgynmud.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ersrkiwl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrvhxtt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2enqplefg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwfbqmr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2sguvhsxt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjkevyq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsndum.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2exdhvdac.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2agqknuwv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyrsrxo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2aizrjpkw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tcynbnjd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cbonpapi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2cxttuxmh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfsrxyf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxlziuw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2auepraxv.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuowyld.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtnxjil.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dveyzfuc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozktcumb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnslugi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbmowlo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eymllata.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdfrlmz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoqrmrp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hajspkbx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kojfcyoq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zlikwgxx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlwhxhj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2befjzckl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2thblzjhf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsuywio.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtavpme.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wusfiaak.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldulhagb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vmahtddn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwqmudg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvbvenw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnbzorp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2lesbcxcq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2orgkcxip.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwnamwr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2winesszx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhlppim.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkrrfro.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwunwzmy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2oartjpyj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bazwcaur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2biagweeh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrijbgl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubewnvwi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrpnfiy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iecbkazj.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qljepgxe.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pckzuann.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegcbfam.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgtirfh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwhsoxr.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdrvmaa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dqepfjgz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjwknte.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tokyoqoq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbfrcnt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuuryif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xattljpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsljmhq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrxqbjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyccbsf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yejzvwkl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2akjsedym.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gusovvds.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2acpathia.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2rttujkhj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ccopsauo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsmvygh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqgjtam.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkaojek.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2poamrjeu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnzuudo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sievuqmr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbkphwd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzipcx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2voeaydiu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthpwkeg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2seoypley.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arvhwqng.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eskmjfcf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxcoibx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfwyjwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqvkicv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cznnayej.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ootjmzgp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2szvgyufm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdefzgel.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2adyupiep.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxmqbsr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avckkmae.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsiecsf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2obamhuwl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdaabf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkpcwdm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzedzkze.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjqeska.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilofplet.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzboeou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmycwk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyntgvj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmatvis.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvazujjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2orhzqgun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ejahsize.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrxnxl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxjekwn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qomuroie.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2khlrdoyg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtqoinu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlfxwbg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyijpfly.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2onextyqk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclkasez.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sgovhvpn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjmhouy.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlevlkc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xndwahql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vueozsoe.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohejqybu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxzdnoq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqtocfu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvwsmqt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2riusuvik.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpheiwa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2asymddgb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldynafwy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkeukcg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2djzjypcz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zcssyupk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tftknmno.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aooornek.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqmpexn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqncvzs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgiveh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlurtfme.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2meamcfnq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bxozuirs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbokrfbs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnaesdg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiefjio.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkpjyhd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2plotpgmj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjtrbyq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklkjnin.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oftxzxlm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaainxb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vytzdokz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwjmgva.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqrzhhr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qexggfwx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlsoixy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ugezvhlh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkskwfd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpaonlq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhioibt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjzvytl.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwsnhid.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnlrnuq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2czbumsdx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2poelkhho.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsbjysy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vynjltwc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhybckgn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrnvlzd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nustpkjt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiwqdku.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2legdbzqb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srcshger.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyylxvkm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfyqbum.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvtyknw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlyyakz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsmzlzs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudeokbc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efvnsljf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ihonasir.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngmsixm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akoysbnu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcwryzb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2khyhaidj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evenuzxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrmruli.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tladovpm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2inhsftue.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdgsnye.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhpnbrw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2faunaghg.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkgoxhe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjfmvet.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzopupfx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvvwofu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qytahlwm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2lufxqkxn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmchiy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsawzer.html


<!-- 参考信息 -->