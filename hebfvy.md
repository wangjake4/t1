代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2abizmzbz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wswgirmd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgyywyd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfdauj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2usddqjtu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyzfiux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pndwkyrd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoqmghf.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfnoilg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktisgd.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpkgbrg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrvqauk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxettmtl.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhparpw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcdcvcd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2lekooixt.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmiscxd.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgkkfud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2kizulxwm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmpmncj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmobojyu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjhtzxh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfherwr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqlnhub.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqlvvtq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzifemr.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jepbcfjp.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2oedficjk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2kehqqedg.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2drhhmnah.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2avujtiez.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sslqlkew.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2chndjbdz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2teorlsqs.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2caxpnbht.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2shaomuar.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2wypefwnv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyrzwzv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vefvzrqr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjvbqyw.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrfjmhw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbmgeev.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2aifgfrtj.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmnepjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nagyyfrt.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvxehsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlueikk.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbiensa.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vffehgqm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbcwrpz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alsnqtpa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsuzovt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucjlije.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kowejwbd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpxisct.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripuyeok.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxshhsyk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2acrjudgc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xztgvltx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgrbdxh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmoxmr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pwofrjyz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fidwxwdc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxxotqs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2crwfiyqc.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2quenuawx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgmecnt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2keskoaui.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkylitb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bydbmeru.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcdihly.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2sysofdlr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpipeug.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxyxvwz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshufko.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwihgpif.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2irjurabr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpycmzlk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ydysdlzo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgktyfi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpluxwg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2essitooo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxccnalc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gavtiags.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbexwwh.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahavciba.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwebspc.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jledpfsh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkxfcmd.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2drcyznim.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vooaetgj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcfblz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rmamkiag.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2qctawxbd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdscnei.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdblcgpk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvepneh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdbvesj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpdbylm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdtzzla.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aveeqefz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ezipqnpv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkqncgm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eflprxwb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2awheyygz.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggnpdwj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuhuhdo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2bditilqm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2uodbxzlk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rcelewri.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbvhevb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2xhndztrx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxarcj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvzeqxo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxwnaca.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2urqvsvfj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbgppn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjevajwi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvhzdsb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzcoutl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpfeueg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tubcayyq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2llxgmpao.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vllimldk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrajoyf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qloquhki.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsparemu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wifnoffo.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaffwgg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2chhtqylr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2xywxvvrd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjeshfu.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dslzcsuo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqwirg.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjorvpv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuyuobc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pixphsxr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsedjni.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcpgfou.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxskanqa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fracokid.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvltszwl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbkbjie.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxqukwe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwfxuki.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxaosmm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqacexy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwpjuct.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaucgqd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakzact.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuorytv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsbnuqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbluhctp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2cemxnzgg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pauufmdi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yauzfwpg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2adzjxwuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvbelfr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fohyjerl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alsiwicx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtkzly.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaeqrmz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2govntkyn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2foalmkcw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isujpyqw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhrojyo.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzskgyhb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaplrqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atfrcfwj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkepqndu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmigdps.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfccuxa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2awunbihy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2albhxwdu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xikcjrrz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcophyeu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poywdvee.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxumxsv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnqnfhg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zazpfqbp.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwfrgvk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkynqsn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2loxozpsj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmpmerv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tegberkc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvtmdet.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsocqgy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwfywki.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcsduar.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csptpmgz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsoqtkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbzeob.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxjuwdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoaywtp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlksuvm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xxppojzk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhssamw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2twoqaefo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqbtbdq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjzwern.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnolfzr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfsebku.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtwhfql.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhyanpv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kinytczt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvbhrem.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcftvcv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tofxljwh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggvqmxs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuhipdp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgnmbny.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnvpahk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjelzyf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsmdjax.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuspgrz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jctrsvlj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaqherq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gldsqour.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqszfng.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tplsrgyp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnkiqvn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2alysewvm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdmhqgo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2daxfjhft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxbgdv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxavuyhr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmypcst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyvpleo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dofirplk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqqbvll.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzmljyd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iviizrqt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2idnitbep.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvxcfrp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcubkgq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nahhxvad.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jamplbqi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvotcqf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2taiiqpgt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtelobp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzguwqu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2clkfdszf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oldemmqu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vakqzjoy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbaikoq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmsbjoo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mchimhoa.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkgucud.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwasryx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jufcqzbb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqkuum.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzklrprf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjdbay.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjinchh.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2yedfhoyy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpciydr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2alaslfol.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2njsttnjy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2voekxdya.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuotqwa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdauxrpq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbcjaye.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmrnbi.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnctbdp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqiqpu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fehgqjoe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2oymhltfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqrlrpy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmylfzp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeivxjw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijteynfl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzlrrgr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyxgtig.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtouzpx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfpifso.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxidqyb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnruljf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglutlu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbamylhz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2njyormlp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrgaolu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qxenczlb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2soiriugv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxifeodc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2falgvtmm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwkkomm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgryvya.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2epenjscp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnyacxj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pealbcvx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyinumw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgshmbo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdwbaxr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxkofoh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhbesnt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynozdt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjxotnh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2disjmfec.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsokeii.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hksdmhwe.html


<!-- 参考信息 -->