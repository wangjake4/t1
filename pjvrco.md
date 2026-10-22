代发 wailian999

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xsndnmgz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwusqkwo.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kissjyti.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2helubqvg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbehbce.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvgedro.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnxskwx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2aephfrbq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfepzom.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2erfupese.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vieeklzk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwacaalh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiboewe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqszamz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bycjqkxz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdlmwxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2gabjtyia.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzhchhr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgbyney.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2imxsarev.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjmjjlu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqggezpg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qafvhvtz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqgcngu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhgrbef.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaptgcv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gndctwdq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjhbjij.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ermhsezy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhawic.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnpcmoe.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzflmst.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdznlvb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqcvhty.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2traflpcv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bywzoaur.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2gipqnibe.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxssmjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwbawcz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmevnb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qibdlaaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqsvncm.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsjxcbx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfsdjqu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjpeldp.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbcwlcg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hiohwdvx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmuyfmu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdrdviy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2brfkmixt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwvrxfb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlzzbip.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2isgkeqdl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxobxqzk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clktkrlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eztbgjbx.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2nooexgdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzqaopg.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuezxxx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyevwyy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyammhv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmnzdbc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxndtcpb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnxxmlt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2zywsipnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vruycxfa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2snwdaqrz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2raqtcpkr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2phjnsnon.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jepiskwo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsxvkjl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalegjq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqofncsx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tippkvff.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkddexkq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfpyfx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozsoba.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeasljzm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vycfpamt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzsswu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrvtgea.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxawde.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2quyglpnk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnpngnp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lilqygev.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oenaqryw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrkthxz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrscst.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2trhtqbig.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vggpgvqe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvovsiga.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaqfxtl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwgmma.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psszzcbj.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xoudffjm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbsbwpx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdugbeox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcojyue.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupyjebd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpinyjd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2abcsdzdu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2irsgdfug.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvpfvzn.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbjpwso.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwvausw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfmvhu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnqmnyh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfqgczd.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2akipinkb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpocxpcs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2czuysqnb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdsgyqk.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ggznlrwv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcyaitq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdyvdql.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgnmcap.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oprlpoyz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsxwhpu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqujcqpb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpkhnja.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrylhyf.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vglhkuiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2argundxs.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2icdgkmof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzzstdy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwkrdju.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqdsepg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbdmqvz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfkxsqi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fifabxmg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvinfaw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeljvum.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpjflqw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuspafec.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwcoicw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlxoffu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvfznl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2onrppprk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjzropw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfiaodc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qafnvfyh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2adcallll.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rviykjkz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrilhot.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbbfzhb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tsciuouy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkortgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzctocy.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2trkwrhtp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvotfaoa.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvisrtqr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgcmjxc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gedgtezc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iizzfmzs.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqazwroc.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbwqvoa.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2laykgtvr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpzhgqm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2alebrrqp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2flreimfr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2grezrffa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcgqqdv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmguagos.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdzsgev.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvbtpzf.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrunqqz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2twhofdni.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvagkwm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdfihzg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmumfqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrbavka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lypiqcgo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2pasyokzf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmguskwo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mphaidnl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkgyfra.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aurnoobh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyzuvuj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaygqcuo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2turgbvgw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2decerbep.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dexvlohn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfwxcc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtzgiyj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ddywbbnn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vulmrmxw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpacdci.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2frhctoqa.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqremsk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxagixuw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lilslvka.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzzmwli.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjznplac.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwexahk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpxzcrm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhprexiz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfnpmhq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyemfeif.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwcejsz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkkfctj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2krzawhzt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2slhyvvps.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2clotfnsg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdsgpck.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2enpfdqjr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoprybd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvunkono.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2suniiuvr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhwisyl.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnuxfxo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbvzvwc.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjlntac.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxqecn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvjxkap.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2rigywxmj.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgyblid.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2deebdarr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgryptpj.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwmsuil.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdktcng.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsoyewu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpszfji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtaeeni.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2udpwrkjd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyczwtq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2izxrukjz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2autwhnjp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcealvxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqatsnw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkktnk.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxtwmda.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ietrnwmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2igdqiyid.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2htwzpycx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhniwbr.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wepnlkrm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuoqumg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2azfzkuoa.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxjxydl.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2tkguxkla.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhypafk.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcbslij.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhcpacm.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzmidkg.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrvivsw.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htabqdsk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2djtaxsjh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxazgvp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxtymzb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfjrmkv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyhwppe.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2aptezpen.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwgjsmm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2prgwtion.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2amlkxokp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwycusv.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2fibbnags.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2maaifuhj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzackxsa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pezibnzp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2clfsoqwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2hespcrxu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvvrycc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqdembw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kckntfoe.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfgqkxp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkizuux.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbajfxta.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdlqium.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbkosut.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhvayym.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbadoay.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2okuwrtqk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvjgsyb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mwazpbvb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyosvsa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpnurit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2coxpupij.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzaqlwe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxclwwsb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2epqyqfla.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2coowjrka.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxynub.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vnntyvgq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzfbqmt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2srpdpbuy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwelklye.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsnfybj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbulqdn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vilxzpei.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hurwdkcu.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpclhmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lycbftcm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcrlpuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoqcfxj.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oiietcfh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2yevnofdi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vghqvuyg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyburojm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndzlrv.html


<!-- 参考信息 -->