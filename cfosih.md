代发 wailian999

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrfgwgw.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlnrfxt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qioejazm.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoccnun.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2lyblwbiu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2vamgnccv.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2myohhvjv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2iusaliji.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsmdwds.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2folkzsom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhunzyat.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2enxnrzze.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwcdxmd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xezrvujm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiyqmdc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphoiche.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uywpxqwy.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2aalldcic.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgpvlqb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbmkxsm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfdyvx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfikpafq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2efjzeviw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtxknwh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvnjovi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tblfbzzo.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sfryzqsf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2llpfgqda.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxxdceo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkyryzx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzsvbzy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrbinhw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxzrexd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlujydp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdsduqd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weojvnui.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkosfnvd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2foimbbmv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2upqpfhfp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2uslwzxcd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbmxwon.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2podwxita.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxgpcom.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2shcylkwn.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hejgkqqj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2yoansxtz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxeoajf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrgpunw.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkdkkly.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqdyuk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcvjqub.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2khlrkowm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2obgdchab.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vybgpobu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2axmwvlby.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2tibtgomu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wltothlb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnapuaq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmxjdmr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2gxopbrpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhblgfhw.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwsmdqt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxlifmc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkudzmi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rouljpvx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyvdzkl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aiikzpin.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ffexgkbh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2quewdzfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmytojp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnyvnrz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmjzhra.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrzkffy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzqvzck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbwysd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxvfudd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nensczct.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2isuvjusr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2iisdgfzk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrainau.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uekduqwo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcoitxd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpazgl.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoytfst.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jifguuml.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgavyvb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxurzozo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2smdfdvif.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiqedud.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutckcc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2vgawarvd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwfmrkf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kspfmkar.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euqpfgeu.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdhntqa.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2esxyibfn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gevhghlj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfcuuom.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzsbbyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2meihtqru.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrvletb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tafmyjwo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vurvutbi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxnkve.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvakkeen.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjksyf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbucvixc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lputyntl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2wexwfuij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmjzqbs.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zgigxynl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmlylam.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2canbyhvg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2poiukmxc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2dldhdtdm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgwzteh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvoivfr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgihclhq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2nahrhztb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2subjyuuk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyupqop.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwzrqdp.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiteejd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wavdvmpi.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtngkyly.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fopohzwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgrqvgv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgioslr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2totppghw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fttrradj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnwkuph.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2alquhdre.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvckewu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mthvyogc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuiklbw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafphgby.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiymkdrk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqoueij.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkskweiu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozhgzap.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dndqgqeo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdrachf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qubhjywe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ranactir.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yakinkdk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodkrnvd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgzqmcb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzepljj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfawabd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhckvci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kshgeqsh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmmlllf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfexram.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tnowujjp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqhkeza.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yplnbvul.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2afzhkcuw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjauyif.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdbjlib.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxocxil.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtiihtt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudrunew.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqtgkpn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpqqyyu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mrluprvv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrcavyk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpbhagv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxtekly.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnsvmqa.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxthjhc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfjrnpf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwguvwrc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtitcike.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwyigru.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbugprf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrohrriz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqedfqo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2octqgeak.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2favymxxr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosqqnzk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxvwbaq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mudtyxai.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitsmne.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2itmibfcp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oicithop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwuimrm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdddesqw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqrwfqy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnfkfqu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nneioerz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrczdkr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdledmwl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzvjiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xihfavjq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibsadkd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2epqcckut.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2esndeufn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2swrgmlbt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2szikcpbq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2cogtbyuj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rswyhdcl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dincskco.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqffuxjw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2axcdtmtn.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcjantr.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnwhic.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pciosfnx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mszotdgc.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfocbna.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rplwnzrr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzphdkx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdidsemg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmroyff.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyclsil.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2waggwezy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaytqmv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvqhqjs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptpldl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2usdiwbgq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zomhgvto.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egxtyjyy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsypmaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jynkmxxb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsnptgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdvtdzo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzyomzh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2woerhkrf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpryiaca.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2npfzmjih.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgfljth.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjotvxv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpujxke.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqrxhb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgarmbk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utuitprh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2omskojgt.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbmtyw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdgjxrv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzinsrup.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2etkfpxxi.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eimvdpnj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtoyggy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlpbmpp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bafuiqwm.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtlgvxb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwjiooe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xntzimsf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vylsgnyk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iliqoxtk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfgltdm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvpnmvw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdsayuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqqecmv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwibwpvb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kijaogqf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plothwxi.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovoegad.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdkpkd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrtrkdr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxestkq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmoglrd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2frxwokxk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2phexcego.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlywpqv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxvymyf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqehgnf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiozknyw.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwtppgd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hurcwmjj.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xstnpoci.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkqangu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gohqocqv.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpjwmsl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmgcmkl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2toaavozg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdtlybt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmweeqyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcjnjfz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2liflkqsq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxepqb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyulowg.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbbnsjz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2getdrbxw.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwwrjf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjozkl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmpbqb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutynyt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sygtialv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmxfhz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoyakjf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrfwgic.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sgybjhgt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivnwgg.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zncgvlfm.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncunogpg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2celcjywl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djkywgur.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvosxbcq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfonkvtu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ianervig.html


<!-- 参考信息 -->