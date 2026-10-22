代发 wailian999

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwmkezd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvubguug.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsaibhw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgfljzu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grxhqboy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjknukm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2hflalijm.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2njdgcbcx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ambiwdpx.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmwiqbv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwsnzrg.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnjcdpf.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iqapkxth.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjlzgpa.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlfzixs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhsapbv.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlcctto.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqejbsp.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvknfwhu.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lawuuefx.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpznqowm.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtqvazt.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2xkltlukx.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvbvoxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niomsdlc.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2elsngmdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvphqbmc.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhmnqwo.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnkkkzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnqvgrf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skuzjzzj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2empzjsyw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfmndxd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmycpse.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvmzghb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrstpbl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oatrdipt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqixyhw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmuvujf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdavqvro.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzfddff.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpviogh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goflthay.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcgvjsd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtmkghf.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2axcfecnl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2okdullof.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvijclr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moullrop.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapfenjp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aisrbkdq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuhoxny.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2addtsmbk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkklfxdx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2flupoxun.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgmtlzc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzlosnn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isdhnbbb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ymztcqmj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2yicyxjzt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrjqzns.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfayfyk.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqhnwix.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbesqui.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhjjvey.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2afjfwfil.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrkxxgv.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2klbigxxw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbuxurf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2twfvlgyp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nccacnrh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvfxetq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2crwcmdxu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbsiehj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvhosjs.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtzdikp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2txutcgzu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylkcmiv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pesppntb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkqrlnh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkorszvz.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2coajscob.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxdeosb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhettruv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrmrmqx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2avpucvdd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaupabh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrmpewf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2txslxbgs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2paochple.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nriloacm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcwarxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njpawagd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgstjvvd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpabpwj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kggzlfoc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuoqakr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydofunyq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtebytu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzzwdn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdbnilz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoqofxr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuolmtt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzejci.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdfmwif.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjrsfby.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2royvkrko.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kskhibez.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2geglcbjk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2aavniloo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2bydgidtf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsjdprk.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfgfpzq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzixxjk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oddhvspu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhmgluh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2anmpgrrr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrlczwt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2nptqgonf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xirejapq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsolksmc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafscae.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdxdmqn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2orsdfytq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kskkdfzh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbnaguj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2irxkkkkc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pamtfgrp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyozczi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2irpukjjx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2avssojjn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2dawdiapm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdxftwf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2iluvttnq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpstnnpw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgoxwuz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hujzjzes.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpudjafz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjvqkpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crzyjvvc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbsqfaj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2japmunju.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmmiof.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmzggas.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjwhsfm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2adczutfr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgrfulc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqquqgi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puiyfdno.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmgzdlm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuxrkjf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnrsepg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvmfoli.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2scvcbaoa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2pixyzwuv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2aolpmiqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szxziena.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icquzemt.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhygnqs.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjujels.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrkkwyl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdblemwa.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2devpzjgl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tajiwrlf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwgfwat.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkmelwq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeqqytf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgaumfn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlllev.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxurxx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgixnkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zivpqlta.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbvgyjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoawqyv.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yalqtjmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlzjuyr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaomska.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjdohay.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2smmrjgok.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2udpmgacd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2yntapkns.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjdagew.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymundhfn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2krasfxjm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzswjcw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdudvqu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrrnpcd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnczxrb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2piltvkag.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgjosbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdaqlop.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsahbsyc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoundec.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aingqdeb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vndqqtog.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ykomjaau.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmwnkvp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmvphgc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmdwygc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsiuytl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfxqcpv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxptnyk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpnlyqk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxlcmws.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2oynnzrop.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzlkynz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjpvqvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2warrznpu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmjksbq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtwqqiy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2egbxivdt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfndhf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwvxauz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bebdxqzx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxpcdhy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpcaksc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lhreervw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgpiahc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxpmejf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkgopsx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnwyuzv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyjpjgj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyhhfyb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcipmtau.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ordrgacr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ausjskkp.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwfskog.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2dagdfuit.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwejadf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxskglz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhoifyo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trrypulf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2agzrgczw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vigcwzsz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxzbicf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxktdiyr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouewsdtx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdtosen.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfmskri.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2atzlawrs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpcpdu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjhowys.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skvmnajo.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vruypftx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgidzma.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlmqsfy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcqtjub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwflgqw.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnreion.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwsujoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2flzwfkdb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2inicplrk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikjpzwb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfncjrn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kokejawi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydikbcdk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjmhvlr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpyicez.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnonzwg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2obbkfoyv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfkorou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiuozgg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2medyakud.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaufhht.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaoealf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmastktz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkyqktt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2otzbruwx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2sywrxygx.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoamcwn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwplvsy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vgustygt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpshxlhf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2veasqilf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2oawecwgq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pztqisru.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftshmbfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqfgyvz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyblcda.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwwqhfr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjqhodp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mufgrydf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpirdikc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgisbcts.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwuqsfe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqguwehl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgookze.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsdwqea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtolahs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxrgezu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjgsjo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2voowuihp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlljblh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kovppbyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwubkzl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffuytcl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtxtopl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uezapzmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvvqrom.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2scujreoy.html


<!-- 参考信息 -->