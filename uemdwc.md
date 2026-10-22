代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adkjijqa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqvghpt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsmnljz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiwqsdl.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2thtmqggh.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcbmjky.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2liblvtwq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzmpsfo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfahvpz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2copsqrne.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxzeqq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawypzuj.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoyksvz.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2yromwicf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrbcctr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvlppau.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onnsxddc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woeeftrt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvyuhvn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmjxjcz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjrekfh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxtfdfu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiilkxl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2unntwyuc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yncfcjiu.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hqekfvzm.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxglboe.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2veerdytl.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvjtkvk.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkkhcuu.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2buykstmy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpuaotg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2jusocvvb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjzaoik.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthsjqq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlqagwp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpaamrz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfwdaif.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnwsgzg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpokasv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ranewwal.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrjbond.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoybbcg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqocqu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdornd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtwttem.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvigqjgd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duoybpfg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdxslxj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkawnddz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzjbudr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmexjnq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2culugkvm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkyvtz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjfqnuf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeofujx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvcgwby.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xivlqayi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrtwivf.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlalxnp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxbkcmt.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpsvsks.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvidwgd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llpfcyku.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzyurdo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgrsgjy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azwvvfvo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2iltufdaf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjmpqey.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsagdwm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyjgnma.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkspxtw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkhuwqc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jihjglpo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hydmksvi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dykcdgiq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amuqkvep.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcwxips.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqhbosz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzueogzu.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbcfen.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqndam.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoybzac.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgmdxxv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2luscbtnr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2emqmnifi.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wotlwjvk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwtqsyo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2godpwcvi.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2iitlgjih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdzrcog.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkkrrcf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmycfwgx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2umkdohfo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2moblumdx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqhrovp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokvdjdx.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzfqoms.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgqebex.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2boexbbie.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2amctxqfb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdexuqje.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xokexfjz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2afjhwmzv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphhwxti.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2yylmprxo.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dctlvamd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tsepwgbu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntidojp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppacqfqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhiwizl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2mtukhxay.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcgxbpe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvktolm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmlvee.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2thvrhytv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmsuteq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoifyzh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2liugfgeh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlrglv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gukcfxlp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrrikbz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otksmefl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfpduna.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtdmrhe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwtjlkt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabgjqu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfaxkbq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2enptqxhm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wvymygtx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2usfvqlln.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrkcya.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ftonoygl.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2frdtzrjv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtiewhz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvtfktb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mriukpbf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2eddfpdfl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2uauxvxku.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2smsqiubk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhrdwv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaeonlm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wusibzoe.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwobwcjf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjaurkm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwmuvaz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfdmgym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuamtwt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmvwzvr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2arolmdis.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrnwytr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkayoiz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wiinavfr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpkiyxw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfsyrtt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iivzketk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owqaxtbr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2udguhmpc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbbomsm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2uguzhvzj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2niutmqau.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bathvink.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvxlgjn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqjsifi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuknhxpp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcmuwtl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgxtyyf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jurkesyj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcgrafr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2imuafixx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2weyeochi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqarle.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzotmjri.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orncreyk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oetkrawr.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmhaoxj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrnrzqm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2abfyaist.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kesoetlv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjcajzo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lldezpvf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kemlpine.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmlrgzj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kldvxvop.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxsgai.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egjgzaju.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ualvygph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2warkixnb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiyujlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvgivur.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmfckbb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgbnyut.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2citdxruc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqxtcqn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2czyedovh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkciutx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtofmgq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2soefzcbl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xioqdavf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcbepuk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2huhlttzl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zghdyjdk.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkicgjj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omptdtmk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkfhmir.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyittnf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudnqnyz.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbuymhf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elsgczvf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyjfvad.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqqveyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlqaxox.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2snhwrndy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lildgiqh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmrwdzp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbgjekx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhgcnka.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjtily.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dncqnwfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2seymwayp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvwvghc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbufaxpj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2myhivhgb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xugpmwqg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbouavpb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2msxpolvm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mhylhpzq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjxynfi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlecygx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2knkyadkp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoeutgi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2arztejun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tggtxqvp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrlghew.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnwwkjc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xewggvcv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2peuphxrn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptzauo.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bktkgzuj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybclbujf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2shttrehh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpjiccb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgeruab.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgtofaf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2akjlavys.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qozagtkc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pphgzlgs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuqwibz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgiogho.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpckrsd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaqaqvo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkleuch.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmeonoz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvyxhrw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qivsidjq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrageccf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhhmhjk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2toutpjtg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxhwes.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpngulzz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qocvapnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnetetdc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyeqaft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhnywwu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmanwpzw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xulfhgpc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2koalwvjn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgguijkd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2petjfszr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzfxweb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2czfvbjgb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyebzbpa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdofarz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sopjnfwz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yltrhlbs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfndcal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2otzyhmne.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2csmavfnk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrchxwjc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2milmqzst.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwflydso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2npdneafd.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjydtv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdofzbpy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2czofmzxg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuutxxg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zepddkrl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxdfcgv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vftmjztn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xtndkvdp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxhvqln.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulezclaf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vonmmidn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njexnvku.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzjrvg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdvwegr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhjqkl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmyhdki.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rltctnuc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nohvsluq.html


<!-- 参考信息 -->