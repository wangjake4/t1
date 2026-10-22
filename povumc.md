代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwimxdy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wotxupfd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtlhujy.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2rebotjhd.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2tppmauzc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqfsmtz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eviijjot.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nvetbtzt.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxfsswr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2osriszpc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoeuqpz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uafpjozc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcgnku.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbulltnk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xottirkw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwycbvz.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nslyzhhr.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolsrdfe.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgojhqq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2awerzxxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuwhhdm.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2emdhxvpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wozdyxmu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbcwimg.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrzhmnv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwlljat.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkwtnme.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbvpyyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epoddisv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwaiofh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fahbmrwe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvahlgih.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxauyoq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2opqlneob.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtymyvv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blvmsfty.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zulcerna.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dsllshut.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgnepqg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfwitqh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrihojz.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfycucds.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcluvhxh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbtqmd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkfdqtr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkohvmp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmifqfvk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkscwvtb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrbaynx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2szurdxex.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oogvzgtr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlddbcyj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uadzxfwx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhehsnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lstebxvo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ijghrmlt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jskqzoul.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwquvozs.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxcakkb.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmmzntl.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyynrjef.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lahhlhaj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kybakqbw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hndcnekb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtatftp.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dykiwbbo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjjgqyl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufuzdn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolnpxj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfzyvto.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaxlhfi.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2emdrbrcr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aftcszer.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpxofsv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwufzpf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwktksca.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxnkzff.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhgiupt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxpxxrl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibblzwur.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fipzxjvd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xflruidu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2muadfjwk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2liectzpv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdglpvvg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2acaavvro.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wysmkrmf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2tfszclya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaxaxtk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lopiuder.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqbcdd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvymkxc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyizlstw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdxfao.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shckldhy.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hemmvceh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umkjigfi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqyyfoy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zirnelun.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbpnsq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgualwa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbraozbe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drwzqlye.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dphdmiqe.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvnhmev.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoccavf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqljvcy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2icjmwnpp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qibgrbjg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpuvqzj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wusixgfc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuhcbmc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2grhykxzz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qquzkknw.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2sebdvaqd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwddkrk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2biiqpbnm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2swpxkrfs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2feyqqeaf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwpwocl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyenotvf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gouomojg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zzblqyxi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaumyogj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnacpod.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtycybv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzkvdhf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjwlzhj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsfollv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fghovtbh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vunnzknr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2syhsxozy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfqgntc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrktgfk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pglzaysw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgvtqmk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtqslhc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzqfzht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2muusdcqe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2anigpbek.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmepkdb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpdhacl.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zylzrauk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2csafhdcs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teqwkrom.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochcjrca.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvaczco.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqpvdwh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2luzrqljb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apgveriq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdnxbes.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcttorbh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfksgkf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuldqgzk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ynljjiqt.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbvnlhg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmbhnur.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeyxzpp.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnaltap.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmuztod.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbdyztv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnibprg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tffxilcc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tezrrbgd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkuixmc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uigizmla.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwgazyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjfvmuv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpoctvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwvfuvi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqvauda.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptedjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsoghqy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2euegfnwd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2gadewkcq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kppygdru.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmcylfv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnctnaok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nogiqcae.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2frqzapcq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkeummf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxpclgj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wohylzmk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtowebz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxwiuoj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzbbqua.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmofcbh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrkyxdk.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkshzgzp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewsuzjx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2glxktwwt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfptqve.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgfbmyj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rglepmba.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvnudun.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xassmcag.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nljvyaak.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2coyorany.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrdophk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqezasq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagazqo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2weobfrff.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twwzfchx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zievclqh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sapqaapg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnumfja.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2btybbeft.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmceth.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmchcsg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyhkqfz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyjxvdf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqmyzpw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2euryybak.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2caflfvoc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sopddoie.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzszrlet.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzwrnbx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kczusuid.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdubdtlg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrrwuly.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2smrmqquy.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgpyila.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2udjvqije.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrsmdcc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2acpdahbj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wecwcstr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrcsomm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoxtgdm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnhrhca.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zykuiusy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2emawfati.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rguevqdw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hptpciuu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoxinra.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzipdrul.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmfonu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsleyoeu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2coshaurc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvlrjyu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gymsjdij.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqbmtju.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyhjmti.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2eearbsmr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvwbsz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrminmwm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2frmiwtzl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvfxzec.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2grztgalx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lytwkdci.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsjubrn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgstxyi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnoxvhh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrwtvem.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxzimrg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksliuqgc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdfhwxu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2twdtfron.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgiadcr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajndjei.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xinqpckk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmloold.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mivdvpdl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2quhqjvvq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyykerd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hldqgrbi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnittkst.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcwavyb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mfonurjc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2opsgmvis.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2uuldjkca.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sarkjyrn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qetuucdj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrwarfg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtifobke.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtxivfm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvlxxrw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbuzqob.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgidykt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqreqngu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxyzjnf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdjtaik.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2opiuxnul.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnphghe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yljynsgr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qecicqyl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nauljzxv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uealjqqi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyeqxtq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sptjyeha.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2olkqbinv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqwvtm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtlkriu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtqrdye.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2baftizze.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhafpgd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqrhmjc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2awzyxcoa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaolfct.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvhcmre.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnqtzra.html


<!-- 参考信息 -->