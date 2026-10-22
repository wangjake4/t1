代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzcmosr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhuepgo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2anmluvny.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnhlbmc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2frngzlpd.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuftkgu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvpdigy.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvgfcxj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqbyofz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmpnkpf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbuyvxs.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cplanxmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llokwvpa.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxewilr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmngyrk.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blmrbtfd.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfotuyo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdreyznf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlddpucf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwniwold.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrsahdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2secsitre.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kufkishz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loqwrssj.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrkdipm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwfqqwf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbwvosm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phhwbajw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpaetjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvllwca.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jibtmzwc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhprswhp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkttyx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rypvwfhy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzjzeoj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txyedpum.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buckdekc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drpcmkmu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whansjzf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbfupxx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnqqwwu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2skijghab.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiaaeer.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgokdmov.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsnigco.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haeyhsni.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2awcpvcqx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rckkjgkk.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nudwhusm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqztoxtx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtoelh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqrcdrg.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhfrlji.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsvirbj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2truvqkqs.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xshqbtol.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhzblph.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hbazwitm.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2owtqvpsv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2colkddvo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwzfbjl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2epitxkkn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgsdfqt.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxwpaxj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjuvpeq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkygnrl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcesdcg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjbvush.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqfgqft.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2shvgijos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhchcdq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzzbqfv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjztwjrh.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammwfrkq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujopzakl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tavhuqae.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkulcuu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vifwooit.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ajczhzlf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2niayrdtr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pchbrzux.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srjoktqi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nehjzdwj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ljecwrjz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfhbimx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2berhzmxr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjynfv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zjucizas.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icnjimvw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amwieolu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhzbegs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvddwzm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnggro.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkagrnm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrhimca.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbworxs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wlntrzjf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoydqdr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2lodnaaxy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2plohamlx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxkruah.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2grhwdfpt.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvapckw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ooosajjk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gycoqsfw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjxakxm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2supexgaz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vycpwuuv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2holfjllo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bquzufgr.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwawlkl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2jnchvlkt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzplsmfq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgyisek.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jownsasn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbamfzmb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezyelx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcaffxx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hevbscaf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdznwfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2njshwlye.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ofedoazj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkfxbvv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kkonhpnh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdkluq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdqqwfv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyarkhjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvxxcv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjmtnvh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2roizshkn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdsvuuh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwkidfe.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xflhfqhu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrjbdsl.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsokhuez.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sprcyerj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmpdztq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zahvnrck.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhlfbo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkvvdks.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqsrcjc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2koupmpaj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkcugjo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchajcp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdssxaml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzckdupm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2azmaslcx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxhyvj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdilbcs.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mexbrsge.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdvogwy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkjfnnr.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qckasqwq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cieowhwy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jkljwrjz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zizaenvs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrvhdov.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nioirkvg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enrkucxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfimfqoo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkyvljp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwobajaq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2exyknfhg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlvpqfs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tezpkucp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiglhul.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwpjidc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jusjiyrv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfxxzny.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkucnqu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnihyh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2odtthkyx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfjeqpx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxruakjh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2icjeopni.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyisozc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xopayydw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegtditd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsufuka.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtajwqus.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fjevfdol.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvlkdsu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycxcjn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzecwsa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyycycdz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyixruxl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lydgsath.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2assxzwxs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcwrcem.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyfahzj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqeixrb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rclspwwe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwulbkki.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbgngtp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdlazdn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxwygbl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgszypmw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyquyiv.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2srciauja.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ojstaqyy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioutkcti.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrmsezx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmuizwu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukrjfsj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzxyknv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2idkxnaga.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmzrqo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkwdfvn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgqhzhx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrehwdn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yblsohmc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkqrqxs.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mezbxedz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrunamsd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwaakbi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wheifich.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umstihia.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2oukrrwhj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvtakac.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnuexmd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsafddxk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjuuvq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2boljkmeu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2myieuqpf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobbmtrg.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ijexnguq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfzwhlw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhgedhf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2koijwick.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2izmhotpk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2coamzyac.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyyokiy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cortmkfq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiiqnpj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2otmbddwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxbhxwt.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwzktrg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxloqia.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkelaino.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemoazzm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smiefroz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhnnksw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqclibw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpzwdap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyhumxr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprzsrfy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhiahme.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhntyesb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebjjyu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvjtsjd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgdmsvo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2behsyirj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcmstke.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrersli.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnrhhga.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyksqyny.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqqiqmj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlfccjv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftljbji.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2obzsetel.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukastnww.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvvpnz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmhwnqn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bomvpfdy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtdupbh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmvrhkv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2emiapprb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwheujll.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2syeinfwc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzzvsnl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyitpcqo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwjelly.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iopdejqp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvklcgzr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbvseda.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2etxqbfks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wnethsie.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vczeuhet.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxuykna.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2imlzggng.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2skgeqnvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uftjumbx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvqfhas.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzbcaid.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozxftgc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzsnhxi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtruyisr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgolqbce.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2seqdadza.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jylmbnmj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmqfadw.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hoynzjgf.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzfqrle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2byycgueg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rlenvagm.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkyajfb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2movgddce.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvxblrr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysdfwnd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jivohtpx.html


<!-- 参考信息 -->