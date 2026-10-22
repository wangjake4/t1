代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzonbav.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxjdph.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aecrbtrj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gozsammh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2vknkneal.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2areueukc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyxuajb.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoeyhfw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2hwslrrkr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoajwia.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyqsurf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrjinhp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hosgutkv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnrcvid.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2unvcwhjl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wskqqykk.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbaser.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrgsoiy.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xighiiez.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2diaawzsf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicwxjr.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2airhqfhm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwugfwt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugjspww.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdkvttt.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2uspcwjla.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2sojnbonu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpzixco.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcigmvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlxstpr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzidkpf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svknvqlr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdhmvhh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2walgkyim.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2skbjoayl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmiffxx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2deljkdfy.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jorfcuke.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhwtpkk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbcpivz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uagxangh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jjathufm.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oahcxrtb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxmwjz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrhcfjm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swiaepfy.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2aubobesr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdagaye.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrsotts.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbhvwdr.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2zavflash.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrfsmtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmqquy.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqwedt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqtalti.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrmuibq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaparfq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfnpycw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkmbqxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyexdrtb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmukxsjw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akzxmlvm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoskwes.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvofxmha.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcmmzub.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjnsygs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhquyarn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2femysaax.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmcvwgc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2veysfzyz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cravgeqx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsvleyd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sydqqxwl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eleaewxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndbnxie.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezhqkyw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbqmyea.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbwbpa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkooyae.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmnpufq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzzxtxe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbfbeu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeihdmhe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabpfgul.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htgoaxcf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcrtitm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rtajmhbt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtnimog.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbjzqgb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbegvfrt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwkohfi.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhdwlnp.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yviufqes.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcniwmb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2roqaeqbn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2uldiwozn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrrpeer.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuycgwv.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtuimhi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2slamhdzg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qumssnee.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisyhnb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2almdxbfo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpwucte.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhgpdpu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdvrdro.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylkgxiy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgpcxkl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2alcvckeh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiggiuy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsmzgug.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvrrgaj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxiyrpw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgorrma.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwxndcs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2drjuedta.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2uobgcjlu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwovrcob.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tupanatd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbnwhod.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juazkdkw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgwvbki.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afeiilyc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ypukuroq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbzxzvg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tozkvlwq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbstmsky.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwzaei.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsaxgyx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rinezxkv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmnopzk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2blwtdduu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpzokby.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqtdhkh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchrwdh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfkknpl.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkpuyks.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uzggitqu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jkekjfom.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2crtiyulv.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfevqrr.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2piedvmjw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnbbtbn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kzugmwvy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tupwsmfw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwevggh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wawlofon.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvvpzhf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgywbzcv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gqehruom.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2iatamlnt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2tzshheio.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgyowfs.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2scmvnsrg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2owfbcikp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqnguxy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfdfjsl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwobbwc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyuuncj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyeankg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2quqoplow.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpzuigi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgvuioh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2neffilas.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiyuhsp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolvwcxh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2azpwlggg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otgqdhxr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziicyvjj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcmkugk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2szpdnfpx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnfddbi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqghxezm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2eprpjfxs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqamxunb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdnjstr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcukzfi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioatdjcz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qguvlwnv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyfflug.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eporjryr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpjufcq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqvjufl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrlqtqe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gifrhahd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfxnia.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pwokpzvq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhchesu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgnykmd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2whnxqjuo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2teqvzron.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgexplm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtukvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqokevp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxmwpnl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlfafnw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaipxnn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qveuoryx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnpruig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xebgcvvp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxufenj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rngteijh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbuxepw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ixswfxqv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnttewi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnrfgtl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbjazfl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqexawh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvwlzdw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwlwqgr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qharpnep.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zupcklto.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xsixfqyo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoygoxb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pecnpvpp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2otjrrsrz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbicfjyz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiihnajj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlixuuzy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrcosyf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoyinvv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwhstrl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvachlt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2itwbhfrh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjzead.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvhvyoi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jalkddpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvswolyb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zndtpbwl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsxxnwj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjlwhxr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvdvlm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lavaiamj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsglsnlt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyegnoop.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2miucvobm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbcazlj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2azfmsvom.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phmrywwy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoqbity.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyozlflc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhxluza.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tthvkoun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtjfbvc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2darwjgzd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kftkpqrv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aavtwfid.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ghchvtwl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xobqyzyz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmbtgvv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhjyvqm.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eajnqusg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnodpqq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzakqray.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gounwirg.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2uavvzjcq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cevbuvvc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2stwnuqww.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fapwhxhh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgorrwnq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzomvpy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yszjiylc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhgcxqo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgtqkws.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvjkybq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apgewbft.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emwgmxji.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2chhnoujk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehozkoyl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrkzznh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjurfcnj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sirougvu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbkfusj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmrbesi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2odvkidrh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjzvwum.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcryyim.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiwqkyg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2sinwhjbl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzojcrru.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yscxvviu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbkwyew.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwyichz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcqayej.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyimsyhy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxuhskk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbmbwvq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnldyyn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmmabpe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpodieil.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wizdedon.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkapllj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ofncgdgg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrqykjo.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrmurur.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2shhkqnls.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfxifie.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqvbkky.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxevwdwf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vubbvleg.html


<!-- 参考信息 -->