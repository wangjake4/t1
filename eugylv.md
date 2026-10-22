代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsnrnft.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2floexjap.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvzznol.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkefrjhp.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kauuheha.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwveqhv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyliutx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gprbnjfd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zioeijbb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnjjjce.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sconrwgj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2lqypkhty.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqgcqvw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzhqghh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2qihhxdbd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvxoucc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsrjodd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyrlgdx.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2sekjzknt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkdfjlx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2awmxgpcl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2vntejtgz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2buugegny.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwrfccc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2orpqzuzu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsgzveq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdhvrsl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fayqhoep.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rktaihjc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcoydyx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjbfmjy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2guhdubqj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbekjny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyjyufl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeumfrri.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzpdtq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbaort.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkwihhd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyksyjae.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfnxcyv.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uchxfgaq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2imsctvmy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgegvvj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2uugmxyoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvmqixi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whkquoyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyenonce.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxibhviq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2osihixwa.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpevlpm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhyxmmb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzrnsvg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbmrhvv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmflrrja.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kubwuoqb.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdhmfkt.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzoren.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vojtjpdb.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtpjkpg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vscnnvef.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqthyrg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nlseqrah.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzwkcmo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfduhewu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2wywfjchl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrehywif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbwfhwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcmpidr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fodsachf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suvwuewp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqxfsdh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2edrsoikn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzgfixt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2crhhivcj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrxpdd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dtibmwlu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2omkyecsf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2txhpuyyl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtkzfud.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pdksjftu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxpeorp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nngitiop.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkffiauq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmgswun.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2habyqesu.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpejdoy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2loezuthu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpxfulx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhbtqnf.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwlmknq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdcqjln.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2alqanyjv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuatside.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2docrqbzh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2manjbonz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehipahm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2geboaotb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qnukgizs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmdgewy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlvvxvl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2icodlwug.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oduljafc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vefucpae.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvledwhp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2reajvjdn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfxitz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoxrnzt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtcmvux.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmigdddg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqusfqkl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qryebsdt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefgahf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvvgbrj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2czjkoqce.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwgbugt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zprrpscr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syoapebu.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexwiwqb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkifclz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2odszgzrx.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgnqyge.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchbsqin.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjgccph.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecymqehx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ualiosso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoojgim.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuugewf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbpvxrx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2voahrnux.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2leakmhew.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2orjzkblg.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2podkjboo.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2elthaoqv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuzgwzt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2meppdggx.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yavvdbcz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2emaohlwv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2phkyjkuj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wotovrvx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2amasqorj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yruijkic.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaschojs.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiakano.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2elerkxwm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2quczrgww.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tigwinxv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2esruxvkp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2buieejnc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyojhqcb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgbknuj.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofiobz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeeuwyu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtbntfz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dffhypbu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzjerpq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkzaxxl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ciezcokn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsivtcf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzclmoo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xepmeooi.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iindwuud.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjkuspw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2epujyuyu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2adxumczl.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2hghdlfhu.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtboufku.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxjjgv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tucdrlpl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qixjgoay.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrqxxvx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhebxlg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipwyraj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoszkej.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmlfpoq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwiqtrk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhcyfdh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbjbtjs.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uelvnatz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjmiurt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2niqysigj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snutuctt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdanoysy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2idoprgkl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjemdum.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2lgprakhz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwgfipj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfatxpe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzonxbhw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbmpzel.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2koqxyftq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2blcbuglo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjangisu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eshycxjt.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rijuwdpt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahhjyzp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzclcovv.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpnbzya.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrgapae.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovsrolu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkrezkf.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnyqoyf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrlmjbn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwgkjui.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2onbqnwnz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrpbdwg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzimmpgg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qedlhrhe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsynimd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdxpoma.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyircwb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvhzsta.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbpxpxe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2umoveyhi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbmfjyt.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2auwprcei.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfnrrdq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2abtnxdde.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iseufeev.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvykolap.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdlnavv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwsfylf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2npqrrkgx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxaxuxb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfwizyp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qensoejh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlwbdzv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhfydmc.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnnicbq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqvpbcc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnmsral.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvoltrm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jseaimji.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mctaoxxs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2licyvywd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkexyxhe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhobzec.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tythtrjg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwfbqdi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmoptmb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrnwrzj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2aiswtafx.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2eookogky.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstjbsxr.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhiomdy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjfcihl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hywcpbjz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdlmbgc.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlfxoz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2couydszb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2fncctnmf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fyktaptk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwmkfiu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgivsa.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyohcmi.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trplcacf.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhezeexn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvubtyk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bijbjlms.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoxubxc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqejwuh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeauuvbp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfqwmql.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphvubwz.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2necaydyk.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2slgxuaxh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aesxhcfp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aintnfcv.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkkgice.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhnkrin.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2taqjgzrr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zreyxcaz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhchte.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2waihbkdd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggziqpmy.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfouubct.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2njhjskww.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2domctttw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jroqnpwe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqymmgtt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbqjdui.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czvkselj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyhvifi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnkihis.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhkpvba.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmamaegg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2omwdtsgm.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhzyfur.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkhcgxy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2irzfaneu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwjmnlg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2moupczea.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoxkchu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfkkmim.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpljoqw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjygthic.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oekuvhdh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypumobee.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jabqnvid.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdckesd.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2migurhwr.html


<!-- 参考信息 -->