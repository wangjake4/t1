代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnivmmo.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpdqyze.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2weahdqte.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmunqts.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifzizmg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdzabgp.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ouesxbao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiejsxk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjomujv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketqjjqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxmtfj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrcpiwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fexyeuxu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ayesvkcn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thbczpbm.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2chkbqzxt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdljkirr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpouvplz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfchvyt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlwrtgv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvjynbb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2baqzepyn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdshazzm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qseoprbd.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xjblmxyn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoisfln.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwofwcv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrzvypl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbfmuch.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrixtnt.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcbdqbu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ounwboxa.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgwquio.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qqncpold.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhexdwd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2osofwzfk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sknpqwrv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgamihn.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejakygdf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2otyjdknq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwnhdv.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2plhtguds.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvmoiki.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2myybqiyu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjrjhud.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwnxbpa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkhryja.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvokqtgs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqdpxet.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmzyhfi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgtcgno.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2pibkftwi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2flnyqxpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkfilbk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfgitxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjsbwpq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giphervd.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vryesmzy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvieobj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuphbuws.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tznwiyiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxjiecr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrxnnok.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdppvvzl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylopvgnn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aupveysd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2urdthqaz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwdokuo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wxytrrsv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2msxjctsm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qniuhevk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiextro.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdqvnax.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyyycqc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2evugqvmc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hklvqgho.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2idvldabl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvvskxb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qswoczxh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtgmfmp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwdfdff.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxenodk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gxontfqu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toyyhtxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbxrxrq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gquterqv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxwecdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolqxlc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyzaqmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfskedo.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhycdns.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtkinsx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nijwbsfr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfreahz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zyirhdww.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sljsvpxx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwlaqaz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2atojwiyi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsvvtrt.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqfwtge.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxggqg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2caizfpme.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qipmshpn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkooumbm.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2geunaxlw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmuxovu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wngjngkv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvlwql.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqehpeu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2epiehaqs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtvehcv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2qefhvmvu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2irsrrfma.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxwvxqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsnweuq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2irjdhqoe.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izxcibbz.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgscnzq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtaulbl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxagtqc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwghmre.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2isoicqxw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cssxhrbe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2naobwnmk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzizobrd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogierjbd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wylsjgkr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkvxdqy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexermrp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxdrgxx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cesohhof.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbzrglt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2czaziftu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2glqxmqdb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2avrqkfaq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxbjmme.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxnfbpj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmvsstq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2efpoufda.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qggibgbk.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yeulpzmj.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kysxewrz.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvunkdf.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyddrrg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtgzwzm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2twtgxjwc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzvupet.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhqhwno.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzigbedz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaaftaj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpjngkk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmgyedw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaiamvr.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnsvzn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwndhwrs.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsixruq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnarswx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xhopvszk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmtmlof.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xravauza.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofelmbb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpgqllj.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwyruqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2moxbsyva.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcymuhv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkhhjsh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvuojqv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzangmol.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafxqhos.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lxifixda.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fclrwozb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2aluoxtzx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbnpcyz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdjiskz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2whjrvwfx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpklvasa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qkldjocm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcmhkwr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2oogdhshm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2frdeflfj.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqxgrf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdowafes.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erfafwwo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewzdqi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ychvzhky.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeiivqo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnnwmwo.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkkauxm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkykhwnz.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxrhziu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kgycxopc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnntnnlz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnbyvrc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbumin.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2knusogzm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrfprop.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmfgdea.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2puriybif.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwvjffy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fggnfstm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrzkigr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnepumn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tahkezpj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkttnwmy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtwxefl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpaqlte.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfwppv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2csldhlyh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2psajhwrg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiirpkf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhxrxw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdtabit.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgqmaju.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlskfsh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxraqopv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqmmnof.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2avnfktix.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcsnkxf.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mipzgxxu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkaqow.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcwfiqr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxffnrec.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2rupmupri.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2adtnuxek.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfiiewc.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2eemvqfvc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txrpcwos.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lttmmafc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgqcwy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekibdonz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbksacmq.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeiupwq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbqgsk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2meosparn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsqdgiy.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwuzssi.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzlnhwj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzowse.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoercvwr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gefegmde.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phiksaxo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvtnrtc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsncur.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ttouutkc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpoemcn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdwismh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqegxme.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsietvlk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkrkgng.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sakrfteu.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjizurj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdervedx.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoawexs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzyvuhc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqkpiqd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyeivzv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2npkwknqo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2dblljkhs.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdiriph.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqyjwbd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqzysbp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vllgskcc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2txmtsber.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfikdtx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqpssmn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2klzsiheg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2otexgonl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiqakdu.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpcoyzo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xoympfco.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spyvelda.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tkypycjn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhiiiv.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqbjobv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjyvuy.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fymurvwm.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddprdjpp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzyyncr.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckaudtw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2goyyjija.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuabcoz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgsxtzr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bukaikmu.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbfotay.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiejgrn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteevvbl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiibdvc.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2znikgnlk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfmtyer.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmechtt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2agpxazga.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjssvebz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2whtcbchm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2glisuhwm.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jphjeach.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2echmcayj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svyynegr.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2havkqvpv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfvwkla.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwqfma.html


<!-- 参考信息 -->