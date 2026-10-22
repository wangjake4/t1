代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2wkphzyjk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyzrhsl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzbkffd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoithidv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyztqnf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzcwlkr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dcajceqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2zslaaapc.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kaytxswq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkaszsn.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctakepg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dswbhqfu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbgyuug.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnztxnc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzniigk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgefpcam.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2eltcnpsz.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgztdwd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2omksayme.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvctltrt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxbxutc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qicjrrjo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsblumdz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omkmpcky.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsasjnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkmgnjj.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2imezzqtt.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzsokmt.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqycbfq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2czwszsev.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lslsavtu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzwhlxb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2knwrzysc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaetvdk.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbphsdv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbwupnc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwohyrl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrcfxzj.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2btrbrkdz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbmjzff.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiwxbml.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnmtsdw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2uehabbaz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfpzikr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbcdhfx.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2knexdxnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmlypjm.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjfhssj.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhxislu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcmxnah.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwacckvo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duiahyav.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfszytq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcyuafb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtlpohp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njeclvep.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znwcazyw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2jneditoq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjivhqyv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhloczdg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevuaaqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mesghkxz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mivbdfpu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iargagfj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpfnpbp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swozoewu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdgluml.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyczeeg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfneett.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psxrinyd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjzourf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrzdemv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqzktkc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmkvmix.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xydgdpxg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzlgzov.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qztmwcqm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fphowxac.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpclein.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2yqagxoks.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgcjcma.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rppkycpc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytahuoch.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqbjue.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezysnydt.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2akclgyiw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjjegfn.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvkqanb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2umobhxsc.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rivfverr.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaxuqpi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gvinkcro.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyggltm.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2aepmykyo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xislwzqz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxsobfj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwrjnic.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmwbdis.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksipqesg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvnzsgg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcxqjre.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2amrdottw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxerlusc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhvgdt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpxkrpu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqliogo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzertudh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfyeyud.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlydcjln.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2blraiwgs.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjjzho.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tgawfyky.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwksdmo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbottpyc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnutekm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvcqmhl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyroenpf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdubikh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqngcnmq.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtnnlk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnutvdiq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdqzor.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdpxbws.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pguxipwa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkltgis.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejttbb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzbnxni.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkzaowq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fyshxxjb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bcagebls.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qoburxxf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dripsgcg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2llylqisn.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtkxszp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bddirbzm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2qtghsdee.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvvpjlt.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2djnrrvuy.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2umpregch.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakyutho.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nipxrdsn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hibnxftb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjlxnzl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmvjwes.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ansvdmak.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvtsphy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwdzbm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyhhyjx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwepsomm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dijaixak.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbvgtkv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2eaulvtha.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrzftqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2njikpbav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmhizsp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsewgib.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsapsqcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpvcxai.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdpezaj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzxhaix.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlecvje.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbtgpzp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaqejqs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqowblji.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btstvmwu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbfehm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzygkha.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhjguuj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsigksw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odzeknqa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iawnfyhg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrcprot.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdntidha.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acktepld.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcvuycv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fggnafan.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyjuzkx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsygbrty.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2viptoxal.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkhsonc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmpeyij.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyuxtis.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvwncwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2foihnrqh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2miypzagn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnnwsmf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lbavvrcg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyfjvdq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gktwmrhz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubeemo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqqiibs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2socvywcn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyiczcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2docvttgp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyidper.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzmjaet.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2azgimjce.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvayjzl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbzwrmc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiuulpo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwienjp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nljenepu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2otorrepw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjhfiqk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ppceasah.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnxxixz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcblekvy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cspxspzn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxayjov.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zibkaovl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywijijg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbflulr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njhgslmu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2widajogz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyxkfsn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2teebddbn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kopswbuw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2omcitvci.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehpimjq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rztqqqib.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxzylzt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjgeyvd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwxqqxb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2voxfinbe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gulnwrrp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyamuoi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdhugdn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2apaezrxu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerksuwe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtwrxty.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbskaso.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmwhozk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkixcfv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuymmss.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfomjck.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkgvov.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzdklyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjtxseb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xniwwhrv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnorlyu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpidieid.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvubetx.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwkluo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmpqcf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bftnrvbb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzggjce.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qjunhjee.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzqfkjh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2giczseou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgasnfkz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbklkemk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiidxpga.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjvfmkw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrdvckf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqraddh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgnnxvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaejpqdt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yggoszjg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqwfab.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2slpkgjup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpajbev.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmskecei.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zecaunzc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfbvwre.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvzwjfk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpzwxqt.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieczqcuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wovyshci.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdztxud.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwxumfp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nspnfoqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwknepg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdowxtkt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tudfzxqx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tivgmdwu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2drkcrkcq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkndkaqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxjyxxe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2laplpuql.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpvcycs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimiuiz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhehfhad.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlhbylu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2orzllarw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhymlztp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzhlbwq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pevggvsz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmlptqh.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaxqdyz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrucrwaz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmcdfag.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmgcmxr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrbqqii.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2szfdqxjr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwmrkbw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2szlvzbyj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxxgocr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwbhrxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqwitbc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qadrhhuu.html


<!-- 参考信息 -->