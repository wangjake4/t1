代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgdfduj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lklpqtfv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2hnypxwcb.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmctjp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynsznz.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkaqsac.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbmmbed.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxunkjj.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nalpnloi.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jksrkxzd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdhvtdv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2atminxmn.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjptcoi.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjrptnm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udblpcvr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2upzhuald.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2npmchurg.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ashmzwgh.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2iweesjza.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbknxhof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dauhwyzb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2snabculv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvfbvl.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtggmvik.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcffndg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evusmnhu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqzszgu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmpzwre.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpouxusv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxslujqk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2okcaxvsd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxescha.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwtfjhb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxizeyjh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfmpow.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kojfwekb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdllbqoq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mcndewvc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzybmbbw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjycvf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzzzoce.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkfdfzr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkdczze.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbbqfiy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtiqetg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtdovxe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyggwqw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2essrfzpp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2neuigrie.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lomwretw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evxlrhnu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrltcbcf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xizczygr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgphtas.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbmhjri.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjopfxj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uezocwpt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkpzhzw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uusjeqib.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvvqjxp.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmeeocg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qaushmcx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uekaqjmu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifapemwn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfikhes.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvulsao.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqomsrd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nunluisd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcfnvpg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxrbvle.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dplxymiz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcgcxow.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdaumah.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jymfztkk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgbjahm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2duglroqk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2egelueqf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2eppbmosr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkktkcq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcihytnm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qssxmehl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddwqtt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlythuwj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2elgodmak.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzoxlz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ljirpcdc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkrrgmw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2twwqttpf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqopgcnk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvdtulm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azklmojq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwobuno.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlttraej.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bivopoyu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspacksg.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2snkhpdnx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfjkxxj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjkahwz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnvirhv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcaxwit.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmkwaob.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtbixxd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbznstmu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunulnr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nofdsvcv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2npnskhgk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjptqum.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zihcquyz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sxokacnn.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbxioca.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2clzxvrex.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2whfkmbch.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjovryq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2crqfyqfg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ekykfyaq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeacskhm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2exeoaufa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2furpzxlz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqasijp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaqcseh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcamzol.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuuqlbg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yesijbeg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2phwkimvd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcwosrb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtjkwbc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnktiax.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmkchqx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2modgioom.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2erqfabkc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuxbarx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdecrti.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhkkles.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liwbylcu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2woevtohz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paquvzvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqghyas.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wnntuato.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowiazl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2sycnbojx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkriofl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaeieig.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuetayte.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbywwvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrtcudk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndirhsfc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2inroshmu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdswypk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2yfilxbpq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjusigdq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqhedfd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwetomym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmulcqea.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtlwfnv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmprvcm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpzfjcm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqgwfza.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2exiidhdl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eywcchhp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpcgghu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnvthkz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2psulmlty.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuioomf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eecevcqx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrdvbq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yucespuj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzyykhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faitrcyi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrvyfbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgdqmrx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltzjhv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xidvpwgh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iakfljhh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuqkgqa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdedvvt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2acnuxqqv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbasxyz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhfsveo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrjauvo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsnvgvg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2igbfszmr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wypxfeip.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuglmjv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrruzcu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uegquwzv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbqduym.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2phkwodsb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhpbmzk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdreyzg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjolkud.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkdbfjg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcndilcb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhucbngx.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwbwiuw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzioeis.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pokevnid.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywunsnyf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuukahu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncewdcj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkfouye.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iouofjii.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvborjyo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apotfehn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhjijrx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqpvbko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2alasekpa.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcyompt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ludfefoo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2swnmdini.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmmhpad.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvltcgs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsjixp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2onndkcjo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2miuvqdhq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgdhbyv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msevfmlq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoizkns.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uecujmco.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwmdcyt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2snafvnhe.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qixayqlz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlkfyqw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tjifpioj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyaobpd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpldkks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkonytoi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjgdepw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxjlnrz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cteivvhw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwboyjm.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkbsvrk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2skibgfke.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktamfduy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsfizlj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogzeamz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfasjkkl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdyivha.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgdagey.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjfhsrk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfbxpza.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakskzrz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxacyhia.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqtfive.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eylxwjkr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrxtijt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nfozofxj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbjcdh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjapweew.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkrllpy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvjieov.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcdbkuw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2guihcezj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmzknoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbscyfag.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2arrjvkai.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tframtnh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfibdhk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qaovrcrw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xridzqnd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rgidmgpj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oghrinay.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hchohfkj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiitgfop.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxdnnfu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iflhxmup.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezfhpo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaioafrm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pasompzb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivufkbcu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tvowdahc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbyiukt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbltmnem.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2agqowvjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwaviyu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2msjfrnqj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiqmdir.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2goivgbkb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdgvxpj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfpbkgw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2thndarjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxckiv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzopmfk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqsgeav.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcwuwfm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhgvmw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvofphe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgycmd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2stysnvit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuxzfbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zymkngwf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwtdhrh.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhglwogc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2paicizwl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqjxocv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzlrnmi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgldbal.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkenqpv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqkibn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uneoyjch.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjopuqa.html


<!-- 参考信息 -->