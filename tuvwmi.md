代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqyuqqn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgchxpq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvklmygs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mszcxuqk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmzptm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zicknkvz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zoupccqy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2gthtndej.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xalsfzpm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgemyvfk.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdquzqlf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtudlsi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilqpzsa.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnlusvp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqpxmqk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejonzio.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxbvphk.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjggeud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2oigjtxtt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfodbdzb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcjxxnw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrhrifv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmnqeik.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xckzpmlz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyehvtl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhxndcm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2slcsgjtg.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkavdjv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsletvl.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvbrys.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2amgvblwi.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2igdquwuk.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvwthw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2elfmsiyd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwgyavy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeijwmg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xumoqosl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppymsofe.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpjmjxs.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2auzbqfug.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2chavvuti.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpgxecj.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhuoryq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbbbmol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqjovwq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuckhhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamfpmt.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkstqxg.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhirnbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qleambqb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmwdjqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkfysrh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taybbjzv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrqqgow.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmqmwnz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dajfnquf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnijvbt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvbjitu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asdmlqvi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2empderxr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonfvldc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkimnwx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txwmhxyh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2chgwzbtk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txvcbdcq.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxdajpm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlouzpxk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhyfqsd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyomoyx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeajubk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swiacame.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrungdz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrfjgvn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ooclbgww.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoffwub.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2edrrhytj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrdrpaj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzxdmtq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbcarx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzoqnuw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkxdzzh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndetxmu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmliuzyr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2yizebrrc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaplzgc.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzewgkog.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmpiiuk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hirvmwqk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2czghjhin.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2srzvyfcl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgnbbji.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mjacasxp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbmmagy.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbrdtld.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqaqhzm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjsnnhb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufivfldo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvbfjnf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzfdhmh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjpvevf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqacjcak.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2pimsdmai.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnqyuck.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrodwxa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrqkhqr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhgquim.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iohnbhnw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2epocvhyo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrgwvqv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tyffpodf.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfdermb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqeztgo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdggkb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cerixwmk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frgfgemi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zavpzbzf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbnqsol.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uinsscyu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxxjdjn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ubotroht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byzfpjth.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdaludn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ozojbymy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rarndcgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaklnhyi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfpzts.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpohpqj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwfoexf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoznmtd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2gxynodfp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2unguxexd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkabcbz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2piugkqwf.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mdohugpc.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yecdlffv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzglgby.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tkazeupj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2erahszxf.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrlaqhr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2obkyggsr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcsgdds.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2linrecmh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvjiwa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqwhlwk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmqbmay.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnfbxex.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2dahuxzui.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zofszhvh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2todjkdyz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bghhgtmx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekgqmc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrfremj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvaehab.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvningg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwicysen.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmgadag.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zljniitr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2defcfrhf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhsmsbw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnruvlg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtzuhkr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgnswld.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkxtyy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwhqqfe.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kduylukd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2frbvwwzl.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpaenee.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nctezfic.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otytszra.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpiveum.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgklcrm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2apwmaomg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgevwkz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2goajaewf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaqhdos.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zubvfomc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyqbzfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwwyaqa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwxlfin.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfunjxv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2awlygpto.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lznvltis.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2avlfuvpl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrlewzx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjotqoss.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mbauecij.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2prtqbrkv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqagfu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrzstpv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2abnettky.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clilhmqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzekanzp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fotlcbkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplsdav.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhldxaod.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdnsvfz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2crsnfixx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2joobrtqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvivawb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlcnfor.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfobyilg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxdfecv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpjrtuj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2itbzvizt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqqcnav.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhjenam.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqkfil.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qikpnzfy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmdfmvb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukxgqr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2liutbqoi.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdsnqag.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzdloin.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgvcynv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jumqeooq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wskroant.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvzoomg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrrdmef.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrijffo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2navmfyxh.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaebjmx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyndfud.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxygsfj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbtojvz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2icdmivrj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgghtpui.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwsjzst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgwmanw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnedewb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhengvi.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xanffiyk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghllua.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuvlqbu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxbybir.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tterhyjh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfnsgri.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2svelctxf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kepnnqdo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiipisrh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjgrfhq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemmxxns.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjveatmf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yoosjtqk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbafrnx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdwcrqz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemsjgms.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2smirfdoa.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnssjsd.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyqwrev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2komhjfoh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnhclzi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihldfube.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqwjvlt.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iebyeprl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtfibue.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yaepudoe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lacqugaa.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmunyydf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoytimi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2agshsunp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzdspai.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xylrmaqm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqmjusl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uriypshb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icahjspw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjvoko.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2njhkqpqb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxwwwki.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbxpxaw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarxxto.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeadkgv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhftxylq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufforehm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2scdrgcwg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqubvhj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2exuwkqot.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuzwsky.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcnjral.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgkbqvi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvqxith.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2itgtkpig.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdipdezc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpswkuf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsjupgb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeqtjal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjytzqk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrnegwk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2amlulzjw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvxciwn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmrhndf.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyrshhk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrfbave.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrhyvco.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeafquf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqplzqs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jshvixpr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2blkqbmff.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2connthnd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjranhz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2arlkxxpo.html


<!-- 参考信息 -->