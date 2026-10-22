代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2djtjsgwm.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xysdzwnn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2usnuvcfw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2easlmjzi.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyymiuu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoopfcj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2keyxjzcb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmykqez.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ydygdqhu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmohjvf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2capmtzwq.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qprxmery.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaicsadn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zouhwmei.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tziwhcmg.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvnkumo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzigntfq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uudjagnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbhzfgb.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgybrzx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgluvsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sapebola.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgimlkjd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjyvqze.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njobpucn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgcspyg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlmrgyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsmdcsd.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fksptqxg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2isssyldu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgfqkqb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtwyzue.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhnpkek.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2topebldp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgnayji.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptkfax.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdjfoal.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzphesox.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvdrsn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxuqevy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2repocmso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydktcufh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oucgfjyx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdolauu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvvvpbs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsupwmk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jptqgjxg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsgsadb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edkpyijk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cacgffib.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpzxuqb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2faxdiixv.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrfbczj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzhimpm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlailmnc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpbwjok.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhpwpym.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbtgfu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbvnnbz.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2arlhduet.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmlvlme.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2comuskfw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2puialalw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlylswn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2esoywcrr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbbpaux.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjfyfdk.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnidjdk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjyhlog.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsrbbus.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxappjo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailclcgz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2patnrjty.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dratzmey.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsklgiwj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbydmhjt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcotsmt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtzladh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qptbdryl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnmpafa.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxjvjop.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmdlfq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2efyzkcfr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqswboc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apsdhejl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjhpby.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcujqmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2aysjtcrf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxwptrf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wncmbbsu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awcgznet.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuyidpc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaajsrv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htssform.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xljwllcv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmrzhi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agumcame.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykyvdjp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axxlfpam.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2citahdoc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfqwkax.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2gsftyiyj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkegckk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yjspamph.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pzckpzst.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tescmkeq.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcybzul.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfvjvya.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbqjtqm.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfcimd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ssppbrmz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpppkefs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqylthqx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2afgknvju.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlhmdsd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ridnnsww.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeszpnez.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzemkvxg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhzhdy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fglechgc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuouang.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2guipkzky.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtyjgla.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2axxobnjb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2epsvlhkt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuqtlbs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmceukb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rikkgrxf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pulfrxsj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvrsprm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2bukdsicp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeebaxq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyjajqy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2arhzdejq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpfwmoi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2plnitish.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrkakwy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfyjusk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvqvrtq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdqbwla.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvkguhi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdxmaf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzdyhtk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxrbrvg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2koqblkcz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmwnhm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmomgiq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwfgvyz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpntepj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyplepa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hazcdtxy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxypwvu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzyksy.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuporfz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnuhrlk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlgbemg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjrcobn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcdplmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjzglu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yckchgmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyilztf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcfwhb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlffbud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrktzmma.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrnmypg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ichusswi.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blffiqmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cymjuakf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2czyscjkx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2drpjuvxy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqmprlp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuuxtcb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnzzosx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2twnufgke.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhbxxlu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uoigivmu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qhauiqwx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvhkdan.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnlyyry.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxyekqf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtrftn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2atotivuz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2txnuayxl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzavrqws.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ualibvxs.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2awnkceky.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2okncjzlk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkmhcvo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwjlyu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwmhldp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgfrukf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvpodiq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uixrskcb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzksqzvi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbytsji.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxnecxk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvougbn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnzerxt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsgaypn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkorxwh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxixgopx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyvwkfi.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rprqstps.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbvbrbw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsozzrsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdrndpi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbqrlfg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdnljzi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zumsyhcm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqtjgth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdixosuk.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyyayzv.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfpaum.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfxdwfb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwkjaxw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfuhbix.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxfbmx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlxfxux.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrlbkt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehefnjrb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dnstcwzb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfehbpi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2klkjmqpb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uealjhhd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyctaeu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2clkoixfx.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgodwumn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2koldwalh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2elozjume.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hduikpzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatmcqpe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejalimfi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hznboakx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqfrunx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvjbgkz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnahgny.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isnwemcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaozowwa.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2myzxrnhr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iesaplnc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoblykz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfextwf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkyxqjx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtpyrdk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrugbeg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bykgxmlp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbigewfd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnhsjzj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hksausef.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrpyskp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsacbpbe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijwxhvy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiwqedq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgysqmoh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywhmhhj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wckjcibc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnsklxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeumadb.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfijldjl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqqeocx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbqugpl.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oufcezxp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbarnyuk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqfyvhr.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgjjpok.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdhkdov.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxahjwq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2besrkxin.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpfyfhd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxgdmj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeicbbn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mevhajak.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjftefax.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwhpgh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2blxlfnja.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrejrzp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoazroi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubebvygj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tldimabx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2byulnvqo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgvkgon.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2erbccypk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwxiukt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbevayiy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmjpdyj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pozkiqjt.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljumlsju.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2victnbxm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxtrnwz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqxelsy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yylaobln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyteupz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcptsba.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aheuxmjm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiaazrq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2unytpvpu.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlllbgf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkqvikr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2efhxdfkh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhlrkvm.html


<!-- 参考信息 -->