代发 wailian999

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pguhxotc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ettttrek.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhensbe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcbkgqk.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2pkajcoep.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2andfzgkk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyprlgan.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcbaurq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzfakuw.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2welphylb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2niwofsmt.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdpuxsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adkasdni.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdjbqhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdaowgf.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxtxmgq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvickyt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urzfaajz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ethvclsk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rflijwab.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwlhogt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eusnclvc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvifhlao.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udcdamcq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2npmyefyz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtjsnvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqomfqhh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjrsypz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaufggwn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsjeujn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrdgdlq.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vlretmib.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqihpane.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqajmxot.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipefksl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwvkayv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auyoniyw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btkhhnyg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfqmti.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqiizwx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlozifm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaxwyii.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbrbnvd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwicdejm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjplfxdl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgxwjdi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uyptdmlc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujicnl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoxriva.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzvhtag.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nerxxpcs.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtrclad.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xptygspr.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsasgqw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkntzlf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqedajcf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rukktrtw.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2oteeibaa.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rurexbyw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nypwplyi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcfnyyn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgxlwuo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkaprbk.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2htzskufq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovziqkrg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwanix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmznfxi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2agotxuks.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkzhuow.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xblokqxf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2comamrpu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvrhlwq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxglbsi.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkshwzur.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzqkbw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxevjfd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2keakerpa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2suwgjhue.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzbspzy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2oimlodkr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysreldtx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgrmwym.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zildilwj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfjsfbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmjyias.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkbiccc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umsfkgaw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyubyilt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhxddfh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auidaboo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkpugf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjsfjho.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqynmxfp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvvoukc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeojann.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lskccnfr.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmvjhqs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2sftkkowx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2nnycytrt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtykyik.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsfkvat.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hiflqvkf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxigskx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2eorjfbmq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2byszteyd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vljsfkyi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2djvmefyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqswacrw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbugfujb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrfgrqj.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajkudwq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmitwgp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhryakj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2aspgmnxn.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoehwxg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2sylbibqn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlezduy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bedbvmrr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxbakmx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2krbwvbht.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpmiegm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnnelze.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxczzch.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwlbpqv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfpmwoj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yguikyfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fatfyqrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hccswjio.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqhibdz.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zptrqaas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmfhaou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlhoerf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eariaobo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ktupcqdd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2skrpuyov.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcswbtwe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dncurrrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxjulok.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaqpdgq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbmfafg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2mavzkcat.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2csgkcxum.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2unglypkt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxfzbie.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieprzsxw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qffmrqna.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lapuslsa.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mjasdaay.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2btaabkty.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpcssfi.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmcvsbs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dhokdlza.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhcbnef.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2typyvjyt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjvuqam.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmibxzx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeaqioi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odbozslw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmmkwvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpqykmm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjxefs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynocyskk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2khigqdjp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxqnqkq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2innnisjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2siieehsw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2imnqnpyk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbgcdk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmutcd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2byzecaci.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2wywvtajb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwlmndg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2asjjenns.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wblmrceb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfkwcnx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnpljxh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhxcucr.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2buhblcsl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlgcxmp.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2arpuuztu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thavvqvp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhlgofj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzgnmtu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2aaskqoby.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2apttfqnl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zllhuytn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnaviqt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvofaqy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otmekltm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qncllcbp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhmycge.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erabepoy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2uegsilnp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcupykr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgqlzbk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfamuvti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kquvbuln.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eihuopbp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtcglbu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuhxpal.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpqinlk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxizbpmi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvabxams.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbjtvqn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsrjaaw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2osinpzeq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvhrsy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcnsfsd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfjyvlp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqipzvdu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iotxmvjb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2asazgbvn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvcotsw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnwiyvc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnaxjkm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkeygly.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mnauqvod.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwwlgev.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbvrrcj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbahropu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkourph.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjgpvbq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2feokwzhj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2alfrsifk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyloglk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgmlsen.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvqykzx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgetcia.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiaxvry.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2huwzajdc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nedhgquv.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkahbvjg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aknrpkpf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnzwsfc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2iziijcze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2joaesrcb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2joheuxri.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tfneeibm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgxdcxg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2laagxwqk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirahjml.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuhvuen.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxaednu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2eclltece.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrhtwsk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcyuxko.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaocbli.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwpefke.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tukxuqmm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzujibrq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhlehaz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxlelze.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2veludwjl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgowpha.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsoeawl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnnshrv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqqcwor.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qorqjnfr.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhacss.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eljugmhw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoottxn.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvpmnfk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qthuvvhh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfvgbcl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knytkzso.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khjowgrv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiettoo.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itudrsmp.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafglya.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbieoqde.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcjluwc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2knudiusq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpchcw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyptrnu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxwsqvm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrmbdds.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2twyjvgjg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuicjxjb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqyaiup.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2yycvctdb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqerohrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbounzkx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iysumvme.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnzeedt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqankywf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhyirhj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2khkdbzuh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdxvzpa.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhunznj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fllffhhb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzuaujv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2midjasty.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbweumds.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvwdyu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlptmusu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zilbhbwh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqpuqm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2lewurnnh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaurbdb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqjogre.html


<!-- 参考信息 -->