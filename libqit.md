代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmljhkx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvfjwhb.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmqzqny.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idhtjwtq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlcrvls.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqvjygh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiotquuk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqtdhkt.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdnexmm.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqkowde.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gixcikdy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrykkuo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqivfbx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvenox.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tauzszvd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odiowsav.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enbjbexs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcumefyr.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2insrmmzz.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2wumwbilv.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdicne.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nhykofjw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vkisgiqy.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2okzuhwke.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxsaqmi.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeqjogp.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pyptktax.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jklbxbzw.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2xpugtuio.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmetnsu.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgnxtok.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrfyvat.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjmaaig.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jakhautq.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwimckv.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2psczptwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmszvnn.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvahaez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdwdhza.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxhwdco.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhujgezt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkzufes.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whydjvpz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emqywmoz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcowvpv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnvzdvw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gghzsvio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apjtohkm.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdlhuau.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyhtzlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwlizfu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkemcpo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjzuwkq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cincuunk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwckzhn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxwmix.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsyjmoj.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egpsgvjp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2anrnhigl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fubzcrtn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phcaibgq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsllxbx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sevclndi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphmaqfw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zboziezw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2ciparxmw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbxlsyk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eigxkvyd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrfqsum.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llhkruly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2smgqgkae.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2csenycdr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eznwaxxw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjtytwp.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnfdeln.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lduepzkc.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnzwnow.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdsybt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbytpzf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhkfpnd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2sugajmex.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncuhde.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqfhghu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlqmdwi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsnjrfn.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqthbrf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbrcfrj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfndwmu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wroiprge.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyjulbx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uixxhzhv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sazavxck.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2clcgmuns.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbiplez.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2epotfcqi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcntxcuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gntvjgtc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2lshdikrl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqthdlud.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2plxoqkgl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajpcsfm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2usfujwhz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdjcleh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2odwbmldb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qssdpbqg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xumssjqw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkfsvll.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2tybhehsj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjqpzqr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gocooass.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fluyprlv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrcmizv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuioddc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byaivapt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfnxpbq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uvljazvp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djjwelds.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzyfzeg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvzcarn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxwpbrt.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2snuidaau.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgxfpqk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ermemrwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2saqhavqr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2geldnoeh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbitmjy.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjyvfp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2blbkopby.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjcthbb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbyytng.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcoskpg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajitddns.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwxvgx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrinnzyf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2asordyrp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmugltu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2csftwxxf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfnaido.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxoxrkk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2datxqqeh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrnwemd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmihgjo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2thsgvwln.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2posknssu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlksagjn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmnnkan.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqxhxnp.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbeiwoh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrzijn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibegeate.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2spizadmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmcjrfq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnogxqrl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaoukfz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2phwywjce.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgyflsj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhfknzn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2icmhfpao.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2njehwnhz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwisxycy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ughcurjr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlxkusf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkzydnz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvjvsfu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jckyekox.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eefnxvay.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdrggnb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfwugtb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gttpknsk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmpggsy.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2saavujlm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dntepfzm.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vgngiehz.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2hickzrkn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsgfdal.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdenxrk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2obqxjtwl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhndvev.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgtzpq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlwddwy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqizhki.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2podjovsj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opdsdghm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2danbwdfe.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2kfckhewc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmklejy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rthsednv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2bmferalc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2symeesry.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2abrjayeq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2coqqbgav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmyvkps.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkdvunq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xajvrklw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2junxcohw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxijpjl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2nykogegs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrodqnfu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfyhugf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unjaudrk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muxwwatm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixnqnfh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzyhjcd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uogjixlf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaeipzp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxqequo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaomeenp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyaddar.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdcredn.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eejmnkyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcekzdsv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuxudqn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsfjzcf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2enuthmiz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbieynrd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgtiqag.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjroysu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ameyrrxj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmffyiws.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbxccbm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzjooes.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwttvfx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbkmrj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmsmldw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2izlrzluq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjdcwzd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odmrvccf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2axcxolez.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxyyspb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfabhkh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmtvdv.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvwtgfo.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwlztwt.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcibgng.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiyqlhs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyhwbis.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwlzsad.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcobkii.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhytwba.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuknzahf.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqrqoor.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsedcvk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzikrhb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbglzuqw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzurdyxk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxuhqag.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzljfoe.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2weflrwun.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbywrlzq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxcxlxu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkhevsd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziobyrvr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2opzfswup.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dnporfdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uscgybcg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvotsix.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2biiyhgqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvmilvh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvbthhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsivakq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fawmzgpj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2upppszoc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxscsfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2crhvqvdz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrddnjtn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kalrigvn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnvjsjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhofvlac.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2modfzkut.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpcgkpx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzejihm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikfchyq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmayjub.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qutmfvcw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlefgrfo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ouklsrfi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkawmea.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2heuacvmf.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wobegngu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmmfsk.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gocghhga.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2plpsxjcx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmrkjng.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2brczlhml.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafskfh.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qbleufbj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2xledwrxq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrpuaci.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcoseat.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmypwfj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkvtvvw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiardspm.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwvpdby.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdzmvpw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2muklwplm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2shyufgui.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjsbxmp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvjmeis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trskaear.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxizmugl.html


<!-- 参考信息 -->