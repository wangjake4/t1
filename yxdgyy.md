代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqgkrpv.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvgjxlo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhpqmnv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbazssz.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhowcns.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2qmygpvdt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmpduca.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyzabbf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnfppsc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjsdxmh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqyrfke.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrppspm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2edsgthka.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhykdzk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2pawmdere.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2mzohmytl.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2aezksrjs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxutrju.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2syvzmrwf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrzycez.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wspkyaen.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2epbwmhru.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sujiyuyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjywmzz.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2bscpfjos.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsodbk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2oprogezf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uueatxqq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvdsgdx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aciucvxn.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpwaeaz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpsebef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqdwofu.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gegqdxyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlghjcsy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khqpjwti.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqxhgvc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oahxnlfm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtxezr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiawsuef.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvktgtpa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enhyjfkx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwdwoag.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxedpph.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahealebi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyzcziw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjoxbyo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knikcljb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtmyosa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2velllmie.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxjopuj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2utuwivdy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvzhrai.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnlajzq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhichnh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdijjyen.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvhqzil.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2singtzyp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhqcwmp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrtsmt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxjvqfp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtpapgf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrrqcb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2npxxlesw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omuopnkk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdsfsey.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tszcaaod.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvnnpyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtyzyt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrexebk.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwsaeyr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyixhlmr.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfogabod.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbprpjt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtatwdu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvfqpri.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkvgiay.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnlpta.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lanpzoqp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2babhabwe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwpmxyc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcqhsho.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstoewnz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwveglka.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssahzbtm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvkzhao.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2csoqcvnq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntgqcy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzkbnpz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlpmfg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2webxnhwx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atfnemlu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynkcqql.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdyezej.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoygutk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdczelb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2txnedcri.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvwriyd.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cltcgvjx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwskeszd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxkbgqx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsrdava.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pddbwgfm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbwbsmi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdyouao.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zifnfuvy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmseeoo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwqambl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxtgmhn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqikjf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxupqzm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhepwhu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavmmar.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppcouly.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpyoall.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoyntiv.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2owhopgte.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ferscmsu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cwitwmyc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzlpkft.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2thphdpfh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2isjngopt.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2edagxsjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfcfapn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bctscyjn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaggrmc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2aksjpftq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2piacxolx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqzexit.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2thbddawz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzwmrir.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbodow.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivopyjjn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qptjkvnt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrrnurm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebbpsj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsugjjic.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2woompycv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygfzyy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yerlvbog.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephhyamz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeljhee.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyemvtpx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhppqct.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aswlnder.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsdmgui.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqocbyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmjhnxk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsyeuwf.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpktfz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhofesov.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nubfwdnx.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osmknzmw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2izxebqbs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilphxawg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcujls.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfmdwfa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogybnfqy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfhpuxs.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2efhzkxws.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkgsrkr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvgqak.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrogfus.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyinqyq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwmppkt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmgqqzz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2szkemqhm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jomlwsyk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2puireilq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimrqptb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2erlgqjdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yltcgpei.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2milrevyo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vohtjuxg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgjnrac.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sedffxwg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gganndam.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tupwkjth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdktfrbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgesvgw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyuucvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwluahk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bllvluvk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjbalnn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2igeumbqv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzbyfhw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhffmqil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmthvuf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mplmqaue.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2magvuvwo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2arazkjbo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjljrgm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuibrcz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdwccse.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ladlypoc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhddalt.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcrpngr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vktyqfnp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjalwqhu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjhyrum.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lozngvmh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuxkkqh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmjwjqx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdyiqi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qujkqcjb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvlnlil.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibqpvra.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ystgveqz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjfvtvk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2egjmhwsd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczulqvc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pltobcjq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbctrqx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlooansu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezevjokh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2drpwdcks.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxysnmuk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hikzuyqm.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmvevcg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmehtfu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahvgnfm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdicetei.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yohruser.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvecisp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yubruocl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2khmisqmw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhvbbhb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaksbjw.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoyhjha.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2valkblki.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2omxijqvv.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrzrewa.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mshpnaef.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whdoovfp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjeehzj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwelmrlj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmrlkjn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2auixbsht.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndcocgb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaqnigb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjnwcd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezzijxw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpwhemg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2raiwillb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zweijway.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpngof.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfhkhit.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcktka.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfktmihi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2afixefmd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiqrdbu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mludbbdh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqgnjxp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmspjw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sekzfrsk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2llcjgkpi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybwnkzh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2noafexbc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiprvqj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxuihke.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpkqgjl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tegwszrz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvyzdbi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqvhurf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzyqpnw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yytteqdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmdhrlk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxnpsvp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwwpucl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqgggiv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaivzow.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvdbkpa.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdomdvj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2clykyqzb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqmamvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2orsnnhid.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiybxqv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsauyfa.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmmjqso.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqafcsp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnwlpb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnlilqg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgvsumr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmtiidb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmwuzua.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfciysx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwmder.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbragmcn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqhzjwe.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkeeyre.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pucdrtsk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpcyhqk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sobcssoc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxjelh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uunuxuqe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzyaohe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuigodh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eekbxsxg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxnhbgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlehyyht.html


<!-- 参考信息 -->