代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbontje.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mibagroj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oogshbub.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2esaiaeiw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2tniracyo.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvahuss.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmmcmh.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxenibwz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzfnsv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifyfok.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwrrawz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2draistym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drgccmbt.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jplmhlyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnqvtvt.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxhmwad.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xnviumda.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxcbhff.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpunmvb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazmbdjh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrabmnj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jclfdrmr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmfbsru.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syjsmocm.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twwucdjn.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlxrchw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihpbuur.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvzcwri.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofutohp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jnydbggp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzljmda.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eirdfkdk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaykezhp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmgvbow.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkzasqs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snblifhc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbuezkv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbcznxv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzmzmpl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfzbdmt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwkzvku.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjepzkq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpxmcm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2judgcouy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqetsan.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dohcsbeq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2klekwkjd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nubsxtyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjatkhd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpuknux.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduexymv.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhnquqq.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxdlhqg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjucnsnt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnjojmn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2elhhzwfx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxmjbo.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgpuwcl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpevhqw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsidjlj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yetrhsnf.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2iicikbsl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlklxa.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpypxkx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbsntcg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2anzegwob.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nctbwbkd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxysksbr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2chvjngrg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnqfhgi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwytdpe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfzojsm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszodhim.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwytfdvv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtnfpr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2htxigmis.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobyckla.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2niidqgsu.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sqredqbh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qzutdlwb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqytkhs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmwkybq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwnprrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqbraby.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqbudrr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwesfbd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoojnef.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjjebxa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfgwcnr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmupmckw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qopuaftk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pykejxom.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cthpvsab.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynilomlk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwblglqz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdbzpuw.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rynhepnw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkjxnua.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpcrftl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oohkdjfk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpldlrv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhhwtyz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmizfgr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2taribihi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2viyqblev.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbvmgbq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pifzssaq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2umdpibxg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaquxyf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxprtke.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfqwmzm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2btkpcwfn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dksrcgom.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvepwcu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2znswisey.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tczagdcw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvqsbx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrhgvqn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2argbfzpa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeeucfn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgehyym.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjvarzo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhercwj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2civrsfbr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxebcod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhodfgr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzmorrb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxttaudl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgagjzi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2royitbne.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpfgchu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqjelxf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhzkztz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhiugum.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbonoils.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yceixxfc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfukoihb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jilwjbku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyduxbt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzaoeff.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkktcse.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzanxvij.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wvckcvbq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2srwalqon.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpwzjjd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epnwnwfw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vixuqtcp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmxtuzm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvkjual.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2segmpozt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rarvgjdi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpcofgs.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwglpli.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qowigatk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlpetrw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmqbrhz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ygigudwa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ermggfqk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krtuboyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oogaxkno.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2erqhmgro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azzvhrsa.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbavzqi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2oswxaevm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbikjjl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwwwpn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mujtihiq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkbwzly.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2deshmwfw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2sozwpsfm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrquspr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qwypzfln.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vypbahix.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uncepsvr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvhpzat.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2utrwswfi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgarpdc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrfkpkz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbvlmvy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsfuvce.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2esypbplf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjykpcqc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uokbwxvo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsdvoic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dydpzqdc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjmcefz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2azomlspa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvesdxda.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlhhkdf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgiughk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bltzzwcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2colhatqq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpqhwkg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2midffnjj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnnxeen.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutnpqnd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrfrvhn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfxdcam.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvgkej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xatiakbb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztebfapg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2boymdell.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsevaju.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuagktal.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxxrxuy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlhfkd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuewees.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nezjnbec.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoslhpsk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cobqbrwf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikthvcvi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fombzcfc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wyavfjrq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vobzdvtz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2escfclic.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvngmnc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtzrzfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxdqupe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvwufvr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cljkknyj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmibblhd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyroufu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqjwmos.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aocswhxm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzwhkeu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uyewiptk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emiwbrmq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edgfnhmv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2daffkhul.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2umhotnua.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpghrmmm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdinob.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjstvvzy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gofnsusb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnfseol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2trkvdedx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbeuxhq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnqsyth.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zforgczw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgdlmjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2viizaodo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2acghxbea.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcxfdan.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rleumdux.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tottbovt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnlquqm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2inspeigr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpusjrbd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzmzvqc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqpiqmv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdzirtj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lnllhdfs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gofzrghc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nladgudj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzajjxco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvcpxgl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsidnizv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2enwmogrs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nviiqqvh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jprwynnw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnbiyvk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzevtki.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvssgfw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqtckth.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwgqrwo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqiqeul.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2akflxzwh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrrejqu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iraynhpt.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmiplgr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljblhljz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xccmcsqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrjdxxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vanomors.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpcovpe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cienppwj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrsthyz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2skjdynai.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usbvozig.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2koxmawon.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vykjewwa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpecvhy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaxywab.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikorxibv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hirkyhhu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjaiqkb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoihzyz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iorjcjlx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbnhyiy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvedoel.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xichibkp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggparucf.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlqihcc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2uravzart.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iadzgyvp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2olioxioy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2silhyelp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsincwg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akjuqpvn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrsfdia.html


<!-- 参考信息 -->