代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmpdzsx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxscuzx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qikzcjon.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jqteahad.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcscbjwt.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjmyymj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhvsyyl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcfrqci.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzlhjjd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficrzlsp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcfgnli.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfzcjzh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdoietn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmbimwq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vadbcmtx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2opczcgok.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uigrpsrg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfgnvga.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xevcsftq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzkioef.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhjdyvs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfprwbr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwechumb.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxslqxk.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfxvhbw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2njnkzote.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoijlwk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzdihri.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxhocba.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdbjjl.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoslhaz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2elvdzejg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2edhniwmx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbtbrgi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiqyesr.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcauqinj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdzuxzz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzbpoyd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpfswfc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxxesqd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnehjepu.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqiypis.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtinvnk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocolndoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqtoaui.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrsvqlr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2avezvzvy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqszbdg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxvqfnm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmgegva.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2stgiohsv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2lembcwcp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmabgokk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upuvboor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcjzush.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qycciqji.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyvwbhx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqepkwh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slhennvn.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxvihtm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbcgfn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrsxzwc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2walxcmbf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkyazod.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrzdzmz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sccvcold.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstrqjoe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwmrgqa.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2flskbjcz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzwolqd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2chbclqcn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmibcia.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfjqfcv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpelrze.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fumqelvm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2movryxeu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfqexx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oiomnvjt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsvqpxt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqocdzgf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjxshas.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzuklbv.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2omybwjhl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabkuao.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2krygwztg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2papcvsdd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjrrlmr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wenjpwxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfrszxf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nccqojbr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2winzwati.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwwxreg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyjlbvd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2omqngctc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoiapca.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2guhgrczo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2osiuqwbk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlvtkrt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2beqxuqlw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqszfdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjidzex.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2spdjxups.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnnslpq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vblsofkl.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krbwgose.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bavkfpjy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnpnlih.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgosgrvl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmczlwor.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfxqioj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2esbftivs.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhwsacx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2beialgcb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2biroigin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2emwkueyf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtordpy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmtarlv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lojspajv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yinukgeu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsymikh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvaxkp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcwixvx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2feyhyhsd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jydyppzx.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2uloapabx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pptqivae.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ovalulft.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrybfhh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuzxrvf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvfqopa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgmldy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ektppsae.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfuoxky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2docvfosm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qactaduk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2prrxlgle.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nilkuchj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrzyhjt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmdaufz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoqqady.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaoslkn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvhvmv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2elwljqaj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpvybqj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ugidwrya.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2odpufxnv.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtapgzl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbckvvod.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqucrgoc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucbrgoi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrufvv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmlbtfe.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zttpkagq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2astahpht.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaobelfg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzblzpo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhntouo.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2macdenll.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2luoiakzd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlprlnkt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhoadkg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yozxhkbk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaupiqac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzuvdqv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdajyqbq.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cumqhcof.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxweubs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodyterf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmovfrqe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpblhedu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuydinz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2merijbpk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylplnlfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2syclquiw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnufecv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oggemgqm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpiacnx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcwrcop.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwokgney.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxbrphl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdxwmrw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tknuphlc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvohizl.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcoacsp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzmdbop.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2agvmesik.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zlocdzzt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxxhezj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vikblcdz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2lanbgdsm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qniitqnn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrrinam.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcunegu.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kauxavnu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbpupeg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fluzxphj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2munhabur.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqovwop.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkzhaqd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcznwlmm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2occonnzx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqxkyjw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwohfnsn.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfhulsq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlplxljb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skhwcjcw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaunqxfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbhujpb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaptdfa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2blwryuek.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptydkcpz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqqxhrt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpgxsok.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tvojeawp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnsldvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnjmcbn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeczzsoe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodrwyr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrxylud.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uunxtngz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xtekcxxj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2flbxefms.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2plfizeof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sriyzcln.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jovhgnkf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzacii.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynbcbdb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcmmdmw.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtkutui.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywvleju.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjjhgcl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpwlits.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zelghqot.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmmcyfx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgryerf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pghmpxns.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhxqtnl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjhaznj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2aknycxki.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjsmizi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2volgdmqk.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zseqoeal.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2buuvqdgl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnziyfx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhxmbdp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhfiuyu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2isiwlary.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2msbuelbl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mddcbfol.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskvzafy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavlycx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2scaoapbh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2exprtaws.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwpcaen.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbuvakv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nasshmwu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcfsxw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2soiracmt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjsfytd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkacpnsh.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ceexsutc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fczpriox.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbwfek.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdfxedw.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqmzpjg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2djguhema.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpmmlcr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gksgjwps.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrrokla.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcvumsv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2isqqcupk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2goslnpum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2utikjxre.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dulipunr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqsdgur.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2efhxwegh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cnztgmlb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhqrybj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzehqqi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2huxuoyku.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2umzyacyt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypreaqpb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2azywjnoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxbwquu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjumxgyn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaywtpm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfuqnq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzuakoz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2heybkdau.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnklrwpt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiwnoip.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fezsyban.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzotkvc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aswxczre.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqwcsgs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwcqqut.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgfvidz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmvupci.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdbjtwr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwywjhp.html


<!-- 参考信息 -->