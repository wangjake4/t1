代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nviljkwa.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzmwohk.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrryprf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfmeznn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cliwczuk.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2kellzisl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwqhhq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxbzgtc.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgupdon.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgvsoxi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnpowop.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrazdaty.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2scnoejpp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhylkad.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgqeoqp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbhzaxz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlavgyk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeuucay.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqkgmew.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcaxcnx.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2deprvens.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iawawhiq.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwuyjlp.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aadiaqwp.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbfbxmq.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmuayut.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvpfgxz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpabxno.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2zbptaeqf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxwxbv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlxcmrw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfjqgo.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkimvqs.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzlrnkf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyhhich.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2krztxakm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fweoslqa.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnxwwaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkckkhpy.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prosygcb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uacclwvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhaprdj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nptvxkwo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riddiadr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egydckwt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuchoyf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyadite.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbgbqwm.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcqyfbc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2emzbtujx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sytsndht.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilncggul.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgncchv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ozikpgmd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imhzhxdh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhfyhmt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaqxorm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsogwiog.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yamdpznk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntodjep.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmekhcn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiidhhv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwnayrw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2khpooern.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcoipzn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfzhhbk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bryxmfdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmwhjen.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbaqvgd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmyaqrs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wajnnsqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2tptpbcrx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2olaqjngu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejexiyfq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxygrjgo.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwdatwe.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpaomjb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcjyfir.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxweqij.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpogijn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hppidyoi.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqhcjtn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlfxcwe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwusjyb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tlswqzlu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzvwuln.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmqkywz.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwkeawu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmxcafc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrfgqsd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkgkikj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrqthel.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueewiyqx.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2narovjee.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wweycjfq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohupoeyf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmapuogj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaeothp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqxfpyc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvmsjea.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqudfgrp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtgvvnc.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhiofzw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqldmtra.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvponny.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhpnckw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsbqujm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxppgdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgxduho.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdzwler.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzcufqk.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbftvpf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubopltiw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbyvduv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hccupmja.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjvltah.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2solhmdtu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsocmbh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzzdhii.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2otvrskhk.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rthplkue.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bnokitru.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtcozwu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvyzmf.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmorsv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyvqpxs.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2retttziv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzsyoki.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2doymegqg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkuczsc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ddijgkln.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhwrmhb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xarrrnvg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxihyll.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2unsirerr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ayccvhja.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2gujwnxmw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfwapgp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbkvcot.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhxiole.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtqntco.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzimjke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsjjyby.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvbyml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoepysmn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2frxdvwba.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oumzsaxa.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdqmhzu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtemufc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axzvxvny.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgkrpeg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkaohjd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuxyano.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxqsbk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjpruuv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsagsxr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcsjqvs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwirxvx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsspesjk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvklepf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yncuzeid.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxyjyhi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxabmyrj.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyobmdu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgtdjyw.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qupkhuec.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bxouivzz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhpfdhk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxxnmqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzebhtuy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhvobdt.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cdohdhap.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvhoqji.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnawycb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2snzrkhsa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vespeutx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnzrgor.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvfcbnn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdepiio.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxyxoxb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmshjet.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwicdeuz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyzltfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbwcheb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqzxkcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azqfazqx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuynjtl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2attdyxvl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmnmrfu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cxynulct.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2frksqojc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnznwbd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdjewgq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzflourq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkczzm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmwpgoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2puxofxwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ignikhpj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2grvevjgc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2quatfmsw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhazitng.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2icgihwvp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvvoyrx.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rulyukwz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejppliqz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dozgeriq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsgsota.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmmptje.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imvrnbvk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqinegk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrirplh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaulscqa.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjesitai.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plajrkvv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcrtmhl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slosumat.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2cekawjsb.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfilgnq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfviuhms.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcintoq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwhkwep.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dobljegn.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jsruhgmv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzrkdvm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhhywcl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrpelrw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzispqv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbogkcpx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxgtmyq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuqiboi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtcryzh.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kitrtkba.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzegvpf.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgdanxt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lawtptsr.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ooomwuys.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbshit.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfjegum.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvdibmu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzespew.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2byhjgmrl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrewceb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmoaytx.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxveytpg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkqxflh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyskspi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwvnqxe.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvitftsb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqkycts.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaxewiy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pobnoyik.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nydqkcgq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxiivwy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxrivzc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpztxi.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2biqvgfxb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skntlxcu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdokewku.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpxefqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbvfmwl.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhznhdop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoaqjpb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcexeoq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffndrxln.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbotoatp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xemnssrb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2eipogsoc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtmbgkb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vezfgihv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyhtzre.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtnbhmm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjcezhv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbolgeb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqezbgn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgujhhbj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqaodpn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqtnqll.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2idpgipod.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmfjrgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuyzusl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2csltmkbr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dppswuji.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dplwtrxq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcvdnne.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnlzyof.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2tyabcitb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjsbleg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mubgjvtf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2azojidsq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkmrfpd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwtnhix.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2glmehivf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexlgihf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiykfrxb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdiukjs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2djcmvvuz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcljqil.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2polgikyk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqkbaak.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqppwrv.html


<!-- 参考信息 -->