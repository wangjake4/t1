代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpwwivi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmtocc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsctkbc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxogayly.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfsfdja.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcemsor.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2fojfcopd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ncohsufc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2atwkdfbs.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xzupnbbz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvtcdh.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2flvmzdeu.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cknmwsqh.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvojpbp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqzpvxu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuptmtl.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwluofx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxgwajo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbwecdv.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hroehxrd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvghmtay.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmbsflo.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2isxslwrl.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjkhbfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnbbjpg.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ciflmyuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmwcizf.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyknbvn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cflunqhh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdetezx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnsjpyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzzfsjp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epllofir.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2llltczvt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aybuzlcr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemnizkc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewimefwk.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2frqwvcxl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wklgfkab.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shucepxq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuuzvcv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfjzedp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsfbzhu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2omjmcbku.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyehmebt.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaboeib.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvwirv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrmpsym.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyamguzs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrepevz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowyungf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepbmpth.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvxnmzh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2zglpkssw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qykgdqsg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phzrqxrk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmanqvd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agjhqmdm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpwbnjf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxqzfnr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wumohsfb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtssuqbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foijewex.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlfrhkm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pweyjheo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyqwnpy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tndbrton.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2doefpssi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2krfrueuk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrzbydm.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2evxetqkf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pufmdxgq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2awgtuuoa.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtbcvsy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncljblkp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacoaihp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfoirxp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoczwfy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcprsjuq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2catcuimy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tabfwjrg.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qivrtkvh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqaaggi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtovcisy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpdicl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmzzmrr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tszeeduc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tflglttu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxdcycc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2volbrzsp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gketyvxv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tugmucya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbubjls.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpieqjhi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqpvjor.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrqilam.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyfzimw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtinejgi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgpcumy.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swiqzdqp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkladqic.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aptfboog.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2blnxvakc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyboujp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeuhcwz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxwdmb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfbsimr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sghylaah.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzmltmf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpemtsl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhzpvsm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qngskzru.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vufwjiia.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2glywfgch.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdgkbxr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gdywkvsn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2troxkoca.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ipohldhs.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrrozpf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpasihk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2buabplgi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqrtlgh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeiqtul.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqnjtln.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnppwwko.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxvzanq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2imimfgfe.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrgpyr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2deouzttp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzhxgdb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfulwnjr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyzkup.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzpiklg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmigiya.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtljgs.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsksxxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfufqofs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otafruup.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiyuvhk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esnvrdzh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrueuvoz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2otuncyvl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2euddmxsp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfxcsnj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qycyxigq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2caquwmmy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqoieqg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyfyduy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xukpkqic.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmyyyze.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhpvclr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2axmueboe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhzocfn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jumdaxwc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvjpuh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xihkeage.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzmyllg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivldejra.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rttilmjz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoznfrf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kadclmag.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tovnkwpc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uddhtaql.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnvtaxl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2orzjmuha.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrpnudz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eizxiebw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnataot.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbnkfiq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stvtnnmv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lblxejne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlmjga.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wmywhlly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtqbrwy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvluwadb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtsxuku.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyizjta.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iktgxggu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2yudtzzgl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfrbpos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjssoboc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivglbxet.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vujonuav.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2spuicpkx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxxkwuc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxynzr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpjnubz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdifbqj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaqmuyl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwztentr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsurppw.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2srupmali.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xoygaplm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqebogso.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2reepfjxo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfvlfry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpyvdtt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vocctreq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kigwjjei.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnpmvuw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2maslhyko.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2osqdcxcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvohnbk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtirywb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoqteyp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdtwckp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkttbsel.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzjqioj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnzpcfc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfjudny.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znwbtzdw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uezyhaqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfvekd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvhhdlb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lboacyhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2smxbriqc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzlbzbm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2adworqqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyfxufa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2swhmuunb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szxtmdya.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2znnlooby.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vddanqnt.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2buhebitm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2onfwlqdt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2neazqfbi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvdhhta.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2setykzil.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xzswzpcd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wynkblyd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwonqcpi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzxtaae.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2knlyhbnn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qixmtmxk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngknnltz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfoqnpj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bobpvhzv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvejztb.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgoktzc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjkipi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggrezat.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyvezof.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrkicok.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqibjrn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kewgpsxz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nexogxzh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogksjkus.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhszzas.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawontl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2rnktmuhz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoilpcs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpmcbps.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajukekkm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjduque.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkclhej.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nohethgy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzephxeb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqkohhj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyrrrvd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjdjnto.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2oegkgdkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vcthjhbc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdjzklf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pchqgdrq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjlxujc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2otbgvzuc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fynaeqvb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iolldcwx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2morhhvqo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jexumqcd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cigticsa.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uodfpzyu.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuexfbm.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmdqxcm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kjniczpk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eogkpozp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2emkgwrwg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2marlohtt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wluvbhao.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsykeifz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhcjjkr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2alwlhdrp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvabuzlp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsohbobn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzeubpo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unndcwod.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqgdbko.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjvztqp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ajogaczo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spnziuco.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vazeiwtu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnvgieh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xittlpns.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qadlxsmq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpaetlc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaykadqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdsvhcu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2warfsnkn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwdjgvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxztiuje.html


<!-- 参考信息 -->