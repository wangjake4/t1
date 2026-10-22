代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbrrmqr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqttjkmw.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2uwievgqr.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2isofhaat.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuaninq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvmcneo.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2runkgzjm.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzhodcb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lvspiodv.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvqbab.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rnazsczu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xslzhrxl.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2thccumtr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugupjugu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdbfxiy.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznukhr.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlubreaw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsxlkfq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvmgbhs.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmzvpsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysprcwsn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zofpagxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnpafom.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyjvqnq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2swjpesen.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuocinxw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2segvueda.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyjeucs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbccqzms.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcozcpgj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjsmzhx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzqdcid.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xniwqdme.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2bamqwtfr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxufgfk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxwjsrb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnogddmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2foghxlox.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oacynicb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2arzzrscg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubskzwwm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mucpuyts.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyfbdaz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyutpot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrktxvd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrjoszi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuoiljs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttrtiox.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2auxgzgmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwacnus.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpvpwsm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbiumrz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnbjzx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acpzjgke.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvbaytf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeerfkx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjnsuht.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzkzueg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmidvlwt.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrkcqze.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbnyoj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwymgztf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaxmxnk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyjecav.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfubwfi.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gobfaena.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2edxvnqnu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ezftyinw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxdwrhg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfherpm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hswooydx.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvvpzmq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2durjizxm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjhlqbd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2warbikyr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uldzhjgi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvqamsa.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ltadbayu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vffemadf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vagbuxqf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldedvorm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jczudexu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxvcvpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hohzlftw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsddhtzi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2rodkomqm.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2erbdfaci.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjmzdnf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrjxepj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kszpkuvq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhpbjtg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ohylhdun.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvveygs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdedtwyt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnqohoh.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2afvaxlyk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poaidrzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orordyxb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwuqjra.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzicuqi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdancdix.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yudmlnax.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqatkxlx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fudgogzf.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxkjjti.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jyakwthd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyeiuhp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdqpjmw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lafdklei.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jctczjze.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aufpqoey.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2buyiyzda.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwbiqjx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sclhnqfq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjzquob.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsosxgk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zswhsurg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uperegvf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfiizxn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2pekobrsk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fifjovgn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfznlyjh.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtiycpg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2khnverif.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwyqzil.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iygllbat.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hefqirkw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yntasxsn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvsbdex.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhodob.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccnkjh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmuzfyc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjezixlc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oscvfnzi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2icnfgucv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dphovtxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgibdeys.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhinvp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbilurq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvyubbm.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jijkxzqn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2udsraymh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtyhouh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbncgxvv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grtgqwas.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgggufbw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kijchbyp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlibfgmr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrysacs.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfswkrmf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2phddnimq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqdiyel.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqebim.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxizcmi.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2epxudvue.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnkcwnv.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgyqeaw.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnxcbt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fldfnnti.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2twrsttiw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2blpibtey.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfyxeml.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ustthone.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkgibzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvtacri.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kitncqdl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoudevr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqwfsdb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsrbycj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzbglsx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uayytaij.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2htghyqeh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jykexatg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxavakkd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkomva.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkatxes.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmwhkr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kwggjgjq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuqbyqp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2boryrymh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2npjbfcku.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtjmbde.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofumlsoy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nooeodgr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmgkugh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xphtcnqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtnfrmp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgktnhhi.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxspjhf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrhtlg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmtngk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrbjlcr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmetzykl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzydgnb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymdkqp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyldwhgz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkyjabo.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fcflllor.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjrcjsd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oazcukrt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bncknxfu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eykypryd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwyasvg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2msckemfe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmqxcud.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwolojq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgzpmhw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dissrzof.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgybuhy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvnkqju.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcvxpdc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqbkooo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2egpgelmb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kcggfjfg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2npbytrve.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvursqk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2myaxtbpc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jutrxitb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zplshlck.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiocfme.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgqjxrz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedemygz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoukmae.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqushzn.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vzthsmgl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rldrwkwj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtvwnwu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iosejwvd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczeyzat.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzkeocq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkxuie.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2anxzluwy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urdmcxid.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vgatesat.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nolqzhrz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2surdiemt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjbtuof.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnovcye.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxxjtb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttgpnqc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2endtlxrf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaufysf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzywhoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqompnao.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpchvwn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2idxfkbkn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhzwwr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlljydo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuaihqb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mijzksra.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfqdbh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjetdaz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrzjlmt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iekmqkxa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnefsjf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vauciizd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfumwxty.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsshlkv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdqnflj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tktmquql.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2grmgxzzt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqmydnm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmxosna.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnlshel.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxdbwun.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsopshrt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vymoqdlq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hcojtzqk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2prkxgtsf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2omhbgvei.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevrndo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukjwynx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaglgue.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmyqqnf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2uciepqmi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhraxgmt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzwmnqp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vugrvebp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2etbrovot.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2otllrrhy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiabwiy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2erygnxor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvwzjj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2apjyipdg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvaiyct.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhvkbcs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdinvll.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tocpdfuh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fctuibet.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxzvxcz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrypxdd.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyntynws.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyekwlqy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jyduxary.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwxqbug.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skyuyxho.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnqmdsl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qddwblbz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuhcldt.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoylkmp.html


<!-- 参考信息 -->