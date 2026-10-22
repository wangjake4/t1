代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rupegzsf.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxtzci.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwemqjy.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmciwmb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwkekhb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujwkgu.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2skbzfvzn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ndisjwvp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hariltxv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwyaoso.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nierjhie.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqmekv.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnlwget.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbmbfkl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2bixeymii.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahuvrpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dscutaej.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkupxwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfmhvxr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlmhdry.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrmilsw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpofhycl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvgzgyc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sepatqgi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfiinaw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eplyzvbl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtexsjgv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqnsrdu.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnxmslc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwoweuk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcplnvkq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqnqmos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfainrs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2epubiusj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwewckl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jclejsnq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhsuugr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwexbsn.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uezgywzd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czulmbmm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazeekoz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzwtrvb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzsqzmh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxiayir.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlnznya.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrxtkjh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uceafpge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwvbqzb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqtmgn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hahggnum.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qshtebfw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhwgiqn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwyiazc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjcpbrf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbfahha.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdugwkol.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfenyd.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oneulmfb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oodfnjma.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhalfau.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2gqprjbig.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpkjtjb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgotwwqd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2qcusuhlq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ndivwdva.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2syctakmw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2odtsnspr.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiqzuxa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmcqjms.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvlkynj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrekdpfr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhomamim.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnekwdap.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2eecstyim.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhexwghi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2loakjfkj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2icfycyye.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2heuafocs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuohihvx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqommmy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2cofsewkk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaojjso.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtqpbpi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvaikjo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwlicvv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzvcbsq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psieimao.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nopdwhxo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjmlbim.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzvzeon.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcbpgeb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpuusnz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxekjir.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgzbcqx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeacapx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrfpvx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmwjjyn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoftltwg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxapdir.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2htorgkkx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcnlqxm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsrmgct.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2javfrqgn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaevoxk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aiysmcae.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfumgso.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2owjeeuod.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2prwlvbiz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zlokfeax.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgrgoro.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfaoscu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2isdquokt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xitijkpz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2chihcgbn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudimdjh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2dquottsd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2alhvvjbg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcbjeoa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jifhunnk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcpqbar.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2thmdhboc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jenzlzxp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbmqgq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzkalqo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsnafsx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2gntvwwma.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fktnjbra.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmzuxh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgjszni.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twpufrmz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgiwrar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxehiub.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzrypfp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ialisyfa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlgikbz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nujdycdw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkyafum.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yvafcmda.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tomyzktu.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2clqkvdgg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmunkmx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pndrodcs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchebycv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2utvamnrr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwqagua.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mampnxab.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nvibjuev.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwuhyis.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hklbwdbi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afjaurgj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2shgdxyub.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wesszdas.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2itccamce.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmaruhy.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nnabvniv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzguxqd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bomohhpr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xizaokgx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ziazgbcq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xncxyqcl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiqypyt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbpokso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnngbgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmjzyqi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfheyjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdpazgy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrdmunw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2uqandzxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pxktohwk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvnesub.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2iasvijqt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2elzyywll.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiszdbqs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjmrtzx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2whpcipkc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2glsqguin.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwtekui.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtlbmge.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlqxen.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2drfgdwoh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnvsagn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbynbvev.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oroztamw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfloglw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2viebbnxu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2upoqwseo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgqybtn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfgeyt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eupuptmq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oueddhio.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbedubvn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnzifwg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjbnmx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjngzyt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obltrzcs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2blnlqbkf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2niycczcr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvwjyws.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhwonyw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sidrqdlt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxomfgt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaerhja.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmguega.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2riqowsiz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2trxnmxsq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyvctvo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njzfjxrg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkcdulx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2frnunrep.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ybejsiap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2poynowtc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnwkvmu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnypqcu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sggcplne.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2azggmtfm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmatlaxo.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdignlme.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcxktfm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2diuzmron.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyodkgmv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwikfezl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmovmi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwakwumr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwykhzf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jidvduuc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixclvyz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2epitougt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsrfyiw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuapdhv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwjfvdg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrsffhb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2injovgbf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tliynpsg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzkfgwb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2inlqxgag.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxckwdr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vftjetif.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkgayew.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2knggdesy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjppgxq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tidljipu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eckivulr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhsamgu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpbbrvz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvidaaut.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yesreywm.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2saghsggg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtxyzyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2flvfwkwf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnffepm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdqopnt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2glnkgcmf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwovnbbi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2oncuwnmn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2plordpks.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hrknbjkt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pajvfmwq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfeulxy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobxdjny.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvgvlha.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vyglzgsw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xojuhksg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okomdhep.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhywctk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2utpodrxz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ranllpea.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkezjs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dodlgsvf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxftsgk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpxdcm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2plnqsjdq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiatvwz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrslamk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvlmeol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwcjpis.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuchfns.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfvdfmq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djskejpn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdqygvn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evvqzpzk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qrupoknv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgpipzj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdotqvt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxojcre.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpinacqy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgupbdz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjvmiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtsupbb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rujglxej.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bjttmfkw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxivuvs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2otqyeavx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aieebiap.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2atccunnj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruychnze.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2huvlwpsz.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqebfp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmoftas.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iinmxaqt.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpjmcce.html


<!-- 参考信息 -->