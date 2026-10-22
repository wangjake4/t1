代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2haibzjgb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdxblxc.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgawkudu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qacnagks.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjamxaf.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbzkgja.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxderfjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugywbcbx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvkzbdl.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kihgxxoo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhjlmvk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwandhvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxmfkvw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohixxhqs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmiivv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxcwqiw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzmbadf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjybhkrg.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbvkbcl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxfdkot.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdezejo.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2muilsvgk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfdlmll.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoejnly.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dukwejzf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iphqnlon.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bngydhce.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iqydbioy.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsnrgkf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stptfwrb.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyvodru.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwbdccp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyenzmnn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkrossc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2rltywaqr.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2felbmjve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwhlbv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cttzkkcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqrnffq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrxlld.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hoffgdwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vodqccsd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlkeqks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bspyqiqx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszlpbkb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emowiqfa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdjzvwq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nldyufkb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjlyquj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2aqohicue.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzoxivi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxzhfzc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmvlncb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2egxkqhzb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqhrvbo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkgnpss.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdehiqr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxduqcs.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnniklg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olubhqaj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndywanpt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2noyeilcx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apsthwzd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsishqna.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzycylj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2xojuvunh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyxbasz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvaanqr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrcxun.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvwzsj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2czfsokpc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyvrjem.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjqdptq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvdxkxd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzeejl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpgumet.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2potolefs.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnijcaws.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2papuadyq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2injqdjao.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2irhqinxr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2aivpsohz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2govkhkew.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmcxdvb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dnozjvdz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjxtnfu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhleucb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgspvqv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmzckyx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vykwjltd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnunaqe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqznkks.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagbukkc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadjifl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2imvprpfc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvqatxc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2yygipovc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgozegxv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2exlfyxlo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpacymb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxzdpny.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fljqxejh.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfualkn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2orpdmqst.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cilyacqi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulirvcuh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrckwjw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2chzdmtzt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcaykyf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nljlhdai.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muesjabx.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsrrtkv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzbejqu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwyhyjy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2njptupoj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvdnklk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hebmgzef.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkspiygg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujteiji.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2obxbrkbb.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgtscla.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxrelad.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyjnbcd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2llqiyerh.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkwwqfi.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwbqzfg.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fuddwtrj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgsphpb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wulapkmb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jwphimhg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdngyx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2syugusjh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zznoepho.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2disntecq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2weyvuupj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2tndqllcr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeqvqtf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2szsduujd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2debsqtqf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2libxbtxg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyarnbso.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2degicaaa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcdxohm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vyljaiaa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2zerbuwlg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bsacbtbh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxgcjma.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2oumpuyro.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqmvvxg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nraqhtln.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsvfeie.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizwemyq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgozwmpy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2esclfiir.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhejgue.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2izbwllkb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eclkexik.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hynkrgps.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkugslym.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziotddkp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdoyqiq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkbwcbx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqugshl.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2upnfqogj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2vulezrxt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dylcwbng.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyozvkh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iybzqmrl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaqvxvp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syjqndye.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mgulhiii.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedkwei.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvodqay.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnxneke.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoopizh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jdynjqju.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtjxems.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jqizkybk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgehiru.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzctijq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtofrfb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2guftkyuu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjfhdvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvemnxm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvcdhbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dycjdesk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoukgfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeyvzse.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmangv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhlueln.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfylshmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xuslkfkl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwntqdxo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gevfaxtr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpjnmcf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xxourhic.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyomqpm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtntgbq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yugnnrwm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fifypjuh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijfmytu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjzzrmh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjkybws.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sniuixdz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwmanaf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufremku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtxdobh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrfqfep.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlitopc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcpxiu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaemrns.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2laomnhle.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjavijhs.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqxniie.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvcnezq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeevpbbc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wncdygnz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wunhtszi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2isljptwh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjqvlru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuvfzvn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khbiqdzx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxadodun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsjfzew.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2szaguutf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppilzqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczkvei.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaizhyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxxlwuf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtnwart.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjhizxg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2novgrwzm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmvsrat.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeioflv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdjwyqo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhitvazb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhatka.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiltcqb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2euqkdbfk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeyjnxe.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqtfzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsdpdhn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkajkrul.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evzxjhqr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjltkbj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfadffk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbftelny.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmifzwls.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcihagx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uivyeuld.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjpbtru.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyaujlb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2brllfzzg.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgjhzzv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfqhthh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfscgkql.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqlypbf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyeatoe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2opcwmymt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoydllw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hniqasan.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2saehbokl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnknfpi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2amtwjurx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvmbcbk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiqnclf.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltevbtfi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jckmvmol.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgxxeds.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2snqnpizh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqvesnl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavejczq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lijocehz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnryonj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkoiiaa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvgecvq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfhbpcm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iadyvtvs.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tphtpqbw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuzdnel.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfkqvet.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsljnzu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxtutvf.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxcuueo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ripyudsr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2peexhfkl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2aximunpv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkaycgx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nanfkymh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmzosqn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2isxbokgd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flecjcjy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgctmyml.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kruywfbx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzzdfyq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrlgoqm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2trcbkueb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xygvpabh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btyafuoc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qozekjoz.html


<!-- 参考信息 -->