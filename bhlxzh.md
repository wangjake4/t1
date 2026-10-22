代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkjxesp.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzwjyfw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjgryuh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyecxhf.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ninmporp.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkalyak.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2aykoofrp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtjspic.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvjixsa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnaesye.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizkokos.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocryjcwc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbvyztb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtomqgl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2cemefeec.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffebbyvl.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiusnwc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xoepxvdn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hqttiycz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvoenvj.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fuomqlcu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lamklujo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhpdlbf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjqioey.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwuenl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwtbif.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyyfecu.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nneyszek.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggctyac.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2heotpsur.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2psxlzcke.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoljqyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxshgmj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtalxpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jenymwch.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhndtvn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyxojrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlamcleq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjribtj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpzubxc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmezjar.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfstqu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlljrri.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbwhppb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzmrvvm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bobuyiav.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdkyhmp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtaqyml.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbgbfav.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2awrycdec.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svfmmuui.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sshpdkip.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2efyitzfo.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxfvcsr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmizbwga.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqpxdtf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejvgjph.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afgqhhls.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abxjcful.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuotmbq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynbfqu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvcdbfk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxraidhn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2soassner.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2shpvfidt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpocnwhb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoqmxfh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2awfvkrqg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfbfluz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2julwrcwf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtbgqyp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vthamapn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqiobyn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttihxbyo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yaulyzla.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2emcwpfdh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dulznqis.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2antwdqvp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcmgyke.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnozjcx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjnkbld.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjbhurc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjwdnhp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdskxse.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmapqtwd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovioolaa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaoqybx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittkbpoj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhynzjz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwappuov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2gijekflh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaxqlvj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2cymbokwe.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2agoeimpu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuxcent.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwhdvtn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcvbzmr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgoslfs.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyutuho.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbrtoyj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuoysv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfymiz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eilygjwh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wizsnfjx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcglwuld.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svqejrii.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyyhih.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaadqpp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkavfvtt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egueucco.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2traoskak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ohehapez.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjevynw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnaucty.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuadhbqm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2meopguyf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qtniluwh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2gszddpfs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoqbmwv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aamodudq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuoantt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kihvxetl.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmehmvv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2yrakpepi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhjqjh.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgndlcg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2oswdbqxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqnxvyl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2upnnlpwj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfyejii.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuvqooi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyjbozs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2neieresy.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pykrztxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhwtabb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkgxkoq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtbzdls.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbidkxt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2flzqbhbm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqfqhdk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrvkud.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2soejiuwo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyrqpbe.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2zshnrgwb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzbswin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgqhtkw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbutekc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zonrxkxb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txdlqrbq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xqamggid.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltghwtno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqmyrjw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjhmtrq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yzracqfn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zdamuzim.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqygtbfm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isbdjkih.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlszgegn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxyjfng.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsdnhyj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gogdcuna.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaazevuu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmuoean.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqsnscv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshfnkq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkohviir.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yeimaoqr.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwrzxfx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2inectvbb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhrplvc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnaopro.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tidqrsuf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2byvcpdhr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2psktcqfv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eologwnj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxnfrxz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2inldmfxk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezifslod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avnttsqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axqaninn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqgzyjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crurmtzh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwdgxff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2olazjtjy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbksllaw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvmwyzy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcikfyiw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbkphbe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxifkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdejllo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hycoqxxr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzfctqp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ojivsvev.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzuggvg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yansqgtc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bonwedle.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbxsmop.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swudcmoe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaakjfiu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srrtfsyf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqbukqy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmplujxq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjklknmg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2isoszunt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzicpteq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfweyflu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjnincf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzmydma.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2erkfeooi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htbjokhb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2avexxlte.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrwcuck.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkhpdbs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdnqqod.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqfxppt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2scanznpm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smazpmwo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaonwcjv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbhsncf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dismwgnj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulejpils.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyfrjut.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gblffoqy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwnadnm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mavtdjgt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqlekhy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmouapxq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tstigtna.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imhsnlvz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2irdldxsp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2twytbyxn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhveohwg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaiughq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoktaoh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xexvttgu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rolcbsqk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgcqoad.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqenabyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2erpiermy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsghvsqv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iowmbyhn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazasdar.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2pejoncby.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ownrdihb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acnysfpj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qonczfuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2boraejwo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kolzcikg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaydwby.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nourxwbf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqndzvd.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgugnya.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrznfal.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkenzwa.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfinovl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrmlqul.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmffyd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkeagib.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbrjkqz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2bunpujxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvncolsp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gnszrpma.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlabpyip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfiybhe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzrugqr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtatoww.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2duclfyho.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mljdghug.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tllrwobf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tceeadob.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2clfpepjt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gysylmgv.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ridwgkdv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zskgualc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwoidhp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbczlqx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqahlnj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwxdvrg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xromhsqg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcvotiv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2maejkaxs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxezfe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzwpkaf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjepxja.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjkmhvc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykrtrfp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2otfkhcag.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjbfybe.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iitrbjwd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdhmydx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhyiasz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kagufino.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlvikgf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqumxmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxbfwvb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oedjtmfh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnmbyqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrucfnnv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqkxru.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfkdyym.html


<!-- 参考信息 -->