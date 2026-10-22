代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rktonsas.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkisqeo.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqlekbk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdnclgs.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yntugvkk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbobwwzk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkolevot.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoektkb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuwpiid.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhakolmf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2aorbkpzg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzurzdon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxadaky.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfmkgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isnaxgvm.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2peeqqrkb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2krnoaehx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcojago.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ersiakke.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqauehk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbmiwvb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svkjdpjx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrloojnu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szzyzwqn.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xijapdzr.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcoszxs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhttaggr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypotayuh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkzvyvi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzbkgdf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbznbvl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lpokpkep.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wueydmxl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkafmalx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzggtu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuqqtsn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeozldyx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpwedru.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqzeyep.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqondbr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hefkbihr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2kilxefjc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhuegef.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkjeqyz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijshbjdv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrdxuyy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzkklb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2nooococr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkosqjyr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2soqichbj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcitknuu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2atuhznql.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsyuarz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bsngbwcg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aikkqzif.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsokstgk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2anikgjez.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvoyap.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbeepp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdftugo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2asenkcsh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdvqugc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2isszsngd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tebqvkkd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbeenfu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tceddrlh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzhgyzk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkpszkg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjifmwnm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqnnlz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxmhnh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjccdwg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoosnva.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzqtbam.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bedtdsar.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2nadehqeu.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegofcim.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vwythcrs.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjaxxdb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2cevtkoje.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjkdreu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlvyvyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomqubgl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaycgvn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqizzfme.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fymdmcyb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzfwdlw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2knglumvu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowlnkcd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvrstlq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mljaahwl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfrzwdk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhfofwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjumjzgc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agqiogwj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evclpwiu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sjydexev.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nizydnlt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlrtfpt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gknclebq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgzftir.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxidyrf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2owufnqln.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bciizbow.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gslvfwtn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2shftoyce.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2roktqkrx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2unjzeeod.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xizuavxs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbldvzex.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlifegs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkvqvsw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kumistbv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2awyqgotf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjeezra.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxccaoh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2higcugei.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwrphvu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlykjamw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxibyrb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzjdaik.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyfsfud.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsoqxgi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiskafu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2htggxfpt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvuabjd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoatsuw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvumnx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsxqwxn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2avdaorrj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2njfwhfpv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgvcdlh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hypjifuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsvnqmb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvsjkaq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2slgydbbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bylhijay.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfepaen.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzgkblb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqegfro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqrjott.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csydkyag.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2iugqmmeh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpurllgx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2robhcsjw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svmzviwg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpeqrus.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gxueonip.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfprdum.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjyjnix.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wepazfmu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bwckokia.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gepsdxsy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iozcwrcp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfgiwqa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znpsxhss.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wwycxupp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfvbdic.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpdnvre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxlkazg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2yosoeiaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqapyar.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2biataslm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ldebzcky.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pscdzhvr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsjshor.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2rxirswxr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hvewwssk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvgoyb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2efsximuu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrqorci.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sgohdpwf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsgxdef.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sebnlwee.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuznken.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrcrbzw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mokecxcv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2grxqmkfr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbhxcif.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjldrva.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbqqegr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2awfrlika.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxwpdzc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2brgxqkrg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtycbpw.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnwpwe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfajobtj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbiflhf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afaeynpm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mewickcj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzbyjhb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnmslds.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2maawfono.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfclwtkb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juglqaxb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduutajf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxgnvvw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhnmknq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ftspbelf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhsntl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpqcohz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nweauksa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iubsoiyr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphrfjlh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iltloojd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2btmyvmyu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhepeok.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxxlrgq.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjasyl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yglfadkf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtjteve.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuxsiqc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2btgudbqk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eifixcbx.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2exmpfzyk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2klrtbezv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emeimodo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmotacmh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzduocq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzedjkn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhioro.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnymdih.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtndzflc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfluhzs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuednvb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pytxmglt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2saoauzvq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbqxcmm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oepqzxjf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsieani.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xixudzll.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwrynb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plaozlru.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvngcfy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2boppaaek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcxrnvr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2osszsbsb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfnwjks.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcddtuuo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjshsyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisxqvkx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaxzjkx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xidxggxi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2iextdkdc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2grczuyvf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nncrvkzt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwfcnzs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqluukzl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwoclgm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhzdaki.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkgdpdx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsnfmav.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2czinqivy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsjiccj.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wakevmbv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvjndyr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnbbjiu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdfjcxp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rarstrns.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxfrzmt.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dntidkjg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vssfloxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpowxju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmebhfos.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnikplo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbijnqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpnrbqt.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfwkcaa.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlngjtq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgqbqkb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhgbkua.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdiaswt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkkizzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwkzzns.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxqtvne.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2thjglcoq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnwfahu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwclfsnb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzlqgio.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrfqiyw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2volwxpdp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkprobc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaycagkq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhgiqvy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzwtisi.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itwgdfld.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqseilaa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswynjt.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjdewhi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2isjrofgh.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnccesom.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2medvdxfu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nznwqmij.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qavyiakz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lxolhyrk.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsoahci.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrzrldp.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kexjuxoo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchehadv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kronfrjg.html


<!-- 参考信息 -->