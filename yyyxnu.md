代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2vfshklix.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmmfdfu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwovibo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwomrws.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ikonzoyv.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2auwautkw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeakbjc.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhqxjpd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wznkziqz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wargbjnf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxftefu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrexmycs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkssnmq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2svplwvha.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjhquzg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lywqzdwl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2cppgymcn.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjbxehl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhundko.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxlglhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdvoeny.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzowiyt.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwroamx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuwsazg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vragskwx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbchpxk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvryzudn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzlicxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvupetgw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khfeqvew.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvvxawb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzzpwzf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2roewjnfy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsveykjg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ursmmvoi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jthuvxob.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecicdvod.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbujfnfa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlqjumv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onijtuuj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcdlaom.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzbuwez.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2hsylojxv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2glowcwmd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwlczlo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2codfckym.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnzorxd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2odiscubn.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcasdey.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgkzmmf.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2geizhsma.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjnwbbe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zyflvgfi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwzgxjd.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjusgebd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmwtqgj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfmzrzg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2eczmozqz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqzeiky.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zndkyvja.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjunhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbhyqji.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzhflfi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2liendeik.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2awrfdpjy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fheyuvda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ammyslkj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qndepdqd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkfezgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdmoois.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyaoakv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjkynhz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkclpi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvfthqa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2drubodjt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvovifdy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzfltf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuloamx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivogxvrt.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yolxfxou.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjbvobn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrqizpp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcwiwdy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxcpcme.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqycyipy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idfshwto.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2agszoyfh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghtxfog.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boakesgx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvklqqac.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqbityy.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbzljcc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2onfwxtvt.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2eouyuihz.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qodgdglk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2fudujkto.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyypmvb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kacetufm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cecamgpr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcbxrxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhblfos.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aymnqzua.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2silctrkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jujkoqyf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkgugak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnonqymo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzntyfp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2haevbgfx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2djxrabwf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubcjde.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfpahfp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxyaaxu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2iprpqxsg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgsplsl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoemjut.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsptid.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcylzwg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuupbad.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncetszbp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njmiljso.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkwarkj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgprymt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbgntly.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjgsmvd.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cshnalce.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvulzrqs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvwodez.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2itdpvhva.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oscnncex.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixkacbf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2plngtsqh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnxwkby.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2clawnzot.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsxcmzd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzqykr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkpsukn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedvzqs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuevfhgb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwujqsj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcqfunk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufohvzmg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqeoisf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwyuhl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyptpkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsuvkdb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqucoth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhwoiqy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcaytml.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dftgjvuf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2jseptfhq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2shctrsff.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmffdk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fksqkwxv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyphusg.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnkfhgd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhpxrr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiboejs.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyegppq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzhoigw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2whqqedzp.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjogfkix.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdgksiz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2moduifms.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2niioggcl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejqhpp.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjqvwbk.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmqrdom.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdrsmke.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owtzqwdz.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxscbav.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicdvisi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmygesx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2huorewnb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuzmdmn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2skpmamep.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhygfsm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sedkzfye.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2caqgqzvh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqabimy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2znfveefg.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mklntezs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgpuzbr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrqhrcb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxocaq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bohvzzyo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuzexhg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjjswcz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2nonehlbf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iitmtqer.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrmwmqh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dseqqtvg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowpybsu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2snbnpboe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2aawhppra.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjozjwy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsjviii.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2niclhvrx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxgyjfh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfgnfri.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnigjyt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyndpug.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoqfyyx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbswris.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhbkpjk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvgbbdd.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wscmqydl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhhzqfm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwbzmvh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdhradb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowljpyk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2yykizzrw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiklythw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebvhihc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2crgmhrlg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2eylgwlpr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qayeysjz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2onkebpmh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlilbqzp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzmtzeb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumwwdl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbtvifq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxufsgqg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjsigm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxjdszl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmhipgu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnwbvqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoiwwvb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btaxvctb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjevqpr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkcyhir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bphggzrz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoadldm.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmrgpwa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbspujky.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkeedbh.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2biyignoi.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnndvyyw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyshkpy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuijkha.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyxtcfv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2exkbwfxg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbovazlq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvptsrq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uymdxstu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwtuukg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcsgqnn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvcyndl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkduohb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzzmzpq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydfgbq.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xltgigdq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoabred.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atlatkig.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2spqdvwtn.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqfechv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2djmyqosf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoisvfgb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2qodiurbo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsrubpr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmsirep.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lwesgcbz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzctvvz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kswkjjsu.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqwdloq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zludyobe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwvvemc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcexzvh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaswxdco.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tijsldbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwxlwmy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2amtsvyqp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbgyftz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2evggzekq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyxgcxg.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfmrvt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevmwban.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2psxukeee.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2esomtqoy.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkpckpr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqkiyt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aexyzpwb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cooxxiag.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcqnabs.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfwiypv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2skmwmfzg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwffhtj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icaadxay.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pcadijgd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiqtlls.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhrbdef.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnzfbsu.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzgjuvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhraiuf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpubcfq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkcymvl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2kogntwrw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vezlqlzw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yppjcmfu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvfbunb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoxjvpd.html


<!-- 参考信息 -->