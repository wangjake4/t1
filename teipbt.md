代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzqkkvl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqipnkr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoqlqck.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oncwefhh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoickrm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2huuuqlnq.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2risiqcfo.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgacnqk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqogdnb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeqxhfy.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2boqercme.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2einpwlyi.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nnicoiet.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgjmdzd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldjrtk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjaivxe.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2eugtwixd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdqlzk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlwzbwm.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pirkubfj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzcwswt.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfhvedq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2roocfrmx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqndmre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbruuow.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwsvmoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwtmrwp.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tspapjuu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsxtlff.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjfeayv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmmkrxm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owibvgud.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjjoxji.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkneqmah.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnyusll.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahiuzkz.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2synlgqdj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2uucitlsb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdmulgj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erqqjlba.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gziwfjms.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2upnwwjaj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtebqals.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2syexpsfi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxthzlmn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyerjll.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqjvzyj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpjsvza.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giffgold.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hixzworx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmwstdt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvatuj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2klfnshwm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuwgvuh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aymxifrk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbckjvqb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzuyzkn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrajtlro.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvzqggo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkbtzzu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pslmoeiq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzwulut.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxqdwyy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqokkkky.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmehwdae.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzkvsda.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2efkdkdxa.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfszzcjs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bnorwnlr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpguoksh.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ntldzazn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2efybzevj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yufkedzz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoaltpc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbijwdfn.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmursxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpawwaox.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2guljvdxg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwqamhj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aasrpkkb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2swsaefyv.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsntqoa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2eieyzjmz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdforych.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hieruksc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtbxydc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmiswue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqduwvh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxnzmdn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpttbuc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2imflwfwm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkvzzur.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuegpgha.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfgzfnm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgoyhzh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnkhgne.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlyfit.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mejjuapj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeotcrti.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkexcnnv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlycrwku.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhngrct.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwevivo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfhyyhx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeazdvho.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbtrjxr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upblewwh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcebkrg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjhejtx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgbwweq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqcpygn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxktwvl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjowpvw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wscgkhnn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqfdghk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgftdqu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxjwyyn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hetaxuhb.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ljllujsg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfboyoi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kymdfcpg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrzylr.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2swgwvltt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2slvgtxhp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcrzker.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqctxfti.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2sycloxuf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhedzjkc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsgamg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlretvmc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwykqzp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyacozb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2peujwesf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrpimvo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaapsgb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdoaveg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qntvvthy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsuqvdu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlytsgkd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmwajru.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzunrkrd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2okbkctfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuyjtou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoevoar.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rexbquhw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcrqpkm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwqiuar.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdbhqeo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rilgdbim.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrfgeas.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhzagkm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsejowo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwizflpm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfoacmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiynkst.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtzqirc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fepssehp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewafziii.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eanreusl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fikwuekj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2attuawue.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqphuvz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrormpd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpiljfz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2orghuldj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2muwgivso.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yotqmndx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2telvzadp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxubem.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2plzncjvt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtyjqia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jthwxliz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ycekihyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eswappgu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2psumgjjc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhnuxyn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhhcxaz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwttdkgp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjxlqnh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2rckenysj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ligurgnl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckepujyd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzojauez.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ikslkxaw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2irlukfmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgxynu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbzqcdf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ercygokt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwzkkai.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbvvlaj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmujhihx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkukoxo.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2siqgceqx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkyiqye.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gieckaga.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dvllplvk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrryats.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvcwust.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnejgubv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlobbya.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwudzku.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeuxmjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiesyws.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmzlnud.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcjdqpl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbvfgak.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqqeyzi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2izliurms.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqhexcs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdvkakw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vlreiogo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dglfmtvv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqlroxw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxydutn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2focfmdjs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvcyrmi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2szpfwbaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bsteaacb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulodmuhy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoblwsg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtgnitf.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmholfv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2afjvzcua.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdcfrcy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2siknglmq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqerfueq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zomshxrf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpyeehq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvyrrbi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2cozidwyb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrxyngf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsrprex.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlwufde.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayizjowo.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpxqulq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvoigjk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kguntsqy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2slwksqqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgelhxa.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2talndfeg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yarwshtp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mopvfbzv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzqscje.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzicdtd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcsmqvf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2huwvjzxx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmszmzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlnhqvb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awirqbhe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qqygdkvl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojidgqxk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgjgpet.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iztsjumw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwcmalf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcctnrmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcbgjxv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtukrqc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvprxtky.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqxxme.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjmsbhh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2globbftw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjyjqvq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sctfjikw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rafcllhl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmxhbxw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wekafiwt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjtyakk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjujonoi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxbicdl.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciawbejs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2omevdwsh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2crzlfmzr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2itgmfmck.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxllake.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hlozhemf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlghukbl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzredpu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzqzbao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzufybf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpplrwn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwstsvr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfzdiln.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrtsxty.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkipnev.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcnhgxh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2erbjgqjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkframm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2symyjtou.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2iueshswq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bswkmujw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvweubgy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2icsdzfwm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2goioplcv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqfloow.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2souqmpjy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjludxv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rouegzpn.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvpkxop.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eolnpkbb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcagiwi.html


<!-- 参考信息 -->