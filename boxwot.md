代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeisipf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtzqnv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaxyjfv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkcofdo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irqimttz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufczljmb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvsbefi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjcjucy.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2garvlauc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2aagxcual.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvuwoyo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yclkqlgh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhdsxzf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgomus.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvwbrnh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvvdqoi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvagguh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdcygmq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyihlhqc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlavfypp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvymxjmc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnphquoz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhnwcxl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2uraujtgf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnxolsp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2npqphtsm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyfinwh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzdbrpb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xweetfdo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lisvqhne.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ooelyjnq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnhlwzl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxfqoor.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arcyhkdf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otorablg.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvqcyjk.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2htegugpy.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rvikjobj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhpmeof.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdmvdrm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvlriwf.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxksoinf.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqcnjvv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyifnsg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzrsytd.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2neuonkne.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwxyrix.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yngixszw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlvnzxu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxbbyzs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobhwlws.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2htffafew.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2usriuhtu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jfksyfrn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsngzpgs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eamidbgy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksmnohf.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2frmnsotj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrkplol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2weyuolhe.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsivnyxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wxprhvta.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwlyigm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2spohygzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkywyudv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnvdtop.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbegktl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmvtvcr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpnpfgm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsvewku.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvgbtaw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dzygciof.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxfakmw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcdyqpi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ugevxkrt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwcegbx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwwjdvz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqktfpz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqixjh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mulkyysp.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bqicnryl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2syxczptx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcpengb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrzcnzv.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qbewxabf.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbxfzch.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrppxyy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2eeruarjk.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cfomvxxf.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dvndzkte.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmbigua.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2klyabpdb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtgfpoh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhfmuy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfixghvg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgfvvra.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2scvwrnsc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwopcwrw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwpzpav.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxggcvn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzfzlkg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2orpcidje.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyqelob.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2twrppver.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlywujc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ifddfwhr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mygsgyoj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxeffge.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdhamzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqulwvr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jscmhhsg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeikncr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwgtdy.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmscccb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqatdyp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkgqhhk.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjgyzwd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuhelqf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpyaonm.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzqtars.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reiarzwb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtacvwqh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2peoxejqi.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghozfehy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeglomj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgknlm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2sigcreuv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2explqfqf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fedlgrab.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pocnqoyg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmdbnuy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2akljdnht.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjenuhv.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdxvpsa.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyrjznj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzbehaq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcuewiu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tlskvxlo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwsuekm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmbzjyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrwhsbt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgarfyoy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jniwlxlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hedsznrm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjhqbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzopdegk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlksgxa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xnylotsx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlbukwk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rihjxqco.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnodso.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnhomag.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpardmty.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuqnfxe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qabnabeb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtmvev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rwovghot.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcskaeq.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmiorcp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zytagnjp.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqlfewo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffxgwcj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsybmevd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlgohp.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2frzzooap.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdserjz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrgynbs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxwgyv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2orzkaxvm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhezbfco.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfovzbg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2twusaeqf.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpkeqbx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2msoykyuy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzwuxay.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsdmvmt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssifxsbh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nebdneeq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqokppe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuvrirj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlqthfk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzjidyx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpptcza.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nplkihds.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2afcbxrzl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclffctu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nblqqnlr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuhzhyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhfmqyp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqljimd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2puxqvptd.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yuugiiia.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwtrknc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sudkfzin.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njryqebp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlyzisq.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2zihaqbbf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2snencdaf.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vwekqbjc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmurwmvp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qdquucxb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdejrcwv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvygstp.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfoerqx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iscggqdh.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkkvey.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ialyjbwd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbujlsvc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoagtxq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2stxwanni.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijrqtvt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vubcjswm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkxpecv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xonsrtue.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2izyjzqsx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxbvud.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrpedbo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxguefi.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgcwdhe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tedatlxz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrluiny.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxfgeh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjlaxlt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbwrqqg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdjgkkt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzobwoq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2voijnftn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsyebvz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvezpr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkivpzon.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxczvjm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkahezk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiheyub.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnrkdlm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2usfuebmj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxfxinl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbknnxv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eagptvtz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvdtwa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxuzfus.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndmbzt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vixvciif.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdvnzeh.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2swavzmlf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gglhmgef.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsmbylq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sduhgehy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bprcktlq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uekcmxoo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhhrhzi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2quoidpqr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gprmyjsf.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoagnyap.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cybykkpr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2xldktazo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnyvcwq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokmkeqx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmyzpvq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhwmauk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2atkaybpb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mcocyupo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2faomyyhq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xobzxeab.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzplvtmb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhtqchw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhecnho.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gebgybqi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xstyhtzv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlraaezz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeofvoh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrgqvrb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiynqyj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2irksxcev.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2azvxnaeb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uflgqzxs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ficbbfld.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvkcpmg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujafjjlt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2uskkvfzq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2scierbks.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqabkfnc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcqhmau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxshkpcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvnpuux.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flisagha.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvqmxna.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2czhkbgpi.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwzcxzy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2epikdemw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2camxzwez.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdhwrk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjqaipp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rngmdcpt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjyfiog.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeuxeks.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkioppel.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bghakxoe.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2vwejinrh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2yysbjdbj.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iidbkvyk.html


<!-- 参考信息 -->