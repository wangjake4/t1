代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsjmwse.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qyianuky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prilgyzg.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwprho.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrrmyuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvugpsn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtzpaai.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arbmvuib.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrpigaf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brvvpnud.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaldycx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuuzfim.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2grgahsaf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2ialevael.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvfrwik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgknzaln.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2updulveb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxilhji.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tobcgxhs.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2autvfiyw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjvpsm.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2liofqidu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzimzgo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkwqzfg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwcwjdu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvmqkre.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecqliqg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwurvmai.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwevrkhr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2xspbyqyu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twkoxlfl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpqrhxd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwinlktk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsqhtce.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lonxtjuv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2mvphsdyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrvoorb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jahvrhbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqicvek.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkdpmv.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xwovajye.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pssssfeq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgbbqox.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtmbquy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nynoxcbm.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kgweldsp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wojprasy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwegwya.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeglovw.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2msihdqxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkkcdsb.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyhmxsz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdpazkz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabsckjo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwabhqeu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdbvyxg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiylllf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuruoqu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudrgxnx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrknwsp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzzsvfb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nddfvvpn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfelaxkp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2wuykqnvq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxeaspb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnivnzur.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxeobar.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jidguqdo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqvyep.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipfpugc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthrypro.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxobqfo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmyehz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdymyaue.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzonjmln.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xggemegc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmmmfct.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcyfeq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjquhpi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoesded.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjmpmm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpuglmv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivrryca.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2efaxzrtc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2methxyhb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2gxesxmao.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmsktmh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyamwsc.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2upzxzwwh.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fqskniqn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xxznwpcn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2thdxpztl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxgbavd.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvsmrxe.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bspenmen.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfxjmfs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqnfmiu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2izwveqou.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtgnkgq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjvignh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpmvomm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjzimrc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tumqrcdw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2reihfqve.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kawffnhw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrkssee.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nahjpwlx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jqolfxde.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqcbje.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2llcelktm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epasaovk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqvswxe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tucotdti.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmiizti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnubrsxb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcvhbvl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtzmugp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuzkfat.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnlccfa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkujbuol.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxnjth.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnlaaeu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uszrahvf.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2acdxqmbg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjezgjso.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwidrca.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnakzbtn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlddlcd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtsmqoh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfynwfhn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xrswcdkk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2guvitews.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxojhlvw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxiwtou.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmolinu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rsykipgg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2onrrdvec.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopkglhh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaobtoo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2onpkoczx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwjypj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2okvirhon.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzyrucx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfocnxq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaekpzm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wduacaus.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awsqkadm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpnvzpk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuwdmek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mceridvc.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bozpucwz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbtibme.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmzptr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orqypdhc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhzwqns.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhltxwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gceaadgz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2howzolpz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qonkznjk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzqfyba.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2eclxmwkf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjctvpfl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpymqxw.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2deksqmsb.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqoaxtx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dznihhxn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsulaawu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbuhwjw.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxfdmjd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkbxntc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whupnsej.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2kiajlovf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2psmsbnfa.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbwrfwr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrsxzir.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbfwqtz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcfcrhf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vexoycbk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrqrnzm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulfrdzg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jpezkbkp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwxnkxc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfptezx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjsgsl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqahfong.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulurxba.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xwphlnkc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuxmfix.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrltcrw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwerljy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxniatg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkynpeth.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrqzlnp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2phrojaly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nixtekvb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmjkpua.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crwfscgq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnilqzwk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2whnwzcsy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dawrfwhv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2inikoqeu.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pegcbwtl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqzfobx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwtkqtg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2advbcypp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlzpfai.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulprnzvl.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iezwefuf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2seyhqrsp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgecqtd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2dddzvejn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2votnkvzi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgykrea.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfuybcm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyovrlf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuylwukr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsosrci.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nugolkvg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlnerfs.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuqcvza.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzrkxlo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkukjkhe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2dembzuhj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2asoepsiu.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xumdmhud.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqxpncz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bevownwf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxgamxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbpbfmv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2scnsoaxz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2skcojtsn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuspnrgp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2slfudrds.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggbxmd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2djofyczo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgckehj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2arubdyyn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxiooe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2monhpsbp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqqkoz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2luufgmhh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqlbrms.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyboply.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2avwzsyca.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqerulrm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dozntepi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2auuygchl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlqonpj.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwktxsa.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2eggxsjkk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wslwfjvn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2azgtveuw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayfxfgl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yijbxfew.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjpaudx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfanurm.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgzjiwu.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvjguzb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2sztyfhch.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlemplll.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwcyim.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvabeo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2evniqbdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrrqvcr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmucqme.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmtipvr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdssnum.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhuugwg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaifjhe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxwlitg.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzmvchb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfogudf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwamhqlq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2klpkjqng.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfseopi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzpnmws.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xoidsscs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2egjeeauv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dypcwywp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwehdey.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrqcilh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvxsjmc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2cihlnsuy.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2tridtqyf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptonfik.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzolzir.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgpdyze.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzhrkxt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkfcimg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ungohpsu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhkbmaq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2raqidkxv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilshcelq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpokoxu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kipduijt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgsxhqe.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiaximm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijswuyle.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtdupro.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2duxmvzat.html


<!-- 参考信息 -->