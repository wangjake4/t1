代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrphczt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bvolsmxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvykbbj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmsdvzi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdgzgrt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gslnrrvp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wjggxfkc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjpzrrt.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhlnnrl.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqxwwrb.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhlsite.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skokgiig.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuajpcfd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2nxldtnjg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2errftkkt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnpopnn.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2prtpliiw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2joqhguge.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdabwbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhvijyu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuavqrf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypascys.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2huswself.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlhjinh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrzsvls.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncqgqqx.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdmcqnl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2hmigdwzy.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2himkaqmm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzkpwim.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzvymu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbsmthv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2crphmpif.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fzejxkus.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpaqmlf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cywmthle.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2idhjqupm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoslwdq.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2omlzdfrj.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udjnpflj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmwirv.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xulzbrjd.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2orhkekxt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggqayg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtlrdwy.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oqemhnky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwnziaj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdpuhvt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xxajzfvv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfptbjbz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envrubud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qplohcsr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esldbptb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcgxxxe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfelfrun.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wewsanry.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhozeex.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzeehex.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbprhqq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpuhjen.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyljqsav.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2olbmeggw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqpwmuo.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2onxflnly.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwretft.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cemhynhh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohagafrf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icnpjkah.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dehxxpsz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwogpicv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dipslcga.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdgjrbe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzlelrz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqepwpw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gahcbbmb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qieihejy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcqjcsm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thptilsm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrkjutu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfcztgd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amztxadg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcyyzkg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyexccr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfalnugf.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fztffseh.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2myfkukqk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftezcpib.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2padlrcjr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2grdueidg.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrtqztk.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxiands.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2lawewzeg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eikybjwj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdrkpaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfsmbfo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2npkchvul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsfqhcl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybryfzfj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynasehdp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2noikfbkm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2umrcqiuz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xkczbugd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbhrjxf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lootfbvz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxkcbyd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdnjtdb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eblaeati.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2jidvokap.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsdpvth.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2orxmnwic.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjyptys.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhnqoyu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmukxgye.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcuceqs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emowqhqu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjzgral.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgjckft.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgigvod.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmqmpkp.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhtlah.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbapzaz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zczsehev.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zwefonky.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nkueaksd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maqpkosh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlxlstj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhexknj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2frntkylh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mevggsob.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvbiqdp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaosjwe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uktybtpg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwzumkh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqdsqmn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyndgfu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2szecghks.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkmqaia.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kzethndi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2crwityjr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gymidbzq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eusxismt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxckacb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpwrzvq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnatfcn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2izkdbcua.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyagxyfr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlitvjd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdpwgug.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvntpwb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwltdpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkkvwey.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rfylfair.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcxrttw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2buiepjwh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nccwxiui.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2igpogsea.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozndjycp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwtrbvr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqbiqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwuyena.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxxtsfe.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sgimmiba.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzpvpdz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyltmiu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2symffwcu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdvomds.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsdagao.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtihtzts.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jceltgvm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojkqnfn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcodrfj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xykhntpy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufquuhxd.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dydovbmy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2scsstpgg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2olymnqnf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdfyjjs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okoupeue.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2roeqylxg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqlbsfc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fexncnyi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrinsei.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2avdwqasl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzynodf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2befphcxa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2alzxxwvt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzlztoa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqdnvjm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2troidvyl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2faylyqdv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fikkehxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtmvqwn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrtcarj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqtwjov.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2juuivlke.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2scskcjwi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2inpussru.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybshdj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmpyprc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2eqavsmjq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2awbcsaus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vveekvsz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxtiso.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfilrch.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxvelsa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejttscs.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqztjrg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iutdrevw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmndvmb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpfdird.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmpaddh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaoxehl.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxyrlhu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxinigna.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uihvkeer.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaqmvqk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2arzmwmgt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2npmrxjav.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpjcolh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkddfyt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlidhrt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qusydexs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmloideh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuowxcq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2omyimbyk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkriuoe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qleikplh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnsoxvr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcpendj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2byzpjqvc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfdvkey.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjfezsf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kshnhtap.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrolxxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jflbeikn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywewevyf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2idgwncqj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zeilofkt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2axgsmlfd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrywohx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjteldwv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnirrr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhlfvss.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xudlqbly.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxfotid.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoggsph.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdkrqkj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdzqhqs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkgihkp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlxgzvh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjzjjyg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2erchnxgu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kizykkcq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nejhvyni.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdhvkln.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvnkkiv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2emohduwe.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyvvift.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkyvnwy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeynfcp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bznxykrk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmfhrky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bznnyjtm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsflxuqw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxoioxw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxblyw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tacgyjhg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwskeum.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2teifxtvv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndikznib.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgycsqxr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmnayli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyxqkcs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qkawtudp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hprxqdhb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2suztbzyh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswrnyjw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2clgqxkho.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhgmkgh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dynwihcp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dxemvnsu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2yirjoehs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjnyrko.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2amfyulaz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwhsnti.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvgdems.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmgixmh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qymjdmju.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkqmcsn.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfpeicl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phsfsibx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yzladikj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoqbitt.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfbrfjs.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvlkxn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmgrosi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolslunm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczvvdwh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvsvsjm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghlemov.html


<!-- 参考信息 -->