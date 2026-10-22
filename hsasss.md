代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2phtettot.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2colivrrb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhervhs.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaamizw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkojyht.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2acgvgzrv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoqywcs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adeedwio.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvacfban.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scqfhwqf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmchof.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2klyvpppp.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jnraedoe.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2mchntaqe.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcgrbfr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2acnszare.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prwolipu.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2nzliwois.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2khbhqykd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyhwzdd.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvktnsc.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcunyda.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqptaoq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrcilvg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmucyahs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwucpge.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmifchc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsjjbit.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfoinsh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsobfaq.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkqoqzu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2iumfehfb.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsiyawn.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmdjvsi.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfjnxta.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqoubmj.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgtxbaq.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2asdgtgaj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjgqaoj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2srivlrgv.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2cozhuchb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdketpa.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprrsnzf.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyaheps.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqobmwzx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyizrrg.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2geimkxqq.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2evzczpbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjnuhw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ckulhphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iljxkipd.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnhgnfk.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2akevpiye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcazyhy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzjnkb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unnzhsom.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqwcgxy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2erofketk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvpvcyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxoigd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2muxxheqi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqfsqwf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyocyib.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epbgjhok.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdftgsq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzsxxdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqciwpfa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zctsokmx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twcgqzsk.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gklntlcy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nearmljo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmhflu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dggjsoot.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspzuiju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvgktyy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzdyhir.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbiaica.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2djgnbhph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpwkutg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqrkimw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrjsndj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iklmyyer.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcrwdnd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ytesilyj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2frcbcrlr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzofzwg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoavitxy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsrmmde.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgycjzaz.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrrwcax.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcyvwbd.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbplyfkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2vexncnnu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2usfwqzpu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcclyvn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2toixtebq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2adxayqst.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfrieyc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2szinfllj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ropwtusr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejtaixj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqarjnqk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2srboeuew.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvhgxwa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrctexk.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmcmvgr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybakhebp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2birrtwbq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughjpinm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwhrdjl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yupesjkb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2pujxiyua.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbdspee.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuioxce.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyskugh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kidtstoz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lklzpmbb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeewdkx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2expweota.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcxtwrs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkvggva.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaqojaz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlamtqzt.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pykqjfzi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfiebww.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfdnhsi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2tginozua.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfojwmw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxugphjs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2omlpcfsv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khfaljkm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpqcpt.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2earrvptc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqefuid.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfppnbi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yovecart.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jksdztks.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xhshcpvz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2phgozanc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kfphhucg.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kevkfvwk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtczobyq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrouiel.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjmwlcc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynscouct.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2difvtxuh.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dflqynax.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bphbyexa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2utsmqdxg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhroupgf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2suvoedgf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2byvxxzzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rluyvxwo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaeoqes.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmkazlm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcicnyj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmygbfo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hxotaqgw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkbwzv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvfecqi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwiheln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhpnglz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrmxzuw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegptasz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfgujlq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hreipagi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhalfgd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyguua.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvoekjc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqrelfx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnyeefg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2akwkjmgk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohehzvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aetrxlsj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgucgvd.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yeotzftr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiaboyl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkjvneu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2mprsfngw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2varpfxly.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwdxxzf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibacermw.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wynmslwg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpibsqy.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nczjrnai.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2asaapsyc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pkupoyib.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2khrbvdrw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbhntd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuwxlsj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xiohuemd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkilfvh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2arbfefzr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsykcym.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsgygwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhrlcla.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfxejy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyzjvxc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpfarwf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxbvien.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2skaurmzi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iugshnsq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2purobqmj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xuusxxlb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2amjhipux.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xglaxwrw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrhlje.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aredgtcj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqmhzjb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcauxalx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyktupnk.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjynrluk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxhsdxn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyritaax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvytrly.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijeltvy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkydflgw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnnxudo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pncjdmme.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhaipxi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uulxuukd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvxlohn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiphfyp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlehmrl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2armjklng.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvcmupp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2finvrbcd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvpkjsg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaqstib.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mouakzym.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2umvkhujl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzswabg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvzzbum.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhtgjso.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwyeaxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpvuayr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmnkbdf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamvaqat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkcggif.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtgggrx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2deomgvlu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrhvctg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhhorzb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhocgqag.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onfzpzjk.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxygnju.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xitazhji.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2haflwsvg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zosgcdog.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2poojorzo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2crwsorni.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2fekmcvcx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpgjpep.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbwpucp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhmxod.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvjizgj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsduifc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxevnsot.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2qobcxtax.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkjysec.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzelxgv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlnxalj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsvmzkb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edxyzlff.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlcjluv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmvrpmn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2doiyiafy.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvqtivv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjodbjhl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atgglwdw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwiyshi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzpgkii.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tovttwrg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2crvzkkip.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvzutqe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlittba.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvrmvwo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhigofs.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2meaykjci.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqcxqch.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljaniz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klufdywg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuaejgh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvixbgb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lmboejoe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrxldmw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekmjysi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qyilnzdl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxsqtal.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2aitcwqpe.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uabbrasl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nodgzven.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvqseqd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzgzbfq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexbnoy.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2etaroepy.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dadgpcpu.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zspqnzlu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvwbcnx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iulzpnld.html


<!-- 参考信息 -->