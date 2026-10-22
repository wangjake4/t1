代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbmaetv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqivsu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2umdvswee.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jurgwurg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2qighdkjl.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwtgjeg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vekedhji.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zlloglps.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fraytauw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrcfpqv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qldemygo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bboltxhp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rpakykiv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzfagim.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvinpist.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2undgkfnl.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxcprxs.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhpewmq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaccvjn.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxtmmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtvpzeb.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2afezrvis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vregwdai.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjuzel.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tejxbfrj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iisdxdiz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shsmuztl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2henyhlxj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lehhofkf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwyrgab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmglbszd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznuzpvp.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txlrekts.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwvkxea.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gszarhki.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpagtzb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeposnd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2imohubhr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzuscda.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aansuzho.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spbysvfo.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcmiyjx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrgpnki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhyerlu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvnfdfp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsstbbk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmrzqoa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivynlelm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoqjthz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dokxtius.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqqnzbd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdflinxt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwpwkyt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrddifjb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyaovnr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtpwgim.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrbkqep.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhuxqmo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvyrthc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2szcrgfxz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzetomkp.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdupdri.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhiarqh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmspjghp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpapyqj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsfdlrn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvuyjwm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoavlrt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjegejs.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvvjlyl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbunpxuj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrlbcfk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjdsxfb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsglsoph.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmnfcrg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgeqkob.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyohedgk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rutwizxk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrsffxz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2stzpuexv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2cielufic.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaymzhw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnzilq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2uedofdtn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtnhrcp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbufxzdv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdwpbkv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dynfetmj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrzqmhe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjamiuk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmplxuub.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2axfsvfum.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvsggx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqrkrjc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czaqqdth.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2refntzfs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafmpcvl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwflkhz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlddjzrm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2aupdugyo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtmukqu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2anjuvalq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grgitlzc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aalboczh.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmoedtl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcuqtky.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wluiqypt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzsjtwj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cppwacwt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aaanwzaa.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsoewth.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2upvpplca.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzlhlni.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswpkdu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdwxoir.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlphpbnj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2psapknxh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2eajqjrga.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwynmktv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2frvqgvgt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiwakxr.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwvyyp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwhsrde.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrujxgf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2alskxwxq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eephujxk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjslzzm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2srknvitq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqacrvzv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2edcdnkqa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oianwdfd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2irmgpbvx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2danckekz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbsfafn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdiqqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nitlezbk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyzkewp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2anqifzdq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfcqinu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2eowgjgxn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vflkxwwc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtvxgat.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvksbqjl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrtwjco.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhginhl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2heqkrmid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxsokw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdhbjmm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwztebr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhukhjk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ughbfvac.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lilifhhc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttafdjzx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elguhlcv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtylyeg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpbjabo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ejilpbjm.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjxnjcr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdeiipi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxhmceo.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rluyxqds.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2orhqovfu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umcclvip.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwrhfnw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyoldjj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwixzid.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqokylk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpagwdud.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2iaulsskg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxrgvps.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sokletaw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jomkxjlx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfidbba.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2epspzidh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dopnydre.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2uulckpqi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkryyjth.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2esccfzjn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumymmf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swvxwwyh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2jswkpihv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgioibi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwqjttx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdedjdc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnvyctx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvcyltp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzsmwrh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvkmcnd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wudtmtvh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrfbgta.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2isoeaxpy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpzjakg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmfrwse.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lholbscw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthybfrw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgdiiih.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwlgtqs.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzhqgv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhqduhx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yprhrccw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2epzipjey.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgirvmgf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bohdenxl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwitxkd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhulewkx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnogkun.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wlacisev.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cflyecke.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxwmbwp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dakhlxvf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuunggnj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exbcrzgg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrphxcr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vlthbasa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudljjau.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtwzew.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaqvcpx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbomvbdr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcscmacy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqmfztg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nebtiuxn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlglfpd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2awmvzncc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvliuik.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjybyfr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2byohwbce.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavgvje.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyricczh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyyirwq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeumzwj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdbpdbd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kpstuiav.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgjaupn.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2queufqzk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkabzrb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzdemmu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2flesduur.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2slwospqx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2utcfllon.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfcuton.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnpnaou.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2whdlhekn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2khpyuzoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrljlxh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfpgmfv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrlpjur.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2oanhnwip.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wywuyvwx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akylmxda.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjmtzud.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fegklnml.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgvknlw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbshztq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eghyvsnx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsmhyid.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gktkknkf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2andhpard.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mugqjfge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wteordgi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqlgtcz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrydlfo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iozpstyg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjxprqb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kddywmjn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvngaye.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2paqhrisu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amuzwijp.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtfttxo.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hycseigg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbaoqhm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzfxdld.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xstqqbho.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2naepoojy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjosrcoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ertbhjlx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwbxsmg.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjcxxts.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxjufwk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xanimtxv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdirryml.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnxvrea.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaklgjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufirnbuo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2psajnfvz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2lyytydlf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxulqdvj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvffgeqt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlpluih.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wubulcot.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuemscj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clblyvvo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdzuqlj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuyoddb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtbtabk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2timjriey.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbigqlyl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlpnnyo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yztkyftn.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtpvalv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2euariabx.html


<!-- 参考信息 -->