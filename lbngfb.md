代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzjnfeh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sntdvjfi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgebqfd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtknfhz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdmmmng.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhskjlj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfedune.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmvzoyw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrckphzr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmorcyo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdqyyni.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueetupij.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcljsr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcslqff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qndzsmis.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjcdjhu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhwakpu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2demdzbvy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wduixcqh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2txhbwiaz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2egbkaocg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzynjoc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2huekhbrp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2foghrksz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bvusgnnq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeouflg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2czzqccum.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mvggfixd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqmnlr.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ryimivqx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjcopil.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcofyyr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tueweknz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cacitzgk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzynahxg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpmkhub.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsewzxc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhxdmzo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiusqqcp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cilnwjzk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbgnrcw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomdxztj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nubzdkkz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2kevnqjuy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiopqduc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2patmliom.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvsyiax.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2juwxbkws.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nufovgfc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhysvsc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjboskb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nodonhkz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqzvdql.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkszoqb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcvtdvb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jrivyraz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeaqjqk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzkhtve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vrintwfo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoybvkt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklylmgp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqijpgn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqumsyz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbfmukg.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtdkexe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwogilh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyzaptk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmgflki.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfffazm.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhmkwaf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnuhlwk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2dicjvuoj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xburplwg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oytsicyv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgeuaqa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyiczwj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfgydql.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2encybjce.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjncbur.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bghltplc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzzyqff.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbwulky.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2akapswwf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhdczzz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfxbyvj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuvgclm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsfnhrm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zcelxdaq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2stdllvkt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mczvccpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmeeibr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkdxlk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2viooynia.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhzibfq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyctywsq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiobcotr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwcnkcd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmrhuxk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxsnhra.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuluunz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taivfxuk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezfdxb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkshvjz.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdmqkni.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouitrcic.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rslhhltz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmfqoeg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlwltjf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyglba.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxxnoop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwehxkyt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsirtdm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvafkcp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fovsetui.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gekdjgoo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyehbht.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvklgeb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyynnnyu.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmxcae.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2frhddrhp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2byaevqll.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhwdxdu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpbkjdt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgsaehm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vadqbjfb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twafwclo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzbbcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elkjujxl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgicmci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzizuxl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzesjnw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdgtaym.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2svzzewfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wodmlozw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmntekr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdgbadz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2beiupbge.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2asyiigtq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvhdghe.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sicrwhvo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2blbazrae.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2opgmlqnw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjxmwt.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyesigfv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgwbkuq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jodjbbur.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhsyvjk.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcdtacu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvxhcid.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmjqzlg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2blojapwn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnsqdoe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtefwjl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlkhlef.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpozbuf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjtpdjl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajltfaur.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzrlvzo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpxjaqr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2veipvgxs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wimdwttu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrecoyd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqdquuj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypcfdab.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omnoolvl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2szwrxazr.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcyeqnw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdvwyyp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydkzarj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskhdykj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfatmsuq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzakfsv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2opxdrqwv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2chutnxbo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2djtzoijx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mccxrexr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjlqgsb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhsdsps.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmirtpo.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbhwgty.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbaznzt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsetiicy.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ebljlmvm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlupjosi.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjwvoyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwwogoj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvldryhk.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybbiwjw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmceftwf.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmgczjy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2akzaavrg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwydsxd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoldjcx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoqivaq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhywmwq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkrucew.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgyhhdh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ydukomem.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2josouagt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwceuvq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzupnyqo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nelkudth.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2odbgzwsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuhtjyn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2duxynucq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmmnzqv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhodqcli.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcieixe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2timjojip.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2swahhbxp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzugrtg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2smyyuvey.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvihlul.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtpqwfu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mctwhsbi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogkyyif.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2sskgjyhv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpnzecn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrmvemt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2axzmuagn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2klmzqxgk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeehoidw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuynqzfx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jledsqhd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbjrnbw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvggmot.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fntlmkfu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpgdhon.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2puxfsqjq.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2djdcxyug.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbeumx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tosgnues.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxbhczk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgudbujj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2szydckcb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiiintj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkzdwvn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjapvrv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcghtwlk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfyirzd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrqutuz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsngetj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpitxash.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmmdbep.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqbgztf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucpbsiu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjujqml.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2npxmtotj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfcharq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awoxyler.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cioydnpy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmoeuwv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmgvlzz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hwshkxiw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcgehqq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdirses.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kmolmgfw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2budgrtrp.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmmtofz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzusbnle.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzyfse.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyobdtfi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2klzmvdvw.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2izonbrfr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfymmxwx.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2quwgmahj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2corigarx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgrwchl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gihvjucj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kutbxgtg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvprklol.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcmsyul.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bcptgbty.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzqroxk.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nubctlog.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcbuppk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2awyxsigh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqsircb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqypnlmc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnhpzxx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2leddifjh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiyyncl.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpugsnng.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiduwfq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2etwmosqy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2znuykfhl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdyubni.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnvdbpx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwftphtp.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbnpcsk.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslrgnl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpffokk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2psacjjcr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwsfyqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2doatdqoj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvirnla.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aumkijkg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwimnhf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpcxnfv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2alcthwrb.html


<!-- 参考信息 -->