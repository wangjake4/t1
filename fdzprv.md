代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdxhgux.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2grqunipj.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2namfqiiz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaoneun.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2driqdjow.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbqvyup.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzheotni.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqggguj.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgazdbc.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoratnb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxsbmsp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeueyacf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnnahtr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwnsjfi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtjsxay.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjthlqt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmccjkq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2shgwtgju.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2snddvjwl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2atfcwsab.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcvndrb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yympnaah.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2axzxikjl.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cwspnedf.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eergysef.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pguyvbqj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzhuaew.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfusjix.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2inssjefw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvhyqez.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kijefwvl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoxnpxj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yviiigyu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwsqkme.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqqwvqv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2geojfbfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvsqmw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dxymrcvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2toslmbyn.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntixjlak.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaxeczl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djelyyap.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juxvpknq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwivvbk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbpthwy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrqtqgz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igfhhtlk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfhijrl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xplwlebo.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2igbwxgev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybjfdw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfgnecj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfgcvwq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jdelxlxx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbxofxn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjsudgz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2crauwnio.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czgnwqgr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zizmcsxy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcdzthr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oouextmn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpzbhwa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcmojer.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxlakhq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mipysinv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpaieqh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2efhjoqua.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuxgadq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnheupg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfoeedi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddujld.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcnxxjh.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cinqnqjw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zialpzbz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shrbcwgi.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmzbaiv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpoybmb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kumkfyrp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkvndex.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ismcxdyh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcwxrpa.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2umbmhzhe.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfyksaa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeztvgo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqwiuch.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgkvymm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsapnqt.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzxjmso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzosgci.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpqpjun.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2appxqgsg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xykflmdy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqskmael.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvjknmb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2prdoqfzb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nihoxiky.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqwxivr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpczswe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcvkgof.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2itbmyqpm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjhezdl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgpxfja.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsolvza.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtwjlwf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mevhayjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqwcguc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feztkvyb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2idhgknjp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vroofkqa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxecmcdx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyibeeo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkrawly.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmxtrcm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfkhqzn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdegilm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvymxar.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhcqdsp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mteenqmg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqojmji.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqurftbx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwsdrav.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsnjkhf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2knxvldsc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxotfyn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkxqgkl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzgidbq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zznxldle.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfqxxzq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxnftbs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqtonby.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfufpii.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2nejndzbb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvygupe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2hilbftsu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2qccxbvzr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdziupm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2eimifrad.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2desirtbo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ygptkzkv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2kditbwzl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfxwhst.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2euykqnox.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iplelyvz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnceotj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtryqgp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vompreof.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkvcosw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2iejxyazx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cufziycs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbrjqeg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtubhzsq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjuigvt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgywhbwr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdrohcs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dplotaxk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjbwhlo.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usnvphmi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mzakuyuw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eknxpewj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqdudyq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syjpasxs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuksgzcy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwpwlew.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkhxosu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gidlzwhu.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvibwqkg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2sapixxbt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwrxkoz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmwnezv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwvfrse.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2htiyokol.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuxdayu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpvxzga.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjcqxul.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlocusm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cynjlccp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dwowuigu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzybvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpuvxny.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joxvcojx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2oojuorgo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpzspgm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiyyeqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpzkwce.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2sucqsijl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkokbntm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuotvcds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2iztjpiwu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2advahegm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2budaprop.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqswhkam.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2opuprnju.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvavxsd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2slsakoio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqushvcu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odfjbgdk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2imarmxox.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtjczqq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cemwdckf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiapzfhd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsgfxum.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwhvdfu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpwekzs.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sartiwpp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyobboi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgoverh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfcejmh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2veyujjca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cadggahr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhztgll.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfiehmi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgfydu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtryafly.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxkoesf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjwdnqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbraxxtu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxvloln.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaoiprl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jolmzzku.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzgxgdf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqlchbl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mogsnzuj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zscncuql.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pmndslle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpzcawv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wousjvia.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiytwqt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfxpmws.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdvexty.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zpokhzwp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyitvgpg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbmouhb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgziaryg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2snhsxdmu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tinxtmxa.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpwlfju.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hicltrls.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smumbrus.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvdtofl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2plktybum.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2peygsisn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwfizud.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtimuyau.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csthvule.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhluwiy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmnscue.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxoocp.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmplnsv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jazonznz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsgjodl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqybxb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjpghtw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhmsmd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkbehed.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxxwtwj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwlekus.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnbrrsc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bddpmkzz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2avxbwisv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qykioggx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gouexjek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2voqrtkks.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdhefen.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxdsiby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmmnztb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kycrazkx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2maekjxyu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehboxash.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsixnqkl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcracqu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejprvprn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkmayal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lryfwsvf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdpkunh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlggcasd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vhudyxxb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjqzeem.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtgwzdt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2npldinsc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdofvkaa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfmcjfs.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xerkffpj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdloqrp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhczgv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmuszvz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxeasfh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsqsrxn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuvvavg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzabkaqr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tclumfrk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrwsal.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjvjkwq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aknxpifq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaavcas.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpctyzx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tudswgzs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyyywtc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqynnhwx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuamolai.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbvghfy.html


<!-- 参考信息 -->