代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmafwuq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yidzvjvl.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuveqco.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2xlicarag.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpsvewn.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkixkex.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2crndcqsk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbwtalq.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bclnfody.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljgaqa.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmyhuno.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2thgroplq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2oamaglvr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgwbnlt.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jszvfqsp.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dymndjgt.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2azelhtby.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwryncg.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmvcma.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfjvzvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhujmaz.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2myartvlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsabuli.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxdkcfp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ormbnwsw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xskdzhmh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yosypeiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntygvsok.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjzhasp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxldpjd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwmbbds.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrudbydw.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqemxl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyrjwxf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhlgoeu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpdrhln.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsjokaf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpuwxwz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvgoqp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppenegxn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlxwcnu.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaopdmm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sszxvzch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhxrjz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrmcmzt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhapqwab.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxciyer.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2cobsssor.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvvitk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqrxvmi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfobcqs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzumogrp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjittkm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2samjpfod.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsboaht.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2deqftfqg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvfnssz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcqhiep.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvhqgml.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdhjhle.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyctuez.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yonoemje.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeorpps.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2bngbotun.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2intbqgnb.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxvqkg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2niczmcrk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmucuq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yswtxbmn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2eghxecfj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnmxwla.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwtzzqt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrlztzv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdmesmj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcnsjhj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cutcuawq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzumfls.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2wwerayya.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkhabgi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yipbrzhu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuibebqt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdybbgg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2phigqowg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjetaqw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2aclyehdv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uzohyial.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2thmvexjt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2oomgpgeq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shuchwpz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kadnziqn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcfefxq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bbalvwfe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfpqoe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkwrzci.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvssakxi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2glhwdmuj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnmendm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjizorko.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2llflcxun.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jbynlvca.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyggvaek.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfsxtcl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgadkgq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoyypaq.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uxazvchz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nyddkqcr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2imacswkq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yahbrjut.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2waktmzst.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2llkkskag.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xyehgqur.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiwqpmf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlwfebo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2abyaqrpv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpyfcuu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghmtmfz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlginuoi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvcxldf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2naxgiyeb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjidfzs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2grycqlql.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2awrdbhmg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfzvmss.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2aolttsuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2opbvcczb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2phqxcmec.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2okntddxy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2xppvycsn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2czwtgflf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdgdews.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hikwxgma.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzrlest.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnnyknk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxxncko.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2fojmzfus.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeqigrz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmpvhnw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmograam.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgdaxxn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnogreeu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frzxnkue.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2htxeltju.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2drawusvc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbcsonf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djmzwtnr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stqrhvwz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeajbah.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjpjtea.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqyuxgq.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2muatleuk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmuwoae.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmwgrja.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hadynqkf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tamunjcf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtquobm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qirisahb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2pagtliju.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnvdzux.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qujlbfsx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpuxeg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrezulx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeayxny.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajsxlh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vafkinlu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhacsepl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2juiiioix.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qypnscuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrtqjma.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiysmgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oicqkjdi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2htxsluoe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnxndpr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pfprtmxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtszohf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnturco.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lyooftle.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxrrlyn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mkotrthp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2blberiyk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2naxwhncy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaptkub.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkhdbqi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csumlefq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbqsnqw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vorzvnts.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrahin.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oascrpdg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hccjcjzc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhczezgj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhjbxfd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbfzow.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rppwnojs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzobfqt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocdxrc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iepvluvg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfzkgis.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfolpyq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jigzradx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzrvyrq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2spmmshrb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2svqfowwq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2twkesfvg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvojgz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdfokki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2szucbhxv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcozxkh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsweaol.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnklhnh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnoddh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2txygcnwq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeemlgo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwlxwon.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jdthndxv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqmbumt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoiltit.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsvpdsp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtbsbqh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwcmmf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yliityre.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkgvnxb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2meuiqtyb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyvbrww.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2blowanqx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtcqvrm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyedvzp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpjzqwm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcivvpzv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdunhago.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmswusj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnzoerb.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqcqsw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mntqqmwx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfdypeo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2umjjhjsc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obxanqmw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuwhqyn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2myvzctsb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhfxlpv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbntpii.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjijbfw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsywpzpc.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmpgrw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrabsyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhecyrtc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxovoxe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxwwrw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxynckn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgfhfax.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwxaep.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfdimon.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgapby.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlwbcwf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocqehxy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sykrssic.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuoagjo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzopeos.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tygdfpcs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mltowvsp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgswabl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbgetoy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhpvrac.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nggsyquz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xepvbkdk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaknzkj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2roohdoid.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rahcseww.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iksjpdpb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2htyphudi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqfvnu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyfzjoz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2slluepxw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktcqll.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyhiokx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2etxoxlxv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xopuxdxy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzykrrks.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuhkjas.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdgsfuh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeusrab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2siyjjlox.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvsjizg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qchiedrp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnereob.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuljhjn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtmsxwm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgxznlq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiktoqf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2edqnltkl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxsqefv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tawogdqx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mibehrpl.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iddwxzsx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxegrsck.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixlnmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shnfidsk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfupkqqd.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaqcude.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yghxhbhb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdvzfqe.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajakflne.html


<!-- 参考信息 -->