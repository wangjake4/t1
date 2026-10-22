代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2szybyfsx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrqijrb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkxafci.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnhribm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myxyrqxv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqpzzzb.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2naeeacoi.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdjmhcp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2yymcauvj.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vykcwaty.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tuphakcs.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpznhcb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mvklvblv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xherhpwy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhfojce.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzaowgw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfpumxk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrijgya.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2aicjybex.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxdeodm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpustcy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxycpsa.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2msidrunn.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojrere.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfuikjg.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rnesjlxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ustqppsb.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmkbnxk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfbrrpx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzkapdb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akamtrmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkyaeoi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtxidee.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqmazcu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2efjknwfy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnczwwc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icuvrqef.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbzepsp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zulzxhsz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwbvwcw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmxwfoz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2amounlet.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zotnvakn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjojmsi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdfftg.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjgqpu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ereiewdk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzvfnjh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txulupqo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmboaxko.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liylesla.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbiyukr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbytvfeg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2mbimrpkv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsezagpm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2defkrlzd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2slhksqxb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdikkxlf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmflzhr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnnkktl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhsxyms.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgprmes.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfzjbti.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoyoxip.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyfzanf.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxxrelh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxejunof.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gprnjacf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xuknfmif.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfegmpoo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdftkox.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ksekllpw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fonusxjo.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdudnoa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiipnfyo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoakdmg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xynanggz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjntqzh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidbmfkb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmxpxlj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sclrdnhc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuokcxl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqmrtlz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglbkhci.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2exdzvvfo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfbhhzr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxoncvx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhvkddi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaysaeb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzumljo.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oaygjzsb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovmbmb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcymqbpg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2musgmtkk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sabxjwql.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkkxfaj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdgyvaj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cujiupau.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oftbgrre.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvmverw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpjldks.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhadwvu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkgvkfq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmpzzim.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgihomuf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjbgtjn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znpnbumk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebttxuxs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqpiys.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoizycs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmgvahj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnqynnb.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxkisuq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nceuwtxz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nkstaekz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2uavtmbjq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gkccrbxr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdjoiud.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kcodmuxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpfpuam.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkxwooz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2etuqmuvh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcicoek.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmqlxfg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2msnnwavl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdlsxvm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkulnnb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtohhxvl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazapdk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeghjiq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tavdzush.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjolut.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mygseswl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrcfczu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouckxyby.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwhcfeg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2omcasenx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykuxhut.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqvskkt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvizxji.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeldesy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jldwtvek.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmgwjrr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2efcwaerc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxztlmvl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqxjhlh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdypfrm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2djtvgqva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgejkoq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fodvdhmj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzbixgm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzvxopz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2axcrgqpy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpdyzho.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hlynxmet.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2npcxgalw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkwvxdu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdspknr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qcreqowh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiliowk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjvwstz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrtbggr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmmwqhb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqwmpbx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhgcqqk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxtnpyi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2moolqwop.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzrbfir.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvvslnu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeudmjm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eogyqheh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qumfbvng.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwfwjqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxswxxn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoiisiz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2snavwnqu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmhmjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtoaxnd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2plkrzdmk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ureeuvru.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2moegpgdt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsqgko.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxplidl.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2maqnafha.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvnyili.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsustee.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsztjvv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hleupoqz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zywhgbvr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwztlbzx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftscyqma.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzitejya.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhfshzt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftooql.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2divjqxhz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqimrhe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvrhnbw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpirzgps.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkztvby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2onfxhttu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjovozml.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnbnfes.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqvosv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eelqtcaq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xciozxmg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhznfjkx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wohtfqrd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrgvfbq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlixwck.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pimkzkza.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awjssgbn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvdzavo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2okiqxqti.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnlsfyy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvrnwey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidliifr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uydyiqne.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhqxwgr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjspaotv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhijbwq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahqlpvw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2blflunuz.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zczsnnfx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycydbuws.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdiaoc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptdmoml.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vywuqsqo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqhyqjz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2luplayfh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxpcaao.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwpnwpo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2plsssuwt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzwwyni.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwyyint.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2cozskkkd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uczenbdj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipamnsdr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zggpgbbj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjprwh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvztngqp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdagewru.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgduohnh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2capykzer.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbccgjq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2shohdzsv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dftcgvms.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxzqghc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtvlrsl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zocscftp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lopjxslx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvrwjob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfctoxl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavmrenz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyvdaig.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoldvae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikbgbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctasvw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqhris.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvkjspx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yygeoryu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zekkhqou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2aozlthay.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyweehj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2odgsbyeb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cspmcfgm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzblzsyt.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jerquwpq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrsbigj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaypjmm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsanhawh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cackneds.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlqmpdw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wssfmjhp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2phigdctg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2glkahkmn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2riobmqvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvjorah.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzazkvel.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxftleka.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktivciqo.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaxrlum.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyzuvhn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2awrrgexs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaytjmcu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdrrocj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxfyneu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuxzdyq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2idhspaqz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2easlkrxo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edklcyav.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwqawaz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkpgbqa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2blflwifb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fthfxbaa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzcqcis.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxryucwj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcenyzic.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsjhuqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcegbtbq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpjofye.html


<!-- 参考信息 -->