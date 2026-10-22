代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscwnxx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2thkhqbjk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2godslqfu.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxwilzo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwlaxpm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qicdocsy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2itkoubei.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmrjuzq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdbyyb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdshbpux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbrtjok.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2cftponer.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiynfdd.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxtcqnm.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvziozni.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzasiug.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njymxdsk.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2utwupziv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2llgzimxl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudgfzbd.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcugslj.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2etzvdewb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2yatqkwrv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2anwepyhb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxfndoz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nacyysvg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgziktt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvxxyey.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdsepqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzcuofu.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvcfdvm.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2oggypvge.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2womfxkal.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsonscn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2efndopai.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuqvhwr.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmfmtm.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsskmbl.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjkjhrq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bopbsmtw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyocihl.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzfwrpn.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2meiwfwxl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyemekdj.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfexufcz.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnfvrto.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdizowu.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkszdov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzlhxjj.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2itrdkbjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeszprt.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuwjnyc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfudmid.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwkwbfo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pznysujd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqfcfju.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeohaet.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckihweio.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2seretoyy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guhlrkul.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqmmodb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdsulzk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytmilgn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izfuscwh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdjnxjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mplqdsmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctildpwp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sggubmbn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmuwueu.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bymsfgyi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhklpkmv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfotgxcm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutkgzcx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxmopjz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmumgggx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtuazx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olsjyjbt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwycapmn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoxchmy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vstdozpj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeijyqm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vywmnmaq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkypxer.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2mviejzls.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkybzsmr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwlydze.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apshhems.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrhsqnb.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lpysrzpb.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbcfyos.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbvcxsw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ownosodb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2miajybro.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkogjkpl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqvuiij.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pvboacgx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlmywwu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2uzotoslq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjhvnfc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjoqudd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlhrmoo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbwjdmn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeryujm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrxfuni.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrlzknr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2efnvqjxz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnhrlbc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2acnejcce.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2moodpbky.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvkolxo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2essxsxkp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gkboeuyf.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndnmtnv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdlfghz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkaytcx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpgurft.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kslxmenu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcldhipv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkorkkn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2skweljmw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywmalqh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqajvuqq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctheuwzq.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjrqldt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xetqcozo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olxqspvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2upnjbxzn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdyfllt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeaqkin.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhcmaoo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhzjdcb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjnsmyd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzcqgsz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2blsgdehl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvwxqyq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qizuhyjr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrcgrpg.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjaespm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqqjlxz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfozhjh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2upvwlcpp.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2grgxkxxu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2igbyclsj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2cphnxlro.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldijjgaz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqqvtzc.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2neqrtics.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2egepnins.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xehfimfj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnirsbz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2cfewxmna.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvqppmg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2revtocww.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2idfdavqq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2clnuooto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2diqdknul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeradii.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qmypaiur.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sszdfhgi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2dhebjzlu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgynrnj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffymzeds.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaqifyi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrdlqy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pptdlhvn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjyxlnc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zteripoj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2senvjykh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwmgil.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vwljlkug.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkcjeaj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpcxxnq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uabhpzco.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nscrcstl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hinlxups.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpyxdcp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2vfutilrt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqefhkx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvksqwo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjivepne.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ottzbfxs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdeypom.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wefuxxpg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwcndnb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2adojxmva.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtgksmy.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpabihuc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjfwzzp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhxppz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfigfcr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nfweculj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgesxhx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uetcloux.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqmqglv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onewaxxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsavhtc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpqctwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obzmobjl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaaevxq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2entqnrrn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2niwiivpa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpxwkxv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2eubperqd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lynkrheg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylruqqgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2myelodfe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hswtmeao.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2svewkuzl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbldhlb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpgboan.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmgzayl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxipfprq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfsigds.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kurozpcr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcdazet.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemanwhn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxwssf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpfoddc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpivnlt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpfijbp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2suydfiru.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2koffrudd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjwspnq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbywoi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kupylfrr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdctkbe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2csozobfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrdyxdn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoxahjx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbzoxaf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aziqamjt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvgvrve.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdnkglv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcoalgi.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzazivr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pszoazpg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaknutt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkmeusl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yclhxtoo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjpnedn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfphief.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2orunixyk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfuzuui.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtcrsyy.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aembwsuh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2degwkycb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mslyfxkj.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cdomypcu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxusrbad.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbplhtl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2owxwtqye.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcalpxg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwodmvtk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sskegiug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjevaszw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfbyhqr.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlvokwp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkailhgt.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jszbyvvo.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lphiypsi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotbxnge.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2llegswcc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgfuwed.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2brmdczkz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaxbplc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxiekyb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hozgxgru.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyxuipg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pejxzgqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyprdbd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksffkhvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zksyeggn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouudawmt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahphtjey.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmjodfq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdqekjn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpxizhf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iikvngab.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbqxwc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynnqxy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgbbhyw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xklsgyfz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2idosgtxn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotpbrnz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lkudofem.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyokgti.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgixnbn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcloilg.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjfowqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxvmwpb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxwwnbw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iazyxtmk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwjqkai.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjaanja.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswmqaep.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqyqdpz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pazgvwbq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xsclnjsj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrxcjx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbszitjn.html


<!-- 参考信息 -->