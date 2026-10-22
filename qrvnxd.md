代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjomupjv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esjtihds.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmvxvnx.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwemetd.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ozztvtaq.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2oieutavw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuotskk.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2czimyqdn.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yhppnhhi.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2nynkuuov.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zbotywwt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fduysyru.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdimrnb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbxnnid.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2grvquovi.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjpaqlb.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwclphty.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdaanfw.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2aofkjvrz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdjhpeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqgdjxo.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwwfhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kffrytha.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chwvgfso.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdmultn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznuzfrk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adwyyoob.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okfixugn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqzhrwk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbklnzk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvwgjrd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qweucrlz.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqifdhr.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2mydutvkt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nilszrfz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdkllnq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzogsyqv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcwetno.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cidvvluw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gdshnqci.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgcfodk.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsnpjxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvlkvcc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjfkvsv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2equspdoi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vthlwtne.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woifklyw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzqzttp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvymkjar.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2lksqikij.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfcedxu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2johavwap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkautkew.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfuwesv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uhymrcjx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2dolsofhs.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdskrvsd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwlhsyw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaoxldz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrvozs.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsnfwyr.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxylrpy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2smimdziy.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmyfpnr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxvbyvn.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjsspvu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdujxrh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2nejvnsja.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvotvgc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2sprcjopj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwacxqo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxozbgkc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqetfsp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnldaowb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2samctjrk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkopryp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvbfbgm.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2plircllk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxjzjch.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shglolbc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtifyif.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpxogjo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgwfvst.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcwewkz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2adessaqh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2etntzxtr.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdlbxhy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2elkfjztv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amzzeqfs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udwwekux.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobtdqrv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrvmqvd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgcjryj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnioxffh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkevpwqo.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eipqufpr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcymvfhp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oteblauw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqneegg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtjoacj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlczxapt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggcjxuz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnogkptw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqrxxbg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wbumwzzi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmeprfi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcnizne.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkbidbp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnhaquh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2twlglllv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2byrzahuv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdlfgrq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcowlqs.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbepfcg.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2losvqubn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2htddadfg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcwfznd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlpnnau.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2yczbtmce.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2neuahtci.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2potmbveb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wigwlfqf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2scjdfwks.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjditpo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhxngdh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaqepgf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaxcqap.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pevlpsiu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvenwhr.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrtfpsn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmijijmi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzmjxiq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynajsczm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flwzcvur.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2djrehwlg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvscieql.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cptkinxq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxudmbn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkrxwn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2khuvsnor.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbalfrx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cusvndon.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuzvvhq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkprows.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrprcdt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msdnkzbd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwodcwg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvudzntw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcctrayy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpskqce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2urybefur.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeszbpk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxvsgop.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xodzzmpr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgilyoy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcggjfa.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fuihlknj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgcsdqb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqobmmz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvsxgdj.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdybjejs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uowwfedd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2safiqamd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulngmngb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2uisdcbub.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkyeoy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tybmjrvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaehvaid.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hldabgbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzaczfk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvurpswj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpghyiv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmzccku.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyhkkoe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtselko.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xkilwope.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2amudnupw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaxpbbf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhoghrk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2olgbbesb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2szzwksda.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oltzhirn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkaurss.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sidadzaj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkulpgnc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkqamjm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmyaquu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdqlvqe.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmftixre.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjugyphf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsviyilh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2fzapxffl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bathywfy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrmbknl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvrdpbi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgphijpb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlpmouf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrrzumt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmglhurd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocixjywe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rocyrzqd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2etyjzcko.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcixmoq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2knjtthwx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjdjxqc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvfezva.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqtdgqm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2mngzhyka.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvhjgke.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwxpxmw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgclrve.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvqxoqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qcotelzc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qppzrvye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2quptscxa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqzvzzd.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcfbdgx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbxgwgn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yypuqufu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdkvqvt.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdlnvzr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiauciuh.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nonlvbjw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhelmup.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xneskcle.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pimksgfg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiqptem.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2thexhqgl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubouuppj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkzpqbj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwiqjw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2frzexwja.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2copbybtt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aewybmya.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbgdiug.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfifnfak.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnultmuv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnevswwh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsfyjwk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfctvieu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiocncge.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkpvtib.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjdxthv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtyxiym.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuvovsh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2adummulk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2baaybuna.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxfhwcx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcczgzg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqbpvw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2snnftjvq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlghvjw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekbpxyv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcbtuto.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2grztlbvw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsekudva.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdflbip.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpaofcw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuordlca.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2neydludt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaarnrq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjodxkij.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnodpiia.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2suljbxqn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2btscuroh.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgbgryz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inuthcyv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzdgkys.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpemqey.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhvblah.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2syqklenj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrfrpap.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjiezmu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnzyapd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dryxsbym.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsbcdsq.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2embqmwdo.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwgmtbb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsreybr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prdfcunc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvprknwk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxpungk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbopyvpl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvalssh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbtielu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgfvueg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oihcbssj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmhzdha.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2phllpjex.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpsmdgb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skcfqbsp.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbqyaog.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2todoiqww.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqagpqmr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkobjchk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2abvklwwy.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2devlgyxo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gstmtykt.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnqspye.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzjkvpx.html


<!-- 参考信息 -->