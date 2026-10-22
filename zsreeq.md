代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtzutbs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nycrpldl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnadpjdd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwcvvay.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2haogtkys.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vosmnpax.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwrnnvd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2luuugsfc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2upvwtrwv.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nreofpqy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hggbqaqw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqlexo.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkqkbms.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzkieyl.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vkawbxia.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvvwglw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2txkuitfr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvabdos.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndarecpo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrtkzun.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivhlwez.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbykskei.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrohxyg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngufrmnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfxpmom.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mibimiox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2solntmdp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsyqlfg.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kerjptir.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltixkp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykgcitm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspxidpg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikirssup.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwpyaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fodmmnme.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpssgjvg.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmzaifv.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yhybnkgo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vojveapk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkmlhde.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsatgoj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gongfmvn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sujoakld.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmidmfn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvezdqhk.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwhqcfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yocxzeaa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjrdhlw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2astjpoge.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olqnpuge.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nscnbvhb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsfxgpi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrmpxrp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzxwhgi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfoajes.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugomjhym.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfszkdnv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcixyva.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2smjcjmnn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nqetnsng.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdriwcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuvncrf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpspbod.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyasbqwc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzzfowr.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzzmebh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjmlagn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxnpnv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2udcvreqe.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xnilqhqu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrbgiof.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdagdaf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjuntwb.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwzisun.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsemsdmf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rndqukvs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdeonzz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkqizvw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kknypppr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnobakt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwlukin.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2djsccymx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ienyxmoe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzvjybm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbsovdi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2imaplrlv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpqowwz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rowstmrv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoeqlhd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2etotteji.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaxafjq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2oloaswwv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocfpka.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twwdfboq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlywygoj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nyidijrb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzdrhxw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sszmqzlp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voapgdxh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swdnairp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzwabb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bboaxppb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2szorrutc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qubaqtgp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnwditt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elarocme.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefxvrx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrjzgx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbcfvtv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2lppqdrys.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2elctiafy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2undmddro.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbmaxse.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqbmoq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qlglvlni.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzqmhjy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjsqaq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wecsyxpa.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2eckveeft.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyojopcs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jglvafgu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhjxrja.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdspigh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgzdebs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwybmas.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfjjryp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbwqtvc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyewuszv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwzhzct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2boxtblkr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvovzulp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzgdkjb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbijlvu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2jiagqqom.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiebwkw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkjjqxp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyppfce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pihjrmiu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfasxya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvehkhyn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfevapu.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyaloqd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzxomd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhudanta.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twywayiz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yqadcyde.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aofupqkc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpomncv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnixtnno.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxsupwx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfobqlg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkomscq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsytwrm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgylftk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjtwxhj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhefubc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wptdifzh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyfevbj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2txirehjs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgbdnsl.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzwatwc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdymxfl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjhrfmh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pueztmer.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmekhn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyodhsp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzmnmnh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xszxongz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkdrhms.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxkvnaj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhcnatk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gprzqcdh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqpqpkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oumxybsh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xchfwadw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2btursqzu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbczklvz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xskgfyfb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbtbtbb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2enxvmbja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mylwiowv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqxdzdp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2prjvqorx.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgimabs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrboawn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2abribbnj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zihcnzfg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlteeent.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntewnjzi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2afrykgfz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeruvly.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzrtvhe.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiyvtmi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2relubjgj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2teduabzp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeqefry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqhvlit.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vewbvmtf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2suedsbvs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhjdvuw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdquwspx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znfenxws.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiwdlsj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvgwbjm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2orgyvkao.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthdnte.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmopvumj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocifjjht.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkibvote.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwybjer.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyicrwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iczckvsu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2efkqzaqy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnjombw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrztqtz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2diovdhss.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdlgszy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sciifbqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eymxvjud.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znuypsac.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwgewoi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfujqg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxsnxvp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiqxath.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2espuxwsw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfwleln.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyhkzbu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2buczvvkm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lehnxnzw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2izwvgniz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibboembs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njxlqimo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbmfacq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgmjlys.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwzjygh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwmfppn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njduccmd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uurehnqi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nemtobds.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuymuph.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2viykufzt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfeelgx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbzeoic.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfzknlk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eviivcnu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiyzdov.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2waodbaia.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ariwajsm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izouymzr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpfihao.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2goktwltc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yobtiejh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwstaifg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2keqepbsp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fttbshmm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvatybfa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmdkxlh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhchsrsp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyifnakj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskwdmim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ltifnggz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgapbibc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dphnfpav.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkqxdwc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwbfztb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrloqql.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbalzhh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwnbowh.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwcloqa.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2exjoptrv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqazye.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsqrqkb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dldvxuxu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2flemkmrx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwkrkgp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uykfmeac.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmweetgj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzagmqrn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqnyboz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpmezsw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwkfkno.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2klhotwgu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzwoiai.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkvlbkk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvxlipo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmdejmd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiqcshk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvqomk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrzgtiy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsifqew.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyqkmzm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtyflfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaztjir.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiskbcf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nplfxbbz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wekexgyj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtclxcrb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2musrzqfo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrsxwsm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkjeyjn.html


<!-- 参考信息 -->