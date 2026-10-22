代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avoqixjg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadjkad.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2modefkgn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxshhkq.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnjsrer.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqkwaij.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wymoixzi.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfvyjls.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcngbuz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwduivp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdaimqy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igkxrmwb.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2udyvsujh.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhobsotp.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtrzkqr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvqjmfb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lekzeidd.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzyoqbu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2fvemkykw.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxojevgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roacphoa.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2plepbxwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jydhrwec.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhameux.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hexdjvrq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvfiilm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txttpost.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qozngzkr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsimuvs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnufvuk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkzyjhl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksekqqxu.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtseigow.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqbsqyg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idqlpsju.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyabslu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aezenvbh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2isnbyqby.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfckasfn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkyvur.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hplikoxx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpghsnxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycbhrt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbperig.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrxfpnc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eldaqonz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okffcfro.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmkshqo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwylyszv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjngsbeu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2demwawci.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smnafeaz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfzocvu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyzyybk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ocovjbon.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hkitfnrv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqgkhko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrysemzi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfkeeg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwxaqgm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sukdwxuu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfntdfd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nazvnvah.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdmsnuv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2tamuexqw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xikwcwan.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cygylrrl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwasbas.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vczhxgzh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeuphjl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosavjht.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxzfuxk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcdtecg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuazukdj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdopuoo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mepdkokk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzttzms.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2rllhojth.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2oumndjbh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymllesz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxmcoig.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2byquzyjp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvqduaz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqdaks.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2oajbgfws.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvsjolx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsopcqt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wluhoajv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goumrbhd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zovcgiqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuulzuwk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuarcld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiqmsje.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjmcjz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2entiwhvu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2soojdopw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsqxdwq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpagsvzr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcypvnf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzerlta.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qplfizrf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplxaitp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrfndoy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkpeqau.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2brtczzyd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qesrotsg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hlegbhil.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lnljorve.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gxddzdft.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkzhdp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdjwcl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwrgyet.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2igvezfwr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2buaggaxd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuhkcib.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2egllcryu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2itguzzjc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2orbcdjoe.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyxtxuf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbljrax.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeponlhd.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjoucvf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwdbxse.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2nloalack.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrvhcs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tctadjqq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxcdywt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhhsfaa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2oegdqsev.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wglfisjw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwmjujf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjwgtnw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uksekfbz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwsouqk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xikrvnof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teslepce.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnfxwj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvqsfqo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbejdqyi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2eckhkpqa.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ublfjbrf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfbcfft.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mupuxsop.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhjzvlm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyepulrg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzutmjz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvmixgc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpztsela.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmgyodm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsqbgwi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvvlvgm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwouqf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwdtqcf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rezkovns.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kdryvecv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dhznrkqh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuduznp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbytkjav.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpakhcyu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2msdsujrw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvhqrup.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jhohzkkw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2chkgizft.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okhhvkzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcwqoft.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpsyzks.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhezgxmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utqyssam.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpxkzwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpmadki.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdprsdod.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhzjdyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqjkjrj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkdheqk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfgqdrm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvqemmh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxfjpzm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsbeaud.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyrgxrg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjweyjvp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsluigs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxtdcf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkpnml.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2meyejmhy.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzirphk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sktnlxop.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xypcpora.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tddvudqw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkjdxhn.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbvwpid.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsnsidy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2olvoyjvp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhjlst.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqondyjr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwodbxjl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvjljuf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgkjjco.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqqysgu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhkiwrz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmnphye.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzowsiok.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iguockqh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyvbuek.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyikanlb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmdfqij.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoigpgkg.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2crzsopfl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcilieq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwggwjo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlptipm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffupellg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtedkimb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2snkqfaog.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lcccqofi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxugpdi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2udktxuzg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtelcun.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2htofatpw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkinnpk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaqnhyp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mefhioci.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywivrhx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiuxota.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsrnczc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fydxhlcy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bweclquv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fskvawda.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwznsnpf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtqlibn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dprjsijv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2segpjnwy.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeuekql.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtlxdut.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbrihys.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsjnoth.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwqwtq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2msaxjwya.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iruhbfeu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzlntqp.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgwkbcg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbgqoxv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrrjqbx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpqhlgw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbeoiff.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxzcts.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jruhiiub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2spxjjniv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftlrug.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutxecrl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2idihmtzb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwcjsit.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlzrwwa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pipkwajn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2plilywym.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylatlxok.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqnxno.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkexgdn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwnolk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2outmomtw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwsknrs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaklaso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhthxsl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdvkokg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzkdfbv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdntovwb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tszeuisk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhwznja.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vmalrtga.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyowxqa.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfbkjhd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2akrbmdby.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxmhfay.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwftyze.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2riuumslf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzceztw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egbwubwj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfajyxt.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kshwadoe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxpmutn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyytheao.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvstwcd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dunuyugq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwfrrbr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2baveudmr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hozfgyfi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkifeven.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiblzgru.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxxvgwi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmtalyd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nouulyfm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszeosrx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufmiljc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqyerum.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffolheqh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxnsmgt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtttqop.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzqhqbp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkswzanw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtawajg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dngmiyfz.html


<!-- 参考信息 -->