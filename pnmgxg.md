代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2alpwriav.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cgejtfoj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaoudyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pqihsegr.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmkiuod.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yufowdgu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeliiiz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlcdxb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwapwt.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2galkxdtc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2urfrzhgj.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlezwqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rabnushq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yufuntxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzsuuxh.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcyolsg.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxsreho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cthlbxsb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pujinfyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrvibpj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmcyldj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylzzvjq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnoqjek.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heiueple.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olvvmxjk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2gndnsrxn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldiiydt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbykizq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2optjdswq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxvwfju.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gttskwkz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sphsyzbh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iunlkjhb.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qndnowgy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2delbxzlb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmztlwa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jugxkrth.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpieuzcb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arftewmw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmqnhxp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqthcgv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgubcrl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqrwljf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxkyanu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygasepul.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oetaxhjs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2otxjrdzw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dphhybwl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlupukos.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmbsodn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuddiqjd.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvogvyb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxirmnv.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sufnjour.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjojpxh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kidyjpmy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpxfgpz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjhbyxf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjumea.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pkytzovi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgmqlxv.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzshwyv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2afwwdioj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrmxzdb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2purtktym.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilepezxw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsliscz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxdescc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yubaanzl.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2nquwigsb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrgwbln.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxeshfo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmeoysp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcnxbmw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwpjiam.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtwutc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsspdghc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ucesddxt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2issxsong.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpbqufa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqutyjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oorghohr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeqpqar.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgojuup.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqzaqgh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvnvqqw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqstwcfh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yavleqhi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfbrmty.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkgdpup.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2shazhpgi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zskazqvn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsonazd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyinpnwy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfzxxvi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lchxaork.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqsyofl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrjeffj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmwbeev.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rscdehaq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlxqexb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ctckplwf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rygqmvgt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2aiktsyiy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dudfytng.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyzeyhw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rimmgfji.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvuphrh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbzyamm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2irnkrsed.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlubghl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2anmncoll.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bckayjrm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpvwedy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2haofynsf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsuohsl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2akqzfgel.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eorsrkpq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkydugav.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xykjqqor.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixohpjog.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxprlpm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmrxcyp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gyavjjgb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmeuecj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akhcutce.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2moqhkljs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xobnrxrl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupcwhpo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmweyyd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2csgxseqb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyfuulp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iijskmwk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoschnf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeffmes.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uddnwolp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtanokof.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obcuhrku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rouksobu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwqoeov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjrvbdb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuqtmzp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2rlquldth.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjwlzmt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmweycoy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuttjghw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpytejq.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sjswxotv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2siklzhzz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwdyygd.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2goocuwiq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2meblpqeb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hezfcuru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dlipcahn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbwvwve.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoghwgy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkjfkk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbveiohp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxmjsaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icfuaohb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqmtoxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glmqswhe.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpueybe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzpnrjv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgkldev.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2whextpqn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwppiyq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kewikouy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjaalzd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2thbdxulm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohifsw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swbzntbt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2sibjgead.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrcgync.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjudswb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqonrxjp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsvkpuw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpumdbqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpznpyc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfougpir.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2womcnuvq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbattlx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqhhmaf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfnfssg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wayfzdjn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azigijvt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmrqngo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpbqfhe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aovhirpm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2whlklpdy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xagaiove.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshsuuin.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcjorow.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjbuzt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzitzmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwmprev.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrecmkb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxskxotn.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upgkdngy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2inyyzjza.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpuwlyk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfghtxl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnadqywh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2adxxdaao.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzoddve.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhyjpgj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrybst.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfzjkt.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxccmcg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthkznxd.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wflievty.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbbxlrd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pttkavfv.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtjzoip.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2freoybzh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuwvycz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyachjl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmpzooc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txtiaxkb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awzonorj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkuncsi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2doxoxxin.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2emxtgqij.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpfdvxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2panfkorm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmarkph.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrmqkre.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucozfaaa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhognee.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2swedsxhb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbepeif.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibheojyn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvpsfpz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgcruvj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmyxkfu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeilaey.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vevdoahp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kucexrgv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbvepgq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rccsqsnk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnjmsmf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emxxlwdh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxnfyi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2txtmtsmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvmwvih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2najbovnx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeipydp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtuoshq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtefjae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyyhfxb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynawpyue.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2agsjppof.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgfdkwc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2umdjghaq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflyvycb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdqeuhc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqewhwvd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sduxxlpp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hilpwuwm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ynscdhyn.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2owuuxmff.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2toodynds.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjpnisn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrjatdc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqheexw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmkeqik.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xabdifbm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaxvmlr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyfcutd.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpsjwkt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2thguagpd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgjyyae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgjmdf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdnatsg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqntzwrf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jakpiixp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxiiuvd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrcbtf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgzqnnc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2eosegdyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwqmakr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yevjocxc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivinsdkp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odiyctgm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoapgws.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsdutqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjztvx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjabyiv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvzvbww.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzdzath.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnsstgq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpzehra.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrhboxy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbixzbp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqwqddo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkcnozs.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxszhvg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfkxpqi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjxwzzv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2usnhtjly.html


<!-- 参考信息 -->