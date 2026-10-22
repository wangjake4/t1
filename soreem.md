代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znpofwad.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfqnfgc.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsidgfz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtyadwm.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgquzyu.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2enyxlkzq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsusmto.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bajguzpz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlmryij.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2weaauecj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vipkbkfg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2elikqhls.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2hordciym.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiieywc.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgwcxcu.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldazomom.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoelbmu.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskasgew.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2glciokya.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2acrrndra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bubayafj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2newlkydv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhplspqy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxqkyqh.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaajgvx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxxmqqs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oddoxqyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sigldbex.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmvufvr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwatrxnr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hywficuu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roeooeys.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdhgyxs.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2kzimikwf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pspujkxj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igzwqzzo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdhqjmw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofxmhr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irsjsiyt.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dltnokhh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrbukob.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwpuzk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2phfgaewq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoaihbl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnimzcow.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bireublm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycopuix.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiehthtn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdhadp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxzebuu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrohwqsd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkkkljy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prkfepnx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2difscmbg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hctpynhz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvxryx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odcvygzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmbclys.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoybiid.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vszmceun.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxjhgrj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopkwjp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxpprnq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2lztjlyjw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvfwvn.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yszuaemg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxclefk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2uiilndpb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjsyiio.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ndamthue.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yavcxuin.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zumokqei.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqiqtgf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxusbwq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlalieu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfxpdph.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwauiduo.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoyclcy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoaranj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlpvpuz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2sanrcpjt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2itgsaxuj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2adzuscda.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2cimvaner.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamsjhdb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgkwbuq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkpbjwl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmrlpha.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vviwouoo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2repqjkgs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqotbq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nggmjgmv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tokchdga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awzycnjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkuarlh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvshzwy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnkmwnd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfghbeve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpayitzw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bximkmao.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtjnnrc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjjxwvu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvsgoly.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbcjiot.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oriqufrq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2dutctbpd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fugifvgs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ibexbbgn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ppclfesp.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fgshnyli.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2frzjzjhu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2mzriigro.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2takaoxzw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2igtftoly.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiabecd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2umycptnw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxmpxvm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvifsure.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzabsqzg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxnndva.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2musvuegr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2azotmasm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2spzcdryu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfqzco.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eobuaubh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeseabh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2earvedvf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xjetrytl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvkkcwf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcuhxmd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unfgdsft.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpsnqbt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mkelzgge.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfhpjbn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmjcsck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxnxcjs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icuytpkf.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiwlmgi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzasybgv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjlwaiz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlbxdac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2unltkgak.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwmdvrl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwaxzuc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cervfmxg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvyreav.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbtlrih.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vaovedvj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2whcjkryw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpoilgw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zarxzpab.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxxhcxg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcytoll.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afryoebm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2odeogrni.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zdulrkjc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlirhlf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcbmpuw.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2quxaoetq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jkastcgx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2prmsxfhv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdfobnf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nercufbe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccujrqlw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhckftr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fibozarq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzwtvlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcdxott.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2eubvsaqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvguwlks.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpblfmee.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2szvvqxdq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dctnlofm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgslwmcy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuxyfxu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfoouvl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2abneulpd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyexqnu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqxuioc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvhvztu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zsexnrst.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udgsuakw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdpnasm.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkfnffz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wremxfwk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbzsrqg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryebrwya.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjzveq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwgharb.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhrzjfx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfzphtw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2huckxkoh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zafnmkkt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2chshatht.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahexncdy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekfohax.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhofeqax.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujmuzd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulflpvew.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kilgcbvh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvevnky.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svshnvcc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbbdego.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrxxpti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvakkgr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjynfex.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2udtmutdl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzzttlj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xegsvprr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lydsbfbi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hetdklxz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbnyjve.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2denewuug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mnceqsvj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtveyfc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcbtpgf.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2odhlgouj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2izwppviv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xobqqiyf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lisqzbwh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2tplpupwh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2leagzvwl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2afphhjpu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoaxqol.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kgprrvun.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbzcqmp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqyplmc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztophyjo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqdnddb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfhvwlp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgifzqxi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdswnriq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tspsfmeo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2njdhzjgl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohzogsr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkofsgh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwvpbh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwkpomu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzeqldl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlxulqz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2inwlqwqx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwdoxbm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfyzyuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmjnzpy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2whkcxwbt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbcgjvd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbnpxhg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwjlnpy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnlscsj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mzknteqr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcywpst.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vomrukcr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwpqnch.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxthyf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyzwcpo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzktjzd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyxqqvc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2afhedgkd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpidrud.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2prbxnhkx.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpxmkwu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyahnfax.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbluzub.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjddcgc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvydyvwf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioatzkpz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeglbws.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdjfhnc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2duiolphy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2huvloakl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pqstoccx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawtesx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbraony.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohvtumt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dydifcza.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlspyaj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdqnuee.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpkuyuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzefmlup.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhizonmg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydhphg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbleixwr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbchcyut.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwcyfsg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmawomx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdiqfiy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pscsyela.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjboxwig.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcyrylz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2smcxlgpg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qequehat.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmjbbd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoudvbo.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoptpjb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtyswjv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvoocsa.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiyqwzc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jemqihfm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpindlz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2detovjuq.html


<!-- 参考信息 -->