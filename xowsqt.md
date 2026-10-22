代发 wailian999

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnqenon.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvebgir.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hlipretk.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxlkmcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxmavny.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkbtwxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxczvla.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkfyied.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmuixkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxpobga.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvvumta.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxqvgxu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgvkuzi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gogbreoc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vciwbdoc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprttptr.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqrxgqz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfptcpyk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdepjxq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjgcknq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkaanxw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hwakgasy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqflzjl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bopfxdmb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aibrjzii.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaptsyd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzizmyv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmhlooq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acqxuvls.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhhfxph.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbuqwrx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bavhuxdo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoudtum.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxbanxg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qawunjis.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dltjuzay.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2adtchwma.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvonnbxs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uiasbvbx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzocazu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xroxygpt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabvrln.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxibfazp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqpcdeb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pldfbdrq.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkedenhp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzbhxyt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnapngao.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2obrhwnpu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcegotp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzarrzkh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2tomlfzvo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vctacilk.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cqanbruu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcapzui.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptstwowi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeuinmj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2urxgculj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutyergs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekocccz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctvevcv.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtbvhgq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdqdgk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjcfngz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2afphkazd.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgdrurd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smfuipdd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkhdsoy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyybkkt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2aqthelip.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjzxdbi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2nglwehih.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaauxcy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbwzmqi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqlipsf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kykptkqx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemqptpn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvhmtbx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxpndbw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiiiugx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mddwziou.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltavvmmq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2chmyvqcv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bxufviep.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdtaaax.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvbyrby.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxxttqi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgikss.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dtssxuxc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdwtsqb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2drtwjsnb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpqriac.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbztiip.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjupiyz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2grjnxrck.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2moflrqiq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mimorirv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjbpywb.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkllbcz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjmqttq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2utmkuvms.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjrfbjs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mallftvy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpokvsw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vasvxtzq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhbgozi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2reiofpag.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2upxcyzto.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkderad.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2znjloeho.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zldzbchd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnwkqtx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgiyuzi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2plvsvtnf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jchoqjny.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2acwskhbd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvikpwp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnciiek.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2pffteyzy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualtjclf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqozmpow.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbdqauu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2iysvlkxx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2otejatti.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pragyvim.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhbcvyq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnfovv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2akkcdpsw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjsashc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pttjzopx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjlyaao.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nucdcrco.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nogzvkmj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrfsce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uawucjbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgdhpxy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbkbjmi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxgdmqu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ierygfjf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2shiqfbek.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2udjnpjnc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdztpff.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsfkglz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ublelput.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2irxtopfi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlodjye.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mkemwvme.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgzuafm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkfjvae.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbfypkj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeprcimn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvppgtqi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfavvbba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnevpayi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwpygl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2nnenklxq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2adclwgmy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2utqpubxi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjknfbud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkfzkxq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrrlvay.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqknjrmn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2dthksiye.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mimsxajm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrbwijk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdoictx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uivghmkt.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsvebqs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vglrvwdb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkotiwhg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqjzjle.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmthikf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbidowka.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbbyvja.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inuqricb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2brqfykwl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2momfriwl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alatetkc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sijhotsy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamfjdbb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cahwrxae.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfucwxe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogktczd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmswbvls.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvaoivv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvkscnx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxcmiua.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxngdlxm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krbyemzx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhclzyd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuvbphz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjbsrgi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxzoraw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuqaoky.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2utvttrdi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkvkpzu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvpspxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqhldud.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnssyaca.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dtasexgg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzkqssr.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2swxkuumk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xiexfdsq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdpbimr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxaygbd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbqtsny.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nndaxjvx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jincfseo.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmkucqg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wltudzur.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypephmhx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkofltlq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyoshxh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtkocnq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwqrshv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwklftcz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdlrern.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jdttlvkt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2turkdujm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmuhhpa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrocjxvl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqtwhdz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xalyfzzw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxmywmc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaewgha.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pikjwkku.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2oimkenzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhupkdzy.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqvhuir.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2mniysyac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnckplj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnbtug.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwfmjtr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmygnms.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrexjhq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqplwwek.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdqshhj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yztqbhuq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqoraz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhoxxtr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhxirq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pjixrlup.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2seevnkse.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvokwbb.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdwdgjo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wztirljj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnpndws.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhxrwuu.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyukfjs.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpklyetg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzzzhsy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpzqiqt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hitikljs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tukqozoh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgyfddw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zibqlkyq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuzofny.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kklhxkal.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2japlbefx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgfoneq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuwrqie.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwojtdxp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dndvvllz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuuvmbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujoosd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sylnkzgy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpflbaev.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfevthm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqqukqx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoruise.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygykklsp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2acfzyaxo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwqzmmn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqudexqs.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbxolkp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjipfekk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2onkajtse.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvxaktp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fslgzvru.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgmtlv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2anzpzcri.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2glhzruao.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evdxeucx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzkbrlb.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcqtrnb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2twohhxog.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tvspxxdy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2esmoovgh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2etyaffqv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2cskpumjz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbscdqq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aofzubnp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdogypy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhncau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2asgcfnjl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeabyqx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdccgvw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2pufbnwaj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2puxqhell.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2getyfsvc.html


<!-- 参考信息 -->