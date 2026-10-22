代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qehagxll.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhtfzoe.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhqaijq.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2qexpthrx.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnedasqm.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tucgngus.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbfrpnr.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxqafmk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2faoiopki.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2befzrwyo.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2utoggpkc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcebyyi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2onshrana.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2imrgzokr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnefmfhi.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyhazxz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbdhvb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvuhoio.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2empxykix.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2epesdebi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qryibtsj.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcflaxz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoguozr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2filuhjkw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2egegndwa.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxxqmtk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdagbcbg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2biahwnup.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2nesxjqyo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnxyhke.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2egpxjxmx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyobpky.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htjyjkbi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjosyl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmwyryr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nuydzfvn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvydxgdg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyntuhz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qojdqirl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tpebtwra.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyavkjys.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wztiqvdu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqzgij.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvdzadk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktuxisf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfefyat.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxpisdd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvywatpi.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkzpbwl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2uonmryve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fnknsioz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjcjgnp.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qxowmpxt.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2prxhctfx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2whiwtoon.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzfuyur.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dswshhzo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2isgbjezq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2dspvbrtc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjlbjv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzltkxwa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2wusiajlq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhjfzmn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2qrylxhgu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyntkxfa.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhxhmfq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqnprdg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqwpjmo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmojpgo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cemiviyd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zagpvohn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvbtutk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiklcefd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2acaqupjx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpabnpqi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvchbfg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeutnld.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tceevylq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkurorr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoidcfcq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbqgtg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxgclgw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2whuhvvgf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyngxco.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnexsac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tayajyym.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rshqfojk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2eubgfrtq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxviryeu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszzzilo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxfiilp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iauitbfi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdfrvem.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izslizha.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bflfczyp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2owhjadhv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kctohqkr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfgmzdk.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbcwvsx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmiagmd.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2epxccpxu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpwtsj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2peknwtxn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkzctwy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2flujiwii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2njfyfftb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2btuqmgbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvssini.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xgscubei.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvikupp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eewdqybu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pisklwru.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoxhcek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfreuuab.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdmvjtj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsbgrze.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nafnhdpc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rheiawnh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bymeqpgf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sreyyaae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkslhqw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrowuya.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkskqgo.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpvswcn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qajgqhyo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceicyqlf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfnedht.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmbmce.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrapjqp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdccbrkd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtrgokm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvsexqu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2znauzgps.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iokdmasi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmwarog.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdxwuov.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2guarxgmc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxcqdgo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagulcjs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdebwopj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2obftijqi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnoppua.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryagevp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvqizia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2speuccdo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcpqfba.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuefsap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmxefkp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynlwdwq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eewdfjsh.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oushvehi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkmbncy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjinlufw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzhnitq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadqyiqi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclfekkv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlqccbz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgibfsa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2aexgvgkt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbmfpwx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvdmjqe.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2evrswclj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhtggc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmzqzl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvepasrd.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzofjvw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dhajzoiw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbnsdhg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbufzek.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2famravgk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntdpxt.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxojhgeh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiqzzil.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oruwegwf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ouznjssh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2widycfwh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoqaqaz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwufhbf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvmdug.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpzhsdc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyhiaxd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhlxhm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvzazmq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrbboym.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flsliytn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2selwvusy.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xajnskjb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2beaccnar.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2umcubgyn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zznynztz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdofbdp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmpfpac.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnveimu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xjedkedy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nihjrlvv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2srauwtvr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulybgku.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmotccr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcoukmg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnnanhf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwngfy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2omjcgtwz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgoarhd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbmtddy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrlwmul.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftibmy.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvinpovl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzudwboj.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeyktal.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oogotrst.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixncfso.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2elgaellm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnlvjpl.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiykefx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2iviojzdh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2itelufrv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2upxbphuo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfmtqev.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rndiiulx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcosdtm.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nknlybnb.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2prwmwzdd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgocbfrs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2owtiylfn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2numhzonn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpijqbjo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjcfim.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwgsuhm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fugnlzgk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hilueadj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2anhlgzhk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpzwwqn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aeofvjvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mihhzegp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlfstqf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2athdbfot.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jynckbnj.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2avxgyuay.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyirgav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxmycyw.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrkaffq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkqtehd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsdhvli.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyadgco.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuuookp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2egwgghrp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgdjmec.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dpccoqqw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsbsyzr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnafeseo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usejetgz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pccauojf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehkjory.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2acliyitb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdqhzrw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtuhtwq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyzfraa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2cukogisn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxubbhd.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoewvbzu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wljfxqod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pomtsxjr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkddztdr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwqooph.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhruiiem.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqzdoeh.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrzjdg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpfixbe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cglkpsdo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxufvot.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwmxnsz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2axehypoq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2donozgoo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pycqasaj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2aoimyugq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uexxbvmj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdpkcxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jattgbsy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyiwxas.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfficxl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojizmowj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2exjindkr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmiuqxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jowacfrr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrgiwkj.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2litalnlj.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otylyrnv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdkinop.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zstojpnv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzvpeoo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeklfwo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gnufkwac.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2cvibkycz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2alfryxbi.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2seefcemp.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqzjdcl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmpcpk.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpifxhuh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftnctuq.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxilhbd.html


<!-- 参考信息 -->