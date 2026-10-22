代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcjtkjd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xssbhnhp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2oeopwovh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvfakss.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fooicixx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomqlqj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blnhxxji.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvcxkcx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2eocynfvb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2oolnqvfz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2gwicrvnf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pvozgwzg.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgmritz.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvnvylm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vannzwdd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlgxzwm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kmabgxcx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoccath.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zskcjkif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2becvwwxr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhxkdpa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2oticmkcb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmmepfl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjkugm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2xasstqat.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2usltbgzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2avldmuwe.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxfpviw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzgnfdt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfqrbbu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2afpamzvv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fhelqseo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxokmig.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xihfkfys.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvznpqb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2oehgqyev.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngujdgbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehydqgkh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgiwrzn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkrzvzb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nheiwcba.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vvknlhyk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbulxaf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2imuqawiu.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbzmqdu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2beeenivy.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpfwegh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2moowucsy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqydlsg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjxdclf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyciilmf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2elrgxwko.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbbviyg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqtquin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlcebct.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yycxruqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmophugu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruryokcs.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2imweyrnh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxymsbq.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2snfrtoiu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmcyfnn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2eeccxvhq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgeeomm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gustkook.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2biyngdqh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2klevfenu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbwhrsf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rksljwnl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpagrjvd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnadtha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjtjmwc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2baklatxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsihfrf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqswsrb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ypddfipg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxrhjdt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sterttvm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmapsytq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxkmrxl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsjywia.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nihmrhjo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2snslkadw.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2layienag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2auttvuvc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hditrxun.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pehqxwxl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgcjujv.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsrpdqb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwulwcj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbhowng.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnfxlng.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkiwkcx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbbehcx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfcasse.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobpish.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oksdwsbi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxmuwcn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2djxvdpro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemcpzs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2upyfcirt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqvvirc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwiqbye.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwnonhn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2julcpwxa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwihlqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wihktxpe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxjopuk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjoswe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rttyslqs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qrahmiou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hanrusql.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgutpygf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbbqluo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2amlcnnap.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcybkcxr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcksvql.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkszyqm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yskrwmmn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxoddsz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hufjvjtr.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdouzamf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgxkkpn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vuufraom.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2srymzynw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvcrbzr.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdastjn.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2altwuwan.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qahskvdt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2krwsksjx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gglavfmg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpjzfvw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscxymk.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjpevtc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2acetbtbv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2szrbailg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2faukugnl.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkieegu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsngoawd.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2drtsfntc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxaajds.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrudvrw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhzkzan.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrmfolf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcrmclx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhmuzja.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkzybtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuysrsua.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyajdrhm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpjokho.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2slsvbafe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbfukrz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqspfqzm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oldgmwcy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2suknamze.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfqcyjn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlpzkre.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykozlnvx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmanwxj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnzxsxw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2hnttbfnp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzystgea.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkmggnk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2slealfju.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2giblqpvz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyfpsoc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbihhsii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2stdrbhuz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrbgrgd.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yublchft.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpozele.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvgvofb.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2belbuqto.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvuhzjj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlawwkn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwwxrai.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxttdyq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qplbqtbj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmojpvhh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxyotti.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrprffn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwypjxtc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pridzqnf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2druuuzdk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcujbdjc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkoaqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuozizf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyfzubc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2uuifqwdx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqywwd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trufzkpy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pahiaahm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpchkd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvicoktd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfbwone.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwllemnv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeqesiq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evksdhmn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvphxejc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sluhfynk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrxywcs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvzebhm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkpqygk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2crzywfsx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fawpkeoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwzkhvs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtirjab.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsovvxn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeltnct.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2khkxzigd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiycdplk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeuttoc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhukte.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fciskghj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2bscyofzw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxbdplh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnyvcfs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyoiohc.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeaxxcm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icflyxge.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbqaaz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yexprdvl.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwecuhk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcirrjea.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eakunexk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2pscsobas.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoveihd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2chgltwik.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2thvkgjib.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqbgfcy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeiuqbm.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2yifutrnp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2meylgijg.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2birajgct.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlkexwq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjesgon.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jutcqnwn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxoycsc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuawtow.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmwdbvp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtqnghu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2earsoxma.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeybinj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2peuixqrp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxgiwte.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqsbdxz.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htagclex.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvpbvhw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2flatqief.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfvqmod.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaczgjd.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kywpstcz.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vriygjrv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyybznv.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ockhgvho.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuvxoq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrriilm.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2maegcmxu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjdbpib.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcovxqd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyzgrai.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbfeoca.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epxurzhn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehagbgmr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeojumx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxdzyxw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkmejzt.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuqvpmq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iquxtmdw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjixfhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpkjgij.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2swtwbpzn.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qmedjptn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgkkawd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qedzhrjp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqmqnug.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2deshyzgw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2smogvhkp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dohhydzz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwehyuh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaibeit.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfhnrlp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnuadqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqysaxi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpescwaw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnvmzqy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwotlenk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqzwadn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2znsoddxh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2caztbrpl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaisetj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2hortksio.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vrudbdyw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxlmfjt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrltfuvj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifepelv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2awjoeplv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ereakpsn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabamnle.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvxlefr.html


<!-- 参考信息 -->