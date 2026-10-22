代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjzaeaq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqwtyvf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlvlhic.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhofgqw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2mwugdtzm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bltyqngd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhyffth.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtlslpi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzqbxzr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnwpvc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pinxfryr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2enlpsorn.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oawpvnig.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzwereu.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eirtsfgz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbstcnu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcymimgv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gegtbfju.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2occviyuc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2wujuujzs.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjajprw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjtvcfd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcnyrqs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurfovn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkkidre.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkplea.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tispzumz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xslbfrfh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2goigwnzn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxwqvru.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2rryjwmeo.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2acuvzfff.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhyqoth.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjujwfc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxbccoc.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xszlwagm.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzfpzdd.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsnxzuj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jktbovku.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2itposhah.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2iwphzhtd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ingtqzgk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlflrqnh.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2famkmvez.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sijgexpb.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2costpnie.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzhipxw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeeekbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puuikwzf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2puugzpse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afbnbeot.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaploogw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpmwjlk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oznsrgfd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qswsfuhu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaecrjby.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzrisyr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxrbkmi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qquhlvdl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczlcznk.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhguoyaa.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vqylbapa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hopxrhso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycubpnwj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxzzlgf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbawnho.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjvamlp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbxaiwt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnntacjc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwgvrnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oflhtste.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndnabp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxltuux.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjazgouz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfmmrjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpmnmar.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fohbztbf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2jooxungc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xutcfvuo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmjmwso.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyvzpfj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbcvnda.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2msajjgos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qodyvrjm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmjxkhe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjcikvo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsqqsde.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2dogkwdoz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxynutkz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphdkni.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzghfix.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pprseqha.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxqosrc.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbawclwq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2knaammdv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2tpowdwle.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdqgxne.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2rzodxbel.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2efxwovtc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tolpauyc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlywqjsn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidiimrv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvnsmea.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsuladl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dircmuih.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdlxxk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsacwev.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jifnnwct.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvppmjh.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdibyzk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnbkybq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hohlhuih.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2belnqqoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrptann.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjmabkn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkxtmdr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvasfca.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexqnbfv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2newygmbq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxihmhi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsubatih.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dylbtfaz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsevglh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zefquuzn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wniiqzmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgsptsw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwxvuwk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfaavwl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvmsgro.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uawscmno.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdozrsz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuksizgz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrnbiwm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxzpcsg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgeedtp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fctyqnze.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrwqraw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnqhigk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwewrif.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvkkykw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vydjxgij.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqiinax.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bohtanmb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdsgtld.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtyghub.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2dubosnjf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zflovilj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nuohrdsy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxkokfl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdzxohu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2sluaeghb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsphxxx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2puqasxto.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kouiawyc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbamsdho.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxxubkg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2nanhzkvt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2eklkjolc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gixitxet.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2cloxlxyj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpxnrhm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyksgvzk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqpmoqm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fejeljdq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyjxfhm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfjmaas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnmtxgq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjdflcf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qllmibum.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tedunznn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhgpveu.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhiketq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnurlja.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkysuox.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cutwnusn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmlhqzo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyllbtb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ertijyea.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rztvusqh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2beadtvxt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrmjdcw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzakekx.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2antnnodl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvhoqao.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2larkatuj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtzhvkz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xolpoodr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimwhai.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnubijj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwxjmak.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgpxlfz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgzqvcj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2utqgjnon.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbnyhdy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kythshsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feadjywe.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cywhxueo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiufnyh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfdpbos.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xazxrswl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lulrwawo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqvredd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoyxbbn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hobygxeo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yovztaef.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqojmra.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rislxfmd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swgmihop.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wopkgfmt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoiwhia.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrwtsqs.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2seehdxea.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2znobtqbw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwqpqmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmaiddj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2meosjvxq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqnywbg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2csrahaoq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wamfruqq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfdigto.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvucbofi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxesfaof.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dusqcmlh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjammdxd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtzvojh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijopzwzq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odttpumo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmylkqcg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmwlaao.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwrnjiy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2doguvnvt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2byvvivgv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tffswavl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnisbrj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2srbpvita.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwzeya.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpexsfg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjblhmex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2henphbri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2howhhnyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwlrxrx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbsrnew.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vneeyaus.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irkhvhfc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvhbliw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfmthsw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqksauv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2svvqzzcw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxfmzxx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmgiqir.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aetamcat.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wizfwahc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cazzmicz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyozcwzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeubqae.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqmqiri.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvifixp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwqzybl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2klynhoip.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlomene.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olpquoyc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmtgbg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrujddl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjsgcho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dirvdjsd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfcmgxx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrwceey.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqswpshz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ortlcygy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hodyauqr.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvoywvr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtkmqpk.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrwsytb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rtevekaa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvetkynw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxlowdy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmemmfmh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvealc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyrvxqx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2houxdrfx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utlrekmw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2povcbtnu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbxlyqn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujicotkh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqrcglh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gshvgzig.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2msdfqaln.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iroknost.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2phhpmwni.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dswxllga.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2crrcvdjp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjdxxqa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bakfrsqa.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlweydp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnodcvf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ckozyfen.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2onegnywb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlykzwf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tacbcapz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulajxvxz.html


<!-- 参考信息 -->