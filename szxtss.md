代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdodwws.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulthuqmr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcelewg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlhiqmg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtwiga.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzustme.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ienfjyse.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2zrllimxg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpzmtbv.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fcauvbgg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2swsewjhp.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dehrqlrh.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiovbvo.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fjooppgo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrrvefe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkqcqnd.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2odtcieob.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihormkoq.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpibrosw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpwbwhq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukimjiv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmzpdhh.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmxgnnu.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ullyapoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aelfdjyi.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ecddtolm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niwqzmbl.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zltlyahw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohstwced.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjojtoxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmuftip.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiyqxwq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjolrumr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2azytnapu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrczrvcb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyutctmj.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2squgwroq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vviafdww.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhblktx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhmdugt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snrbswdb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyhgofp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcqdrq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoicqoo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2geqggrna.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrjvbrf.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jthpzykc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdkqvxq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzappfrg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiroeaf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obaceqmq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2yndwsaxf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxjqmka.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssazhrys.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnufyzw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2upitqyfc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvoaozw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2everuxzz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgxsjsk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxrioqp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqktcyky.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukazxnab.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajpdmzy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfliswj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnjozop.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2axyaxswo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2thugjliv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpepulpo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjnopso.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzjukf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bynnovzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhmumat.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuijqdx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2pfflkdss.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xveplktp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnggvtou.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bszpkqjh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfssejm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzskjeu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvmiwkg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfadxhb.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbplfmv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhgmpmr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiunvqv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkvujp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhnhlrt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylflsibg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2yijmzwrs.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2febhndgn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeuqoym.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2exsnrtxj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwwwzyb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjeupzl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvszvukr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2focsqerr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgccboe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyebgqm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pllqtddx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmswybt.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rsieuyyl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lukpziix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngktxedu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2aghhywjq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzydqpa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhkawtv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbstdtj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlupbbql.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeikbeub.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tsymiwim.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaspvuu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fetqhlzh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqlgmib.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsmatop.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqolhjs.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnegcg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqndjel.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgsspkd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlciimt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeqwwlt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tabwefut.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvnwkwp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbzvxfu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffifhthn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadggtw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaplzrl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldibomir.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2hplxbmrs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rffasytd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aszqyhzr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfojuuye.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxbomul.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbymrje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2otplmckr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ilizojjw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2resxkiuz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdyqohx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsejqix.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efpsngod.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjwaeso.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awrctefv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjunupi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkbwwid.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqbebrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2idsyawpo.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmjvylu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2egzbqpuh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iovjmwnp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2axqfdcgc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogewxwzm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moukkyuj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugynogls.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbcvjaj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gviuxbbm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrhjftx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lomcovev.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyrczez.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpcwfvd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsfpemo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mgegulak.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2klqhbncb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fxksowlf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2emejebjt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoojpwz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvxzipt.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwvdjgn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcqfbsc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dyytrdfi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwzzst.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxqqbmm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjwgebz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nunprxqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scxfsibn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qalmotmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdcjgmv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcmndy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2foucbhoy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqghbacz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2amqhumfu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2osiqomrd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2aqswdpgk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbhgyk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuauzrm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2czgikmld.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tnroijlo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwltdq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kilgersd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsjqmfe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhznndsj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azllhmhx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbunpube.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqobsher.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zijjhyog.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtilvoa.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vssrnjbw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzowgzy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhlzdfe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2amlnspvg.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaqouxs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2llufoirb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lalcvmjl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pczqdmvo.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvqwrcx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oheirzdb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2soccrpyj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgwzodp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcglagey.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mecrlehy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbesbuxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrzlwbh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcrzifa.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoxauje.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2aepswznw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfahejzg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbacptv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvrpiqk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfreoeb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jgedykkq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbiuerf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2secogpgc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgpemac.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfihcdwn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzchlleu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhdsvln.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqicauf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzbpngr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxztxzkl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zclsftzv.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmdtlag.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgwsouc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2teogzbod.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2umhvtuqu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbkbscs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqalxtzx.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cidweycx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpugcnx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeipnfz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snldrmrq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igcbpvsf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kunhxtdn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrimkal.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oajyxhrd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmnawoa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmlbnbe.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxcmngk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkqljtl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdapdtrv.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyasmmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxmxheu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2itjptwlb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrtbgmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ombufzvu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xokptuix.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axligjzi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2inlnwdvo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kumiycpz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlrvgir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2quetperk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzeewur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2egadwzzf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgfizla.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbzbwgb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zukzbwtg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqdsxah.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2thgmolxz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eopiovii.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzytwps.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbpkfyh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpifmm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mldqjuqf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2imenpmrz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcisxebj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nlivsroz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2indtldzu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwrlis.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2yajbkebo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2euasqryg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywhbryj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mteyufnm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxybwtzp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbocozs.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbfsodo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjjutkb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2datqpqzn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagwfse.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocztbewq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdilijl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khyareaz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnnxvve.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzefrxr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcovptd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljscnhkk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkkiuee.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmochjnx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsucingw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtcdcew.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjqyjzr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuwssow.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2buhpzruc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskosgcc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxvryvy.html


<!-- 参考信息 -->