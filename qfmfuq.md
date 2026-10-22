代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvozlsp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmtvqpi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kioyudql.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvitidj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sixqiwsa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2geoxwtmg.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kbubmaga.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2uazczcjg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2svsagyyt.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wojujmug.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2orfnvjtb.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gblscova.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dvndlwey.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ygamoyli.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2urlbimuj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzutjam.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcpwtal.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhrnach.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2duowtzxw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcvbtd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmhyyoh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdtgyhi.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhymmgg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmthoam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olsdwdlq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ekekgmiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnodyrzq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epvibcer.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eksegdqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgssnmag.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvcfhra.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bymwbxwf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmcnatb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtdpotl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfezslo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxhywli.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlcgria.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjdzglw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhpsfih.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huhzjdqg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvybkut.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdhxgic.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqeflde.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uzubcbex.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtisxgpa.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhpfhjo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpdwrbz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxdlluj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvwaez.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjbbwnr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyfwown.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmmfopi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pinirzyd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2jspmteqc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssierfed.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdybrhu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fownomff.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xllubnxi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vibnszzu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkaksza.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dadcrhir.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmdavrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2setntizz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqqwaxz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2icifrgtj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2exuzwbmz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zknnjizl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mitujuan.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgwgpor.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2usnnxxhj.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyodwvsp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2chmmmglp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpvgycm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkneean.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nasijqpb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmotrrup.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jslpgybg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbrjegi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wargbosz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgsdjqz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyodils.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2quinzwwt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyfcjig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bljlwmrr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2opaatedo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbpcnvd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2verdqfzo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffkvvm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsectjkf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2olyqiohy.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2idfhihbj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcjpatp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2likkwecw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xifqkgqs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzepodxx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaymlnk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnddjkz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjqdbux.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkctrceo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2keevgktt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsjqjtg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxtrvvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ktijjroz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jomnbmxi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefgvbeh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2goicylml.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbenrqpb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2irbmdbgd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kizlbwaz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2paefjdgq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdhesju.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzjhruh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcegrge.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdppiht.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vksbxruy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2rttbpruw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2svjmcucd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbslhab.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpzrdaj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdrujmk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfteqaf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ceynneif.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrcesfg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2umflcvbe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2akxsiecn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbpolos.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yzogbckf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfhnivo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjccadjf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahekqozl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2suuhguqf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pabefuwh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2grwkiurk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vpudbnsy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puupqxhg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmstach.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnnenhc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezunmle.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemgsil.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpzmkq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kunccpsl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrxfnrd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xojptkqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2alolxbyx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bipfqgoi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cgblixya.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeomtaz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiochso.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grulcxdy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2focaetrn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2twplqsft.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2whsmhnqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtgxpir.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxqophr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeudmgf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hedginfo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utlbacab.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrqekah.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zytyhyot.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2khidxhvp.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzchqyb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmxketz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2aoppqyuk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdxdjby.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmptaf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fochdgfl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkonbse.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdphixfs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjqiyr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsygrert.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhufdwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyusphnb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2trqcnpja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trweuqvy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvglmj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kzidtzws.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsufzsy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iiarnxrp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgoqlyk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2yntrojhp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnhghrf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgidgyz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cltsfrtr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vemuaexb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuwouzn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiarhldt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgadzdu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mezlczqa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjrafrz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnthjqff.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmbohny.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pequkwlc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjlduj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdmmjhp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyzsjel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zroytcio.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoiaoig.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvhreid.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lowohhlu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qppbzkjp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpkcuyv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qidwnxby.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbbjnof.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfctgrpw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwugryp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxsaosp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nckcfimi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlhmcfk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlvmywv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejccbqbw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sppbnfon.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bozbldbu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnwfonn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yocmpdhl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsozvqld.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmdzixu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pulvuoiz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgbgat.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbebghp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfatiwn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvmcluv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccsukjo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhedbjgi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzxuqgq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqcpkqt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxilxyg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jilrzpjb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyawhtz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzntgra.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypntfuna.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esflugau.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnffmyr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrnaizp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjblslct.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eaufplfa.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxlzqtb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imaouyjy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpzybew.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcmodpx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoqizsd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jphqmpmb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqceelli.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hstcdpve.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimxjfp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtturxk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcjraca.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrwtcbz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uarmyrxp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrimfjzv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2sztpcriv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgdldy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtrlal.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enrmgmva.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpnxmhv.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yztoexuk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yinngbmy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmpnkup.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvawgtj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcsroge.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvanqxb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ucomhdee.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jysjtjsn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsiieib.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcswibe.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxotiyyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdduapu.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2didyijqx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpecppig.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mezurszk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqstbxcj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlcjbnu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmuowrs.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2baocbblv.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eceocyrv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ewipljju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrbwixd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdvdkif.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfdpaht.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftowessv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cinoeoer.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxufhir.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrvdjvc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrvvldb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgoovmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvncfqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgiaufg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hogykihh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2khunzvvb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2weeswusk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrqfjyr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2meorlsjo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfspin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2heqjcvln.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeibdrnj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcercudk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fozihyix.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyzpxak.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iwglnvqv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdbmmor.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfciaqo.html


<!-- 参考信息 -->