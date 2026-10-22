代发 wailian999

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdptboyb.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhnqvld.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrhzpmq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhtkcbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pibcqfto.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpljxvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aylhanxs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gegygnkm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvgosv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enjebrxw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbnimps.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vavfbfab.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvipttvs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzesjieh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjugoaf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxdrwdk.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqemvf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwymnoiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtoxlon.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crhfoxhe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrotjtk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhnhoer.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlqjwgr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnlbgoz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkikncxr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyotzgla.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtkgrzv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiupmwr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoiosnv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfohwbc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuwefym.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhhtpls.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkucnsv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2cljalzas.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtmwgs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmjzbta.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scyszltk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoemngp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ynadectr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2bletdsiu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbadasy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwfohsq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njquxupf.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojommxxj.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgfflpo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2emgpaues.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xewxdncv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfaaemh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2urcztmuu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzvmaar.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzxvqtm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxczcvw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzuwolk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdldyfu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcjxgrr.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgggqvvi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphgjztw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrffowu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoquclk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggmdli.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazdddpk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2buqbsstt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwfvevz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rypirpcv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvxpfgf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhucijp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sicnyzkn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2maazvbuo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixurrlrd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcambnp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2medjzcmc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqihwhs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralpzkew.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpjhfwz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmusjhf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kchwvjxk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2msilwqfx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqupttsl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfcqafe.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbaaazj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpeezxx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmsqxwa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2udmiutnm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjljyp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osfeorxz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrvpxkn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plczhnaj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jquflcyz.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejjswo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiqgfet.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2abclirfa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qroxnenq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rsagfibg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2juygpyvw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlntout.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogvkgb.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wenpktnq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mingiwvk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnwzmln.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofetcgtf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2shlhvclw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwdkbis.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzxbcwf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqrqxbj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvolvsa.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrdcukh.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2isepgsxy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrwaonb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2goynxmvq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aeevbfea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2phozaqik.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyqupec.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhekpezz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2anddsynv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwqooxy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhndopl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfpdkug.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsojpuar.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeygivi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfilxmoa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mablhmys.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkscrkn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwxmzui.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2njxzskil.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pliypzam.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fibbzkla.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjaepxk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbqdcvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyemswru.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxopzwea.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbihjet.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2akgykjsk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2polblnem.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tixyrhuq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lylharts.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttqsjgo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmtvegh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvmyreh.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzfcuqs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2buhpgtgx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoqearf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuxekzu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hololcum.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cnubaykm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2iqihntpu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpfvwko.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbuxbit.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqyrfdl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnknqjd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cidtudye.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqfeqsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsnogml.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fvepaedn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfssufv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2njlazjhz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wznporct.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2itcrkeam.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmjdud.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdycwpi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfzrhgk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwszhjh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pinbtmrk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2prrtpytv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqdrldc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2krvrhmcp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2trsfqiyl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhncmalf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzvszwa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eojzqhpn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpakloto.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2whiocaoc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlquyys.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jphnoknf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2emghhqkl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnatknjv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnbkhfb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvqhrwt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2liyhusrw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbfgyvv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iomxrtok.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngieyems.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tppgpqap.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcdbpan.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2khvlctkl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vumfwril.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxpckbv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2luccqxid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxyqzqh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckbddfe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oekrkbjx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gatsfymq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnpguoq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fljtcpql.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdtlkzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivowwsui.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkboypp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kthsvgrm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuhlysq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2khdynwap.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkdeap.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmveoud.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2agslhumn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjwmabr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kplemyfy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqqsoxm.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnelidyk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jrldlate.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuqylbh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtodmcsu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttutxpis.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpmxecr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjawawh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjyofwy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmcolbn.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvubjoad.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2swjmkhhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psuaokxj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhprthn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbpuwru.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2slttqgmp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2blhltjyn.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmlsveb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkooiivo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgnxmyr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrkjdew.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2idsxdigh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxhlyfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sriwvgfn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoelnup.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqucmica.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvwqzae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqvjha.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dboedxbl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzpfqgd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgjvdta.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxhddeo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhtyawt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoiztoa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofgxxjv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxszuynf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wjontldt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvwvii.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2eojwqgqa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ziidjqat.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvgoljt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfddeys.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzhaejh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnafgaj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vksngrjd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wczoldor.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjivxxe.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfqvvp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdzrjak.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrzzumb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjhoudd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvxczpb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtakxlw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2brbehiex.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhastkt.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmzzesu.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjwclro.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcbpwot.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvmkfht.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsludipi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbivxcd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvipscw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfvhfcp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2asqxlflr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2rfklerva.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zllskajn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyuffwl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfssedsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtqmlos.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eswbfmhg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabrvrel.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkgwluc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmqgmdh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okljlknw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgovwklk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2omxbrbru.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvhgzfw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcrebjd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcmcvly.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfajekkp.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwpqgnw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2tucofjmn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2wkplvhyo.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwfbned.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuienafz.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lizovdis.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nranklzp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsarezcg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nswzrjwu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbgkfxj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwquvmvn.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvhokgg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrgrytn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvncpi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rppmsuxd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeeylig.html


<!-- 参考信息 -->