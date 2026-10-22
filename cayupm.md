代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2gudqtpsy.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzfzrga.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2abrevsmj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2covtfoki.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2razuvkjk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvgtigb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeljaacq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwlvcyi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2igkbgrao.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymixjtwa.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2efcqdsds.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzmugpc.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnyipei.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvkiozu.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ykztpnnk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdevvjv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mlamvlqw.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aheymvfd.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcmxfgu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rijubqfm.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2dagamrbm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyzdnqo.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvfuonf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijbivvh.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrykxro.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjafdzp.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqdletv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2utctwjkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgocuypf.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkrfdno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeefeew.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2meezsolq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2osjmzawh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvrrinw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqmhenu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkjtzyi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxnmdid.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsspzgh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsnnoyv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzetvdv.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbouxopf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtzxays.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwuevgx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdisvejt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyvclxe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfgusv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpevqka.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2apggsqlh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nstsdwfa.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmykvrwi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2janpixns.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqclnhtw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hozgspht.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsbftxp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipysrxil.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaqpfxf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ityphmxn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbfozx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icpjtfcd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyemyfxj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqpasfp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pohpfqru.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaovsyo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwtovyt.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huyfsran.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjljue.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbhvggp.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiqwgbx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbezdump.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gigfjumt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nemuqexx.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2gezerkre.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2epclxjyf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkwqtxl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nesayrep.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwxwjzu.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjecyuo.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dpctmnbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhfuypm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfpptjq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhqsqtw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pojqkejl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2watqbocx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwojbdw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuebkspe.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2umeshfpb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxtuyt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqcwusk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrwcqxf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhzurgz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlzilcb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljygiy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzhmuby.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzhtdpd.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjkcdel.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvvoslt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axkdhdvv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xalblfdm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjypaqzt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kscdwbwr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcotwej.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puzofeaj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxbwsfu.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfxhyhx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgouhbn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhbyirj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wyshfyvh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2iprpwfnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnhwqck.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pofacpne.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedrabrm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uklyusyi.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ykctnmpy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrjhzri.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cnesupik.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpsjqlp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrwlgai.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfmmurv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxfcpn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzdwdsi.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ljypbtkc.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkloksu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjiagvp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmxqgdx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzidpbb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwyrxdk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwknlac.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mefmpplr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxwtggx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkrznmo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnzxryh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzpfqmu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnntnvhc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzosaex.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vphiajuu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zifxxxtw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2phiycfsh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbydsmn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtdlabv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoybrgh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuimahh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tclohvky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqxvlfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sixsznvb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtoaoui.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqutfpf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2awiutsdf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2czbezufr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdxutga.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaicwkx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlydtfxv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bczixlwt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhgbqez.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfpcqka.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchwilt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gssetuad.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczdfwr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaxmqeg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvskeyf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfelbrkj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxaznnn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtwadtf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mabunolg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wnamaslx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzcijde.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcfxorr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtvrgqd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmnirkb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyneybd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkvksqp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpbfvqa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbtnpnv.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxlfwvs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eidruylm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnaubku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiluzbu.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsbkiqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igoztklm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqrdsbo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kudqdomr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2skfhehjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzceyada.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2noozllat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmvitdy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2igezpcsu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdqoboy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qygsagrc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxijrsl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2onfxvfmw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgbczgy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jktwyveb.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yujgwmbr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcbycna.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkxtrgj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tamtfncb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyougixw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pniygbvj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbzqesx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgxyrvu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwqenwm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasqdxsx.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtgvzai.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahypqnvh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddbusr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpdqbfr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgopryb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iugyozge.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiihncu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnukvkp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywztczng.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yymreaou.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvyaotq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjrfsnj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuunikw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoyeyzu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwjdel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfmhpny.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrccyrum.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuknfike.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2thrmnvxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdqrqgy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2upywmjwe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iivepkvy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbdpsnv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2binnrtsi.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgctala.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tklqvwzi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjryfphp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqtrtkh.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwuctjf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiephrd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtuylrr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfplida.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlstknln.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwailhm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zreqnhpi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2winskbhp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sycikarg.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wagqoxqa.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxofcd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlrmaot.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2idvvwbas.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldncfqji.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpfumeq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysecvlyl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdrvinz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2luydvxzk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaejmjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgqpyga.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vejsejeu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsasnjny.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzjghrx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkiihsn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2khsfrnlk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2axqzuqos.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpxjqaj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtvpxji.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfgjrsd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfextooz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpkheio.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2coiubkln.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryechwfh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2meokammf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vouvnyfm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrgksfr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tejcymyp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uawccrfp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rbewdook.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2piqswfvo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgksxum.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxengve.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwonaql.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjroodh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2stidgbxa.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2feilchue.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ueskdlct.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuwmqwb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgbwctu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcpqaox.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eslbidma.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsduynbc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpqhyyi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhsllgy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idjzhlhb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efhajzwy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2knkrsvsg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjxsvej.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2crcqvzfh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyonzxm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrazidx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgezjghl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2norzznao.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2jszfpacj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eebvtblv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhwvpld.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwohppv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjmndhs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvxacgh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmtswtr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyateddk.html


<!-- 参考信息 -->