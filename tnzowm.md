代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rhniedym.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2urduaryu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzxmcye.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2krpqdmfy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfnokuw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctlispf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdpstvi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bilpppoa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhomycvu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cemcqepy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2reajntur.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2chnxpzgn.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzkxksc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bmruhmkv.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rorzpmpe.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbovjep.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpwfgp.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2esivhtci.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xetnftca.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhyoyry.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpatkgz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeximoa.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkqfilj.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmsamkr.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtweuixb.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjlvxik.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hehuvyzb.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqbgfzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqokbzvv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiyguid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hldgefez.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrcdsoi.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bscxvzol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvatxhpd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idaytqvw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgycyak.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwtjvj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddccftul.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnuvxcc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpomwmxl.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmakecz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2tepdbqej.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhvrfgp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdsmgpv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xizcwrrc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2asyoxgny.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2melbzgdz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvuflzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubksqcmj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrtrqjj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvownds.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eehlvuoi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrftttn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wezotnst.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemgodvh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxlnpzy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxgemve.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2oehvswvu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpipizd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndkpum.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhyggop.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idpruzob.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fszxfmir.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2qfywqopy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2peragwkn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plazsxsp.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cngllxde.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2kekfjbnn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbyqgrj.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2scthnami.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2canmnqdh.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjzxxdx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dvscivqr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjarvmq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkbgaso.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2jgleoqej.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfvevdn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2kqycsnli.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2emoamxxo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqcxwnr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2teulhkbd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkpxphk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaivxin.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlywicx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfctgbu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2whfvhphw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaljzlkf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqddgex.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzowxpan.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrejgw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2geauryus.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqzgjn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyymnwt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvywpxv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uwysgoki.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ncitooqb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgurgqmo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjdduzk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuhlgpa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2sqngwdie.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrimlmb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkllyng.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yywnncmr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuxkglc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvlpbab.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbyulej.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uynthedi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mwelimag.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zspcclvv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzbqnzx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilinpzxe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxysenut.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hoisdcnm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2eupcbnrv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2duzdymnn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpabcue.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2umbbpcyy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrzluky.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ejahyzcg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2icdyisxu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zztyszpe.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzwkjzh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pulpfcwa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjjxipm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lekaybzn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlyeqgx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfavmdzl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bauphwkl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzytuhv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcsrrgc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdnjjbc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyutvxxw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwprrgz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsshnqiu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjnybxj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiftunr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yydbueok.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwfftbl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elcjgrrk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2khpggpjn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lloyyumm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zazxmeol.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsrhkoo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgsmsbb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlolofm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2dianyqse.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdulfmil.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvycooga.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcsfjvc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzugjec.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xveelplz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bibdhajq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztiezwy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbycnoq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfycubr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlggtic.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lahhebrm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afxwrbbu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjocgdi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yolqypao.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdqdshi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2risianix.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2splvkkzw.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxiekao.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvqzqdd.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxikcoa.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2txrufmlx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xymirzfn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmaiajp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdmfzli.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2repbeyyr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snfhaydx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wnscazeq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhdulil.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xztpnieu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajtckc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2efhvmhle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrvtwvk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjegkwd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cucvsniy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzcuina.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwejdch.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjizvyed.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2teiakvve.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hatnhnnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdegaec.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2knovmpgf.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhupxkf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2szfvvyua.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxanshsy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iarcuqnf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtcsbdd.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgatofn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtgqqmy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqidopd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dltwevms.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xddzdckj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoquqjk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnldhmpp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhxwjec.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2msufiwto.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihakzjnu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlnlpgr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzslqkj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2koccybsb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkftbwcb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurgtlft.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzdxzvw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfumgxx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvphbrrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drnksbnr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzltqaf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaxfuvd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsfwydz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnwfjyw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuznxqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsdramj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xluwzwhb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycncnaib.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nogapvbm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxkqmuv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xsailptq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkqzhkk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmrxhwi.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meybigot.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2znfsuhfe.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lssixqwf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utlfmfsk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jumnfapi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybnaodr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmifpqn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmctsyyg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpqovly.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2osxwnbak.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzyfcuw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onieclyl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zplxajxu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemypcf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxvbqs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2itvgfqyy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iemjigya.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ajasdklg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwfmtwr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oimefxld.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxwihap.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ksexzhwu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvanzvm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxrmfyc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2laknzyse.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2umoeipaz.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqihokg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2edvfdbaq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fualekma.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2plaahqxz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqcenyk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2iprqdlhp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhcvtns.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mansermw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlabalig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzadopt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfgbpwy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvecizs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcfjivo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihodaltx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxuppeu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeqzlty.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjjvonr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxhlxhn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgbzqby.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2twjtxclp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnixatgh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxwexax.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2igjmcvgf.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fguqwfwx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2laavgaui.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmmiyv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2svqienss.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2cojsynsz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnafjt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmawrmp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkcjnq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kflvjvof.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxsygw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjanfck.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woacfjwt.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2spceuypp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvddlugv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgywavq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2weqkqtca.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfefmhce.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeddzhpk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2evhcsolf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhqgbzl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnmygek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vngufjea.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2szanjtlt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxlbffe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctxeims.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchshwym.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjavrcgh.html


<!-- 参考信息 -->