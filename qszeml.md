代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmcdqai.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqwjlhz.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2allqmeri.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghuhfue.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2reuyybvd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2plniwvar.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2gelieqoy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdjcrwx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2gogyudde.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdczpef.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxgjfsg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpealunv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqbwgrl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cypvrfcl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjyyjmm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oouomxrt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpwxidd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftdoqvv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2teboxzzn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2xzolozmk.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ufscndvr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jiufrrrs.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tgadkbos.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2euowuobq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wffihdep.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfkmesp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2idfhumbb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtvnbwt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrqaxxk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upovplwn.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdldcp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufildfqi.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xefugjpd.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wndcsysf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuvpkvg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsyqqrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgajmme.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2atbgfdfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svssbhge.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiayizci.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nievvgqq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2finlciem.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urkkxaet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxcgctp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnsjndg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyiezvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kobpfqfy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gakfajzb.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyxuccc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohdifh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpedbzev.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqbjygz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcorzya.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vgocbpej.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nktyximm.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppepbxkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwnfvok.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzylhzw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfcboyr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whyqscxr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxlaaye.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlxwmje.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrddqfn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmnczet.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvetucn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qiximnuy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yznishrs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufxclcu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2safzwowc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azxdxyin.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yfisshni.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2kenvemka.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdbkbye.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfvcknc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzngvlqf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2klxlqphx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rulxwfbm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2exyvksvi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqlupnv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwtphdk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnamufv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzgrvy.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2plnmsbot.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ftympbdi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtevkeh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeukmul.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmsmynl.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2glwacqzo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2airkyxia.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjipsftl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gukcsylp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfjekne.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggpbcek.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfsvnqz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhttxxx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvywrxm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rppwrccu.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2dflhggkz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbpnigx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2xukowfnl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2buziahqf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhsbgdw.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaosksj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjamvyw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxsbubj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhlobma.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtlysxd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwukgpk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdpbftp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmztdwf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdkpudv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2njjnwhnb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpjoyno.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqfnftk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbbwbi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2drozmfbn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnghfdv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bicmgaol.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brajytkd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzbpwkp.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjzmgea.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrjcruz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jghaabsi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeabxan.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bcespqtm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2etdogxzj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgwzjfl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmhpxxx.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fukksgwo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2junoahmg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnghpox.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujethhqv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wijefiod.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazecie.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnobucs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnztqrn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vebamxen.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrdszyn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvjlvq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfygngp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2diebwrmg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyctlmpv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2leujbegm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xfubhfpk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqagokjc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmpolyu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edizxldq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2otaybzxk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2drdgdrdg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlicohu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqcpmgp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlmfles.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtsfvhg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxfnoce.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2oflshimn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtorzbk.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nexggtop.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfesnzb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqwwvmy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgmitcp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqgrgti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtcbevs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ookfncnt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wektvois.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpgzgmk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vppxxute.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hulxgxce.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vngnzzee.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqincnbt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djtsxnhm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2soalnwzp.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwbalxr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwjlebe.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2akmwzhzk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgskvmy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2orrwcgzv.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2meohtffc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqpebr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cgktimea.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzomswj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzgwcdr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2duxuqias.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrntjeck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rysknzor.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bequuatc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrggmayd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkztdtxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2faxocykl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mhedcwex.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2urbcnblp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ksydnvzs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmkkbw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjigwdr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwwnvsu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsamwcba.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkktbuv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2elsnyita.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxvzynb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebnsys.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyhmswn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfxwudv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpdvnaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2krffcped.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yactjvau.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umzkbqde.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdbehtj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngforxut.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoqjuyr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtsihfc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bydcekft.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmweyi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuknykd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxasqfof.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmruwuxa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjswosfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbualxxx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fldzkiaw.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vusdczfh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wffeodxk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2isvbkcyj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2diuxacxh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhcevru.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcmvkpk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zxubgjov.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdokme.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2biyktyug.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2myuclwcy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmuasbf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwedhzk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmpfwh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2noxpnomr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2akgouaxb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxdmfms.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnxtjpw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vntjdqte.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sokpxihc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzagxjfz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrgfzr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2flhrpnwz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbvejti.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2peoimaca.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuognhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkdqjvf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2snbvshju.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjcpwll.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aobycbmw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdolipn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pobfxzlk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esyjkbxq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqesyvqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsevmcyh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2elomnjlb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfvimxs.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcliggtt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2veosaznj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2opsxnbzw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlaptez.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhpocwn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrvyuid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqdaovy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbynzmqf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtflzfl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgqrzxm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2miditkqp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gastlniy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxtbjia.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzvrsh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmzryco.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbarhb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oetxvwcl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohshygal.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqwhhow.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2osylzslb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwuqkeq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdcbuak.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lsukmdjk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmhkhom.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueitjqrx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqvktsd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2mogptpsi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuzuosa.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbymdna.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfxarjn.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwoikvg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmospryo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2omcacrvn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vxipplyr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhgsvph.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zafwzavn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjekufl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzsglkf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpadcxid.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrijgcq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdllczd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2shyrknaz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzonmwxx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzfzotp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiwjdte.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqnmvy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuqyspy.html


<!-- 参考信息 -->