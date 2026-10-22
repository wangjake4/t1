代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2atcqwjer.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2fydrbtbh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpxgcja.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoxedmi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiitqmc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2danenxpb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmrqfvx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiejscic.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfdpbcc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicdobyf.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2taamtucd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwzjaqc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2psxinspd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2sixcznia.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuegemk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gtomtqxq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkegpc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eseemdqb.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eahxjzcm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeydbln.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2exvfiffx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrljlpnr.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfazami.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpimvshw.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyskue.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hepatqiu.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2srcoquyj.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlhixsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlupstsg.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aexejlea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phjzzgyl.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euucuboc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbxfrfb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skespdgp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnnddlh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2safdhimd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgcpvce.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tegrinha.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgnkbzh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oserovom.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwjaool.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoncnfp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwopytx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cloljwad.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmjumtc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjbyipo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2embgbhxl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvsyzgv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqvfcyv.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eixeadjq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2roczunym.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drnblnkx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtthkwc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbkjxvt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zelosjcg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzevxaqf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhxgcrz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2itkfhxjr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kynuevuk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbevoim.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkavajrq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rujkyehd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsccfip.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2isnbtezg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2naldqmiy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2psxcufxm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfdymgu.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcmhkrx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmilkcqw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyzvyrc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2assxkzsq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjuxvf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvvthi.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpazebw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2usobnvmv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzhwmek.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iomqzpjq.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhmriaq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiwxoyd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2atqsbdmf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcrtbdh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnmthtq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbjtsjg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfxpoeb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2islzmqft.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hmliizmw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgjvpvt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ponasvvt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwmrhr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrbbznv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzbvwiy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqjkdzx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgfpbdy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdihap.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhtcxop.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnvmevd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljboggxw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnmkxcq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbiuhnt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeodqxt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhifowv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snjvuadi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjllfsm.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsmufmz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eatffrbf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2biijczkb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2biyjmzlw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2htiqwzer.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzimkwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wntsytjk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpdmyva.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgrcahq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jblftlxf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2guhvnerb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbpnal.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zohodmhq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rscjtuzg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqhbst.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pspajoof.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lpihyzlj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vokfqmyn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lcebxbee.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuxmvdf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hujbnslm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fasoifnz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlleqecq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubroskwv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rsielemq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezewhsmj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqxxmce.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2afmasmuu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqkcmwt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvazdpyf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgxcklj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wduevkdp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2muwpnxna.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2babpyajl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdnxmxz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmpdms.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qnseygbu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqvyket.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bggzsfvu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2uefcuihn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kujqloll.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amitixjj.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsrsdzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2czyadjpm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdknhdq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nddnutog.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2xewmshnh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxjsiwk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2glzrvxkl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsvrfmt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsmhbrd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrclourk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoneujq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rundynjp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpldlnkj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfxgpok.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmersse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhpjpyk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzzkzfq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmmmqmf.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qaknsqgk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2knyjxhjj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrfaedx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dkygkmku.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbkkqst.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaqafvj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyoxliq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2owdfnbho.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcroqkrd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhmmaxb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2strtpzdc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnlunwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvbbuwq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfpvbrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbiuqce.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwimme.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2drygvuzf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoiccej.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaancpb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pyietjaw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoeyqcs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhvvryy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyhuqvd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2yeknlnzh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rprzlnef.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvjcfns.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdpdaxb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwflnyg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2etcmwpuu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxgygd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hseqonap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwleuxrb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2avcgvqkt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xslqdrba.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpahcwk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oamdnylo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvrvpwh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiommuzr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xckyksfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtylbin.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2probfrzd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqevqsts.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjdppzr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdkoppe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sikuucix.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsicwruh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvcbiuv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxdzigg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwlhbcb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqcpdsy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejebzitx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkdigkm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iydikngi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqkqikc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvfsou.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruohxnqz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlmmuhg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dvchadba.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2llasdhlq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iufmrdcf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oloxmzmb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybinvleb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmsszfl.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jweqbuva.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kafwfgep.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2peuklxwj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqzdrvo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrsnngx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdcbdqs.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2irvasmoj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2aroposml.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfucaptr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejzbmzw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmosjzeq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtneucbq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgtmohs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2iszhlukm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2beofclgy.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmndrejx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikjbtcy.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwnanct.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqecaceu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpgxnyo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufavdcmf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwdcfdj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhevxbp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjvksol.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hekofjkq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybzrer.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2obrmersg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2oejjvrqw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpuilru.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqokevh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbllcac.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgthhcb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvewubk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sudwscqc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezakbj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcmwksf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsqxbve.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsikcwwa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhgmqmi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhxdlnv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjriheaz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2igkoipjj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2degqxham.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2urxxlmzm.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rujaedwb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nujunejw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbuatbp.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyuwlpm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphvlrcs.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zveajqti.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahracheu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsshhwk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcegyxp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjnxzqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsueurx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypkxczh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bewmdyzk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2seixpmzq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uovtreia.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2txlgbbiq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zulqgnjw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iatqzqvp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gexcahlr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgjpnkx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aebrvmib.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbjyjbc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2czksiezg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwryjrv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2raisyfyp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2sntimnas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lesmpljf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2weqvkdxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotkphaf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljyfrvo.html


<!-- 参考信息 -->