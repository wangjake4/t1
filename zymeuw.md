代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2niunllkx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggqcof.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cgadymte.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2yycfhnlv.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzjjlw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2dybhgguj.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acyzygkw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvvkyvh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cclzfiua.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2tqffclmm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxzlium.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoinvbp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ravfpukr.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ubutfrxz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwznzjwu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqihhxrd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjnzsip.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqyowgb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqsrram.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqfdyg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcawnj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yefccayy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bapueyju.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2clmgoisv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hdacjkfd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2prdsvlay.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjaqhst.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vntprnyx.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hvahdmqw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoujkkv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nasitzaz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eduyndhx.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhcdmcf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izrupyvr.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vijyuqgp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppbgeij.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqzxznh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbtogyc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2udqlwzkg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2aldmettq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fagelyeo.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cejdvbwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyxcnms.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfzlerb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygonnjwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrifzyb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfevxzx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtrcdaf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keekrhnv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpyetjs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpbblbf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2selawitn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpapvoe.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2wpngfqws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcennxcb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsofrknz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdlcnlc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqqiqhg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwglqqc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdtzkuw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gafregyf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crztdkrx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jricvehb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whlrqerw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcgahgx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfvzjcq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmrvjtf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbxaoll.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giqvevbh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwcjsaz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yumbdbyv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujngqsjh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqjkpti.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzsdxgl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfhfnxa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpnuznj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsdbeph.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmjksv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faujsids.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmbwsz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoqrtuw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqtrtgk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhseoyv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjodunxf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2kymuihpp.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sowmpord.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uftttvro.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjbkzqp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wotcfary.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsffozr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gthlhzxr.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2veypryce.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbfzshe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrrmodk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntumgdly.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfscxdd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyrephi.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dapntckb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiweigzz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqmerqs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnypwoxl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudziwn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfayotg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lipzenir.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgusniz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2czzifrmx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnphcry.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2behccreg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkedmgb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asveqvwp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbssgbh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrzlqyy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2irxcwdfh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whduimvf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwtfzsc.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wquijeey.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavwsou.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojktzpl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sexleubw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqustzs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uadbnbhl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzsrvre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqopruny.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlnqqak.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbmppuc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uglhftvg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2nromhhca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2alxtwjrv.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gojnooup.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2indlcgnq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2slbvjmrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqirpft.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmurhmb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2liegelsl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qpujkwer.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaqrkjh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsknnxrc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvacfyp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhfokxu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgekgtg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xskxmvdb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzhahmd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2bkinnjrt.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2snoxqfas.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhquzxf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqxjsyd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhegzbm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yldnmqyq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqegmpy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bypuepip.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsulbjrk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbnfphj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhizzcmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yafhlvvk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpfkure.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhmxkbo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upglynky.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2tyejehhf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfwqxlu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2klqrnagh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snupzkoa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2luiknzzg.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yclfzklh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcjkatv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuogcgz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iswfnjgu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrkvmqi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcodqet.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2yodcmxjw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbsvcu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpkwoeb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtudusj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjmbbk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfqzggz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdjiypq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2psexlzif.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2osvghnii.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqokviq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iutmkfks.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2brxxpcor.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxeiadn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjfpeog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzrvjzo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bftcgkkx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lfirwkzn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bykljqza.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvvcpyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgfujoc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qnucfwis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrfrqoz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxozfxvu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvofvqd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfafcmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbabasex.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvobafs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmupcaj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2szobwqcx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqywdmkv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtulxlyv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2epumdmfl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2esinjhyp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqcxsek.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2clggrovn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqengin.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvccmakm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2erabblnz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2afagcren.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxpkdni.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plqygtbc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgbnalh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpjcwg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyxqigp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esbxabzm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmvyirp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2phasmhzf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuwcvgn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzotwyb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sstksnyo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhrwvri.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhonzbtr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhnhwp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqhyxmo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khnwpkoa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtlbbxc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhtsoxh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaaklnr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eahwaqst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqjlcjs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjqsydn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2embgosjl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsmfjjm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwtzcwn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2txzcqyua.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2onoggqxm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuzqvdc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uselapvz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2piaudexs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyzwcsv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdawroii.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvqvokv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tovkzuyj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxxubzo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmswdos.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiwdfpe.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2niquycwt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyondmz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrpkdul.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfugyzr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pppjmxio.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uogigqvu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwpwdht.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgoeaoy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxvbxvu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsrubfp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujvuhxt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xghbilpz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbmxvqq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uffwmhrb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsffxfj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvnnhxp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwoylhc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbigbjw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfvvadk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2edfdceoc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqluaxf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2sznwxexv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpyrbsx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxzgvzy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqcxdba.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrnuukq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqkyfut.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2voxmeboc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hycqlpsl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbrvbbm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmsomgr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycwjvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfryumz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xytuppxf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mayltcmx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2adglzwmg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xajoiblt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhguxkrg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrjaofs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2chrzlitc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbnovuq.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdisugh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipcmxml.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2whoaecon.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xaociztx.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2afyiknuq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcqsqmi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnitexh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybivfdko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrhfjx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tonjxnll.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndstorj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvmvjql.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyeecxi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcydph.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcaqdj.html


<!-- 参考信息 -->