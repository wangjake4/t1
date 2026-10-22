代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qowddfwr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuoeqhp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyylusbx.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyrdlso.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2bujxgntw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbxzetm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwepfsu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcfpwah.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkixvee.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkynpnzy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2csclmorb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2acurtmme.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjqzcrz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpigboa.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxblaas.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuncdfs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzglsltn.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2rphzahlz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvbetyg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbxafhs.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrcqajc.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwhxvjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2nywgekzm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmzsukd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aujunjka.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjhqftc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuzmley.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahihfdhz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvpmzdj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dohqhdke.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2iosvdxzm.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfhycfr.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsbuiwl.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2alcqjmtz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ustyypoj.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xriqgkwt.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ticewbxs.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcbafiy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2trllyfaw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qtymmkjf.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjzlsce.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wntuzadz.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yibiibqi.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iciejyvl.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuktzkg.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzmswri.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqltpsb.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlinzyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrwqtyj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzfjyhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlltwzqc.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpllcgen.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkfyzxw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeficqvd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmxtvvc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ortumucs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvgkwhu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwcooje.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grtbtohx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdzqwts.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlvzixx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkpdcyx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wruodylh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2firrilkx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcmbvib.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vsynltrr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqxuojz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zphaxrtz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2alasqgur.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgjkfra.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtwwook.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzfbtgm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjnujio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbijbbb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmmiaim.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejctpxlz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kclriqst.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqfkodh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkylfii.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjimonl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pomzphcp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cngoufwb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sajwyuni.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2smhlqsue.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zasexyjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuziqalq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwtueti.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifharxth.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjqxkkc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuocbqv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqeatcj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xoillsky.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcljtxr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbjlrii.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcxbnvl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsgnbri.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vmllzwmq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jduzydcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhsivah.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwwygtp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcscrfr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrxpztw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyvmroj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvmkur.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcticrv.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ftupxcbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfdjjr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazrwsqx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnqvdrp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlrghkw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrlcorl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqrezej.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoknvst.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2obqxiiau.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hhudymkr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqywqqzr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrezsbsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhyrfbt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwevsofb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2snhcxrmd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkwdybo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnysrsm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowghln.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrgunwq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdqzknk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atsnfeic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2eftpxruz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdedzcc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbhhdy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdjmohb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcycjlrk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyxgdko.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvxypkw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2oketdxkt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqibhij.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwjcynp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsqtcfv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2givvkmbv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrgcgeh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxqtwzo.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2caetqtkg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfezqhh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fiykdbyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgyluyu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvhxtlu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xakwbupo.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2svmpafit.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrsvsum.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpidzsv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2arwyyjyu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2brxjuyop.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pltuzwvy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2buirtlct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzkdoml.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgisqunm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxgjjn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoqnodm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vslhadlj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyaoeyu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ciswgztb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ostieswe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdesjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2msaibmfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvyodcj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmxqki.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwuhdqj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgfogca.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iniejfwa.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bryqazkc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wywjaeqa.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fydbbglw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoyufha.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlllmiah.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crvjflci.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhysamk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqmqvmk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyqmngr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpehonjp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rftkxlus.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprdqdbw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpzklyo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhqbsbz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nddqpcib.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dckdseby.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cjchutcf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfwrlvh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzokhu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mwezbjnf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhceba.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zmctucep.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpmvjgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etjuglnn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrdkipq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjclldds.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oescskrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcdxyca.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyxdcrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wosuzmdw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltozylcg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvingza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rncytikf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaowykb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwdlfyh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nzonjkez.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhucladd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfmlqvk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xokganao.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2weamzjyk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiitohu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddojhipz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnermrdk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoborno.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djgprbbd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyaiqmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojrmadt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvgwzx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tspiybdz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bauveuqg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkkdmlj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jcccvxhd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhchjsq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdkmath.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwqqhvt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oazeaony.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjttuqh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odogedai.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyvlque.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyczmuvj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyrydgk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjpogii.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxyhkqh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvfbuus.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwwextx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2laaitxlt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uapopkid.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhjitzc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhauiuuk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekifvmo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2olesysad.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2assvbgic.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cogyktqt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkdakju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2scwzxdfe.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twfayrou.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgtrssa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2arizajes.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsrxkwn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzrdzwj.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqbslnw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxulrpw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2brcpnfik.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2aufgrute.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2djvhbszw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbahzfx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kidxelpx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvquoiq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwloude.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azywtcqq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxtadkz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2maiwaqei.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxwkhmv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstdvbo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzphvji.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyokawe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfuucjw.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgzxbxe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcsmvdx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmioumv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2detovmcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhlfygi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlewnev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgljzxo.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awoitvsp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fgojtrxw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bonmztqk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkarhsi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awsmlujq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jhovbhja.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsqjhhm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2acukdwij.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2trnddriv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvesonbf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgxnvum.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzztghtj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zebtdfnu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lacipsrl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdseugse.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvjxfzf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlvucpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qthvhwnj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sigkajkq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gorcdncx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwshckgh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulemtsvd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nheftsdj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2govjfdpi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxewteg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhnltxi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2odgilqbm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccelbnmb.html


<!-- 参考信息 -->