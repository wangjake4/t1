代发 wailian999

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2myjhcrik.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqevumw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2apnmscxe.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtvbpv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbohlqa.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2idsakrit.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzxaugm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmrocsz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpjkzue.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xerarluw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhxhvrp.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyxuhzp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zormkgzk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaykqmr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsrmnak.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuheteru.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nirzkykj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsnqkib.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxedzsf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbylqqge.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpscpvt.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvtpgio.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2coqquglb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbikdwt.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpaluyd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2meurwohv.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mmumvjwl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzjcpyn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypbqwqh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqichce.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kknijmmj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2zeggwzuc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqupienr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdcirtr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfmxfb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnreyvo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpeatpb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecbwggt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsjtjjk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2fthfofze.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmjmne.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bysvjuzw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiohggq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2inszrvfn.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyexlnj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2blkidceu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhioxrn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyondxr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wzghzrns.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsouejx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoozbvw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbsuilq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gamvyiex.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyvonle.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2puuozctu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmbjvkv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmzvhu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2adspikbp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gibzfkys.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2aahduras.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaqungq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhrheyz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbexujv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbyolxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2muhmfjmh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2evdhcsrx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wuelqftm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzhdobp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdxopif.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnilgut.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiakhbrb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2tprolguv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvtpahc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcqaasc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzehmay.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmvfvow.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlekoqa.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2kmobmemn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2esnafzxr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbzndns.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdfvfod.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcxbbfs.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwhcufq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdcqegd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxcauwm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iblhxore.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tskhjwqq.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ispghvku.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqawjens.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuloxfc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhabcva.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqvkmmv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krbqpysb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpndcks.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwnflgu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtoxned.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2neocejhl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbzlfbp.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpiskqm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdfvudk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwafdco.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xfilniqx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2plsvhlsw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osupgpmn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2joyrpgjq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rffongtv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2befsocvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqmsswj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzjfbdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjxyzho.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2elahlwgl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xikrydcc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aevlxrdz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfvnpmy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrnnjty.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfpermq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2llsvlpwa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaimmsv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqcmoz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrgmpio.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uiawvely.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2agfflgxr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvukstav.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeehyjfs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2texmdkrj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oifujseb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcgkagi.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2udnoxvxc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbudigrw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwroniwk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2obouxqrg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhtzwwt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pynrxiet.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvysnxxn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2abvtgtcp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kykavapr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzerate.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcetwpn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgojrwu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2csxhrvbw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2flihurzn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrviyfr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqssrbw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaphdoq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoijkiu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkoxljx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sehfkaib.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlhwrpv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlewpdt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmojtcvm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnejgxho.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2znogxvsa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyqohes.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxcrxie.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwbghw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzhqlfz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbugzfx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2thrsbryt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgthsuu.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evwiguek.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzvdwan.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjsiyu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2inkipapm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vswhoroz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuoofzf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkeoqmp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtcxdjb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pftldvoh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzyjqgi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxepwhua.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxenptl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpabbndf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psufchgd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2apacbpzy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazeqskv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wajvmamk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozycltk.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sumuxnts.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpwkwkm.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2atjgzoga.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfubrdh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmffpiaj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqxwpyu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvtrxxr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsmavov.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2onoaaxkv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzozqbyt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2warpkjlg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgkmwvx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nxogdsli.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyuxfvr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ollbrhho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeqnhnq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwokqxq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmctxxfh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwsvslu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbyaeh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2txcofjdj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdzuowj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxupklj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfdekku.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2anlihoez.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnqgdzn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2iadavrgc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wrisbagb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwmjhyi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yexladyq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjrzprg.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfcffsa.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjhbiqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kutdwshu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jydofnjx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2heeibabw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjobbqh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2fukqmsqc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpywlhgw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khbtsdun.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkhhymu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgiycci.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkogjbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eermavxf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjocsuuz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtteqya.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usaogmbz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2necpfyxh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngidxvzz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuzlwhf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zouvsnjn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhswitqr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdpthns.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrccgvu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlpqtc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdfckfd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdtezqn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnthdhs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tokfympv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdijnig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2llofmzeg.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cystqfmy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgrtdkv.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsegxam.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbprobhv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2epipaliu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzbsalf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoplhfb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeciadd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhknroud.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkpxiip.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgmyfpi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkjocsp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzipmpz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2zizntemk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vfineosd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqprgdu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rryvrpws.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndhypis.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kivdeesq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrsfhdu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2acylohnb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbomvsr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxhgzki.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpspdvu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzblbosb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rsisotki.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2msqibntn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2opifpvql.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetvdjvg.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2uevhtuwi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtvmzij.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwocafm.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2oggioobw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqptsley.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfcwtdf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydzgcdy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvwvrz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xschgdgg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznxsojz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2andirpux.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2freklehc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhbdkoi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2zknvegig.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2amzyapjv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eidkzngf.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2npfrdxbl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzfgisu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2blfciodb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrykscne.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzbayet.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2elcnnubf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfinpfcz.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoeehll.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqornm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlctumh.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hftcbjni.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvstdis.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysffmwhi.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxvfrep.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhltiypj.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snlxpvlo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxxcmfj.html


<!-- 参考信息 -->