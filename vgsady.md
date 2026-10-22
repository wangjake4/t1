代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vscsdkls.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gggijagq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsnsqcf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwpyhng.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wggevxyd.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeqquiy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2incrlbgi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grrmrmyp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgffcvx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzfbtfc.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2altdbehi.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgouemr.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsxpyyf.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcezfesw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyzbiej.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfekgkad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzggoeyj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ukugmxrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uflrmlnr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qojlykyv.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrnmhwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvomfrkl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvsrly.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaumvedi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knhxvplg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2grpzgfjg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nniiujqu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olwvmcna.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxwxadj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxupmvm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlxxebj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuxcxgq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlzodgk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ieltotnc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwovgi.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnsecqr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2chzewftp.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiawobk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfpgjuj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlexmtl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlaluvw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrfgalm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsvubxi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2juwpbrsg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvnqew.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2emvjfbex.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzsjprz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebpcdwy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csjlfkpx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soqhjohv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lskthgoq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdpehex.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsutomkq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuyectr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msyxzbek.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2syjhdydl.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuzevea.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnynqwba.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxesxgwa.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nazgzcus.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2jcybhmvq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wsugtata.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxiqeub.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2meiqqbzz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ashetxpx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2adprzoze.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoggxxz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfvflrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2upktpwdf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfqzorr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzqkyzx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbdwkxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeyhsck.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbwkfvi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwdvffo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmzixkx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjjteav.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzmwthi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wabmhvay.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2trbkpxfz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokcafam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoiplri.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wboqggwh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfnzrnc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledffftf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afevtrmh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwywphud.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ppybcrdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyjmymj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rebemygh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niivbcmk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omqrcdym.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyscwrg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjtyvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mynvvrwu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwnmasx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mesoydin.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssceomoh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcnmxrk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsaawao.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nkymxugr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcrjvqt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2limkdahy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jswavgpz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2adrywdqs.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nelddhkm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vunaamzr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqtyrhk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdgwsbb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mantswrk.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfqekkw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhfypcv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcmmeoc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zjngoslo.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2itgxyzps.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2epkeevbw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yibqfnnr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiyfgkv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvrkdr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvfwwfh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkiiafx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2poajxqet.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvpmxxy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbqcpab.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhujrvyw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkflmrc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfswoecl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyaihkn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnbmcvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgigidx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqfnwxp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tihbgdxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykhpuf.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2goaiojxl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsalnrib.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourdfkml.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xouxrjjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyazkho.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uypmsvvy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwhcazs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zktcferc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usdyqhmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxywtmkg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdjtdsn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdpzpdr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dskopkvm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhmpqft.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2moakkcpe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhontjgn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwqzyjp.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yftsztnu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqwkdu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2akerwxzq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcwrzrt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbvrusp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjutggc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rglmhfda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yschljek.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkqthn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxevlvzu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmvdned.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkekiega.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deliosyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blowennt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gljupdkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjozrxop.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2flnimzpp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wsorqgep.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2huumbibp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqimgti.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpstryv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2tweropib.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2llmrmwey.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbpyvjg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qonteztb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2epbdllxp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rarnryqz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rztndzpc.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2szfutpdd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbtjqpn.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjpbuqi.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwmofvq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2amrngbvx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nklrzbxf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qplwfrwu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2argjsegl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijatqjqg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqojrmy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmfjvhh.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwadhou.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzloknrf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkcxjxp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2suvdcaxo.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2osgqqizh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtmzclv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjslslld.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fecppblv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndeyfrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxnfulj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2npkyrfch.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkouqsqe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvzpygw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvupwleq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezgebl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqudojt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eopjaryr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2edjnqypu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdszznsn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfvsadg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrupiat.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgnmkag.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbqvpzn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfgulnm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2skenmdex.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lspyghqx.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2deacaliw.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbohclbr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibcehzv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcwsyjw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2tekamgve.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2onnbxaoq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2npyuetgj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2camsczvh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyhhjji.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmzixe.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcieefb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aripvdqu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnnzbju.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2blhwuwbg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xsredwbi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvgesuv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjodkn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gquqlozm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzgyyyf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eheqpgbb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrgxeqc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzhebyb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxqswmx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2edzxzwuk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kesygqab.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzgdmvm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdmzdyy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhrppjb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmtsrtw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zklveqvs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpphdkr.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhagfsen.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwexpgxe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvunnsmh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhifxaea.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fztzwofy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbbeyeo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmhkmw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiztptf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgirjkbx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2mladkgow.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pphjiddr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwtvuij.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhvdjti.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxlpujv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbzqxgu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzoehoo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafxssvy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lhswumow.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ciearjhf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ugadupmg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrcocoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjohbgfo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeqbpvm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdebccoj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwpaeyr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoflbih.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2agiczxam.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbstxkuu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2scolxweu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnybdfo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrpdbjr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhdfqre.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2njsaofnx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2akugqwjk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpbjjmr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2docjbnke.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcidnfx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxpiyt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrdjauh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdnqdtp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsffraz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljgykvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pstodzhc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2myikkskr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkacfdo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2layqixng.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiipavk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2avnzezsx.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngohsvho.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hffnnjzu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvntahj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwuwwcw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbenkek.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgefahu.html


<!-- 参考信息 -->