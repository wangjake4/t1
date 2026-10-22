代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2slzczjxd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jknhuqnq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eneaenxd.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqxyfda.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2cblofpid.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjxrxdm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbgkmqk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzhszuw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2epqgrgqx.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqjvvg.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaltijo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfecmkj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xysagrhj.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2lrztsalg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdzuwtk.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qondaukq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mitjbjtb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiiywod.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzyxual.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbnwbiy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lawngzpr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgbwxyt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfstznrd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fccwybwc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyusbdsa.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyhuaev.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhnzhzy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2uwahlgye.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgudpn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2lctkknin.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aubmlwpj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmezpuzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyujemi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iphefrsp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axkslezf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkbkmyb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuizjhnv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2addoqdxq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qapgxisf.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkjdmny.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxsrxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrbsvjt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jleundbm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkyqpyf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzsumj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgswoxt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyrnaan.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2npchoxql.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrpuoht.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzpltuy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2xscbyucl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcxoiwy.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgyikv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2csjpunqw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aftgejpn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfpdypj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ttipjmci.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlneajl.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnrxytu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2esfaxzmj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wazqpzrq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2pljbgcuc.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2quyjplxg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bwowfxvd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpoysgv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhainvgz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbnqkr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlajfofk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbirojs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgipdyp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgyjgkc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlfqnmg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2iooijtir.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhqafqs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snuryycj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxqywun.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2swlklibu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prvndlnk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2gghfzoyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klazuyzg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmrgfbl.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfnwqta.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzptmdfy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzyccsb.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zisthhjo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhqjty.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvgnnbp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2oogkatxt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcszgdqx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkttrety.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdlbwuv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbjathv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcvlnyx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuidvqr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2uffzxcip.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsrqnzw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjosrfzj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqabxrj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvnpbue.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qevdoaxf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2czobzgqu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqghqn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jpezqrag.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vbujdhcg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzjhikd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvjplps.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeswygu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppzzpc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoasnil.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgdyycp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzynczry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aegmnorv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiulwnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoorsya.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmasrlsf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrwdhct.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsnnulf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgymwb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2edqtbwcd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2myroagjh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqpglkk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuyzdxi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xavfyaqm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnidkflo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2puvhrwvj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyntkybu.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqyqmv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyibotdg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuphougf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzodidln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrvgdbl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvjztjv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uaglhdxk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmlkccx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyoyxjc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcymnul.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyvbwpd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgfqjt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlgwmbu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxaiidu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlwslel.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ymidwvkc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqsyclv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxwvce.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yutplezu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xobmmdce.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaljujrq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcybiru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjcdpi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsiftrz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaghymb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zhufqwae.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2halxivap.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2htiripnn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqwsupl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxviiwc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xxufnrqh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uoetizxp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmaznxi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuupqtj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehwopww.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2otmvymuv.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vherzewg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnvfovy.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlpitsp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdzstkz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvcpxkt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjwstcc.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnqypts.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvciqug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuklnjo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvvdbwa.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pclqnajm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trtpqhzs.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxeyuer.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2avooyqwq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyxyrts.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyecosr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzizfrkd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaudhffb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbdprxl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgrsrzv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smjvisxb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsxiykh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzupqlk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2csqpmupk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2asectlid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2clsjciny.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlxrvtm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hexdlbnx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2oamxwetr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2icxzeyob.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmybuvy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvenkhdu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2itpkcooe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2osgcqmsw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaavioc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lemukdof.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtofbiza.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikdlzuj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzdyptc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyfwnki.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtjdukh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhbjxt.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfgfntg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmfyigg.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpmbevr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxglvwdq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzltidbo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbwslbo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2daldhsrl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2igufgogb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyzheed.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqizjhd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvtcvg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjdmvhy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvfbuzf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoidunz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2csjlmrmk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocytwjbi.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthjuowb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oblslgxs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbzpmdy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eymtnzhu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcfqkgc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvdpnhz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcggzbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zswbeuvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qftivqws.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwvmxxn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xflcmslo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2fctiybfc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmftnxee.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2adjeujzr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqvtclu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djlpzqkk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhkvcyp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2asrqxgpx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdkuifr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdewawwl.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjobxjf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkurkla.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuldepae.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xngbrrux.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgydiemv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dspohsei.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlcybaz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2oqztgfue.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojxbbl.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqwbkzs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whbvpvci.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjffqcy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rprzbqse.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqynffx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwnvzru.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdscrjp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2epkmgghn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2xegmqjdx.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmiipvv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibfqfbu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2taiuvakf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcuofzz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagpgzo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaysbxx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eociofmo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2prdvujyi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctktnpoo.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkvxcco.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfkkjum.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkdzvhv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhinzzq.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzzanmn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjfzlgq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdronvbc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2iswffacp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgralny.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmydkmin.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhajxnk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmpwnei.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2abrraqpy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jygtvemd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2usafedbi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2qlufyyco.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmfoyv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvmfaqn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cczcsljz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfftdtjc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2clzilero.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ltppysda.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vtotbfel.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjugoedj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lepkdszq.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkofdrb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2boeejhdl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zkicwcoc.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzqyiu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyjumc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcsbcc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwgtstr.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhdoofj.html


<!-- 参考信息 -->