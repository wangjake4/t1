代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzbhtfm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuzxamb.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqbgyxf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpajltoq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yosdayvf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2stmtfgbt.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinyari.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zopvukkt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkyngla.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpnssfg.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdzwnry.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tblsiylz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfelnky.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tekklrnq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2llkzsrme.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsheacsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omibgipq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ekknsvie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puotllaa.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cakonnrb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqpgpjw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqnkgcb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzepllf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmzlgxm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhjnbpe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmetjue.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxkketw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjpdyes.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjwgbnx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnwachu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfnncql.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgcsedq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiszoyz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaifdki.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyehwbb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xesfvvhh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmeuyy.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpojuin.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2usnzmqau.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pptdmmej.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhihiykg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbfhvhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edvvflig.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rufjcaio.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdruwlfy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxaidrq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxzrqwj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxlyejf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqscudsu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdjbqa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbgjneu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaeslas.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeysrly.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwdpmhz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaksgol.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2umdsjjpb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wecpxnwn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kuejmsgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bszxeyai.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkkxvy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2atmetvha.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkhfnxz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kobruybr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rskxwpph.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcblnwe.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfmckgo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jveasmeh.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2piwhvamy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkfqplq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijksafqz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyndhssq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2miefrcut.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhgfpwr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gegphdvz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvylinah.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2byhmgwzt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftjmiqd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtskmxmq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtsrfek.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyciaie.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytapwci.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqzapxk.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2limvecxa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxkqfjd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmkbjqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnosstwz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdmafvp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzdlaxi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfbrhqj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqntoeud.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afbgdtfv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjhjatc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asvfzngx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqpjcjt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tkevtueh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnpjyod.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaanvld.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtmngg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avpkuesm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmnuhqr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmapwrs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2suyktcho.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qporrldm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sabjsysk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeqjgrh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ovczusui.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrrzeiq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdxjdlt.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2szrymgiz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wakgqxku.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ofesbdjh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xibemdir.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxntcgsc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyjtqdu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzdvpkl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vjntcwgo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dikintta.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsymblrg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyygvls.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vszkiqqe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2oczsobpj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2icwquoja.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2emmodyxk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jadvigur.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvbrjcn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjkqjs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alizlojx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmovvxa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwrmsmt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnrwjwu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2voqnimpv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwhirhv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwuajxp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjmkczr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2oerszzld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdejzjev.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpmbaqn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaztced.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzamazh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfwcxzz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhhfdqi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmseouz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zslfjdkn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnggosd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyudxjc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeqcnbs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2kalhafgz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuzizhm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbohtv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dywnbqij.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwmhesj.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2keyyivmt.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2euhuiohi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpyipbi.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2oymrozrr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvdkrhy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2obbecepi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2znzfxtjs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhvyasp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oozfxwlc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctcyct.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xifvwzeo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iejmxycz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiqjxbu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqevxpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ishvwsat.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdewzckt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2llaypsrb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jburrnsw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2arlctgpe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfzxwow.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqtaufh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdwevfn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2huumuquo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2seslnedd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2spoalwjn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vajplhbs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2euhtkbca.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwhrqvm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgjbmyw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxniyqm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhskhuy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rodrhjac.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cstcbtqc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoaemzy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2byosjoth.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2clfqdoeu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmatttl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aayajjuf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvemeym.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeigiay.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvtltut.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2blevhgfa.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgxluah.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbwofjr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcmeilj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tagigkjs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2feqfjcjm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjascsyf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bltuxcau.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2geahkyfe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqymjae.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzaqju.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iryghbze.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmerdctk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2odlsponr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrzxood.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsocflx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wihjkeih.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oodrbltv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqupaty.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbexnrd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvdpkhi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2quhrpurp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yolrnzss.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgevuae.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2aixggpro.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbmuzkq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkhnzro.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2pckttmqg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymccputb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsennto.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzcuuno.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyumpcx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emtpfuix.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2secheoga.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tthjewcf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmugtip.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgmdlom.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcgkrtg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zibctivt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjjxdax.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeosyiu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhwsjjf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzftbqos.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trufbpsp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnhizdp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgnopnk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2asulnbyo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxicuv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2edidkfxm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqlmtnt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstusfnf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2sclmuchu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzbcxzi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bgldilbz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqjxodx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwupkcp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqevgwah.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoxpgcv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2babekroe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouahzsny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2alfdwjno.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvkumjt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmpccps.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjsaojw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gcghutqn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2fobebwlb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkrtexr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvymzoe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmzcbut.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2cahaxpcu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phrxnzmu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxiblgs.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlfpmvw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2urcptmfg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfwvmrf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uevdzbye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxgccxx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2noiajhwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhepxcc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtncong.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfqmkyk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgpxzww.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdrnnrq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2izgwctgp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhssutmj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spoojvkh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmkkbrh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccppgvvs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2dodlhpky.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimtbscs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wunpryiz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqevmgi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcbyomr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmplokaq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzzllr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeoqezf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdpykor.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2olpufrrc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obxjegnu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vilhkwdc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfopuro.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpscrowd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrebpjz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuslqqxb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrxtwtv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnlmeyl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2igjgboad.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2qxluihne.html


<!-- 参考信息 -->