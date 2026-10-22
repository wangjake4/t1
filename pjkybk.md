代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2qudhqiac.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zncyqllk.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbozmnd.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjjemsm.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kykxottc.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzktscb.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bkboylcz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sirjwatc.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpbuoqz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhmteky.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaymfcj.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkulaby.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2omkbqvcp.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzoyrqz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jckfnplm.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2okqaomrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaxukja.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2snxnojyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2goanwhci.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqhtlrc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnhybne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaohcni.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dweswljw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htdynfca.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdejijj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzwrdau.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvafkgzf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacscyz.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlhgzzr.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mtppycxf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tonxyfji.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uumekqcv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrhkcw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhjjtit.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvkqkgt.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjduncnc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsgrgbe.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tixpeeaa.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoovsdjd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmcemvo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjyhcqd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdmgxul.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnfhrjx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjkbvyj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfbzaxz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxyezqm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmbbdqu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhbita.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dprcwdch.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rskdssac.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhvmpag.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2uslnoutn.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyupzij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hflqoqhp.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzykiyca.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjdrizy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2affbpmsg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjrhlzf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiajjnxp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhxqsdq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hodxcgbl.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ancstzbj.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2nskcacxu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpbpezz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeptweg.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtkifys.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cctlcvzk.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymleevw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bysglahd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljwlsz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2atceltyy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyrulcl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2brgdkmil.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlygjdsv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwuwrgp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbtsjgq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fctkeemy.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2friejnrv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzveuumb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gqppamch.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgfwcng.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoctnde.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2brznqibz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrjsfoh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icjrbivm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclvamft.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juniaovr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvjbidd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adasjymm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2icsojfts.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkqykzr.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mrastpks.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwjdxdg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxncauu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2clokfken.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dgomnxhb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aynrjvaz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzkplpw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnknjmln.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgorsqq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mueymqyf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuumgen.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfrcsh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnileoc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjgpihe.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdsiefk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wubkpduc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2umkynbgd.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpfvikt.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwedyzsg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxlvtek.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwmsvxp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2psuoubil.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2drauhadd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmscddks.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2rftnarcv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2azorgfmn.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpkzoxz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2efczempb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgvsnwh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzucofi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcsgltk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxggmdv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxynltmu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2dktionkn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqskidy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidsndj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqpjsxi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiworgc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mifbolja.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jquoatrp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euhoxjwp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuitqdng.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjuqeds.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2prdyzccz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qirwazyy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbljtrje.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqklnmq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fijzhily.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rymjbhsc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrecete.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmrlhp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzonbyhe.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqhfbhb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2qukxjnlc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbedpke.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2oivcsctu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwnojyv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noypbykn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnhoyqs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhciqjr.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2apyuukdt.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2manaaggr.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eildhgpr.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjcjodf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2artfscgz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvldqau.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2evqxgoei.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhrgks.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwzwjji.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxomjib.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgerkrc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxohqrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzngfjwn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2txsdwggp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drbvqfgw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2soxefqtl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ydibbbfb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdctdzl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzopsfnh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtpncxm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2juhgatdu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2htankcdd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuzlkpe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyuivte.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfbukph.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqkgydj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2epgiljvo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huvmrplj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2veahpshe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fianinjj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziamohrl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjvyayy.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axdmblbh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thgsdrux.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2stduavxv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymfeuqa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2wdunxlcx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqnypi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnzhyk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambcidlj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjocgnlu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cblugsba.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2epizlrzo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunthnyb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2barcfgee.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2civycnmv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkgorqc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqkjbhg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiygghrv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iznqcvzq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpzoktk.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqukjik.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmwxxjg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlkpkyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmfsmtm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnyyxox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmqltcc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobnpkk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2omdloiaj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpwvumd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bpklclep.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdhinfs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnyrian.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqegpiw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsgamr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ziesbcnd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtaniqb.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2libogxkr.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpllchj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bhncjukf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcbretn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2asobkdkb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsppyofh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2borrjeay.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2osmtrvqt.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpgzngs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsyiops.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeovqwit.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiqgexo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnjutda.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyuyhzm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobtggiu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sabinkkg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyzpquf.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwolhvr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jruzybnj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlumjet.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwshbqpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuhbsep.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtlbivy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2obbdodty.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gysxpsql.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkromcw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhuwtbs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2axedyagy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwcxusa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2awsfeftx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jateoarg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdifuzsn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiwrkfz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xausjrev.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hpamglbb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sukeedfc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbvmccl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbyzklo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2utiavenm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xchegbyz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuirnuy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2tefnotmr.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2enxxxjya.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmvarqo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrvmund.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpsgevv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfpwqlw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2mowxrmuf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqgdnps.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjeilgh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spmsruks.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2npfviodq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmhxrgv.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzquwyoy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgulwo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwojbcsp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyllssp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaulvck.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vatxrqfm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvqgbog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nevivogg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmdozzn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pkumewig.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgftohzc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hseavixb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsrijpr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjnkndz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2geyxssmk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbxrfxe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfgpkq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsuiili.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkcgocf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzuurmh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fucucvkf.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrkbmni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jghllfof.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orapkdpc.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iurtvcwl.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eseonhsd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtxbepp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzimqqc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2apwmfmfn.html


<!-- 参考信息 -->