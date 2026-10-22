代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxjsuza.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmbnjhk.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2crktskbt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ezceygsh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnaxbdt.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2uqntgvus.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwjlyyf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vypwodjw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gigukkur.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbswzzq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2doieneqb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gahdcdjt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikebmb.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsdtsls.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2avffegdj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmellvbo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkjvzwl.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2raihxaag.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2helvcenb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwuwbrt.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwbksql.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2tftawnhk.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ocayxinp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxutwur.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgeyvjg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqouaddv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ognqqxyf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiwicho.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikooofvm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnncref.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrhoqsi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fysawudf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkzwlqp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevmomc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ebewwyuk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2cshaqham.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwmjjhf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dglbdwqj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqgpqbr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfdyuxm.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lrexozbv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2maoftltt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszyhcd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdgamgn.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjmluwj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ylerylss.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcgosca.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2icbgomdm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vktooxda.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgxxgm.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzhlxzc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkplpni.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqltoyp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuwfzcr.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nugttshd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfutmjn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrjudkh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfbhvjb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2fdijjcxv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwmzlki.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvniajdm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixerbrhd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2askixake.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nscomfcq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2pssesrys.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxojjc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qadpbymn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2vyalfznb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eymyhhrw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryiiiuw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrckvnn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdudytx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdpzfif.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsoazfo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztkxky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzpirsf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyctagut.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2cshpnymh.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgguxol.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqslvuc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdopaagq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omdhfrnb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyexkxtz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgivcpr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2rwycavgt.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aylhhjor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2voptuylq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcohobcp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqyljxm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paoyaecr.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsxnfxc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvcllsi.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2abxrcpoo.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2njqacjjq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rraqsvwo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfveynd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrxqkmv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hbldvuxr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaddbii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2davquktn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ygafqwwy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqbvxcq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbhgwgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcvkdnd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqksbmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqvubmk.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcigfbt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2yquvrvlj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuohtjli.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rltkyfzw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnkvqrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzvhly.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcswalt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxvrmpc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjxdqlb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mscuezmh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjvrjxa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2shewmott.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2devhgmuf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cirmuiku.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhvbwlp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sibtxcww.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzywaodt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccyljxy.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urrvsopk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2udgydevk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccdqmow.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2slijqwal.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tknjjmzf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bismohry.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgzmbwu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2errqgera.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwffiud.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqctlxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzrejuw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvlmawh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjydhtjp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jltezrux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2svucicxa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhpcxyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnniflsv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yufphnde.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmagtts.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hkutwfow.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocazjwxp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlcyekp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oowcmfkl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2klvghdbx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sacpckar.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2enymjyka.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2igipdoja.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqivxlhi.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoduhkv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvmvxks.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdswtawh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkovdhr.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2mewhadlx.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyferdsd.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjtvlyu.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2rasipfgm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2syyryhkd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gttlqwnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopovts.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeblwij.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsjcown.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbbipjy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuopzfm.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbftdpq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zchujjpt.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzwolai.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xldkyknd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmpyarg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazfxkar.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetstuo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhpaqu.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2saorqmgn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycjgpuj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrphiie.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsearlwb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsdumex.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjjkbek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ayozayjk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpocmq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2albquvlb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfxibwu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eyluvdfq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2shqjtxeo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqosqwik.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2juqpdwak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2frjddhzd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gexgrphf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2neiozrby.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgyqvyl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2omtrvzwh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyxpxkd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvsmsie.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiywnkc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2npnchyxz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxetkgq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2kphssdqb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2kukkcmks.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwanyeh.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovogltc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xznbqrfe.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2galbechp.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmqxxce.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cehkrsjk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2puesmtgw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxafuolc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvsekpd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnnrubf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpdygya.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssiapsa.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfueymo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjbesyg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvzhiem.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sessjcji.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2srhokvlo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2neywnhxw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2simexxgx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhrpiz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvxrluf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpchkd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vroobtlp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbeieb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2doiihkye.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2akxqesib.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwkbvbb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfcvbkp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qguwizmz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmibuykq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzuzinc.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvdoogl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtwijsl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzlskex.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbnljjn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2chbpabqo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmosuvo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2eautzogh.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ppctqaxu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtwborc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2upydbmjt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohzsndd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbpsmic.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmlnkum.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wegjabye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxagyzp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgmfskx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxqwgrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfsctz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlixdkzn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdwjybh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gksuraxg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrwguqa.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjpubqa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kinpvhnz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzsocww.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbsnts.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2deetsqhi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwnjzwh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepkzgv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2scbgqatm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfisqnb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hngfqarh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoeesgy.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlklndv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2cghykece.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhdzkdc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zedjmoit.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwfotv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiwmprs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjthbwe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcwrwgw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjzfptd.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqizqzy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoxerjm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fogmezld.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2sffogllk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmesdvgg.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjkindg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhsrco.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gaejaqtb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjmprdc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2shpcebgl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2radcbevl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpumegj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odmduaux.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2drzzikoo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjjbnp.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobvkwvh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iauwycla.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjvzrv.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmspspf.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcinhltc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioqfxh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2aylqbzuy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnmmltt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mfczlncb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeivjtj.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaynbyf.html


<!-- 参考信息 -->