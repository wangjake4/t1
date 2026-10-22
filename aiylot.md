代发 wailian999

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2evtmfxqv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxcgxvp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zgknwglh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpgxjck.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2blnnnfvk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2isfjzequ.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2mriljhhd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vggssgvi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmehxgqk.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgctwpb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2asryyhlr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbwdbdd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tllzmewr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2akdvwgip.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhxmaph.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qkazyfks.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnumbel.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokmans.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmayezu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2phehrgqy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgpomga.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxkljez.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2miwjnijq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wglpfkhc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihdpsq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeugybx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrndmwm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwgttp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuisqlfe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2wzohhulk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cucuwlqv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpzrgun.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvgqhnk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpccvxb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyzqihf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aecmdfet.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzdtjm.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjpkeeu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuxhfym.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrnhdjn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtmvrtt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyblsym.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sgellesk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyesvvh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvclsmc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglojscx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mohwporf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2euqfpwqw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjwakkw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2htttibik.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jfogbhng.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njfsfhme.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyszujy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnoiibj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stpdfabc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxsljkl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2tsibspcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jngortvl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcygnzm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2sodgxigi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrffuiun.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ophjcdqn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvgffmo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfkagtg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdrdfcl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2inormbtq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2junwxbpk.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkkecmz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtashce.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxqszl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwhqrqe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnyhbqh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2exqceglw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyxlmiu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfzabfm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmwyci.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkfdlyl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjscyu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjyeaea.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvrbihx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyskbprr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqukkxd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdyzcdh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjbmtiv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvonyom.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwtgjiv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrpfhjt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdsetsn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtfnmzm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vutpkkty.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uidjtdub.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwajpdkk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2znvlvltp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2utckgqcs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzcitzf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrhttro.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmydgshq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfnqgeu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2icthbwkm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvssyiyx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdolqam.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcoybnt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2bodzwfxc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdbjeu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxfecsh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2siwrwbvq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqfwlng.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqchowbs.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgsygmc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzahjly.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnajqqh.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimddahm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2khdikulk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcznbij.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qepltqxw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2joktfdok.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsavcjux.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhlfbtc.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugclyjme.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rauwrnbe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hidsaxna.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jofyygbf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkejvin.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2otrkxyka.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyaaylq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2srbvulcp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibscocsq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2croqtgxs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumlytdw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydozfyzu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmgnbzy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2maufavfi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpomriw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqnctei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwsbnqh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkzigce.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfiazxa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2onwbsedt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhneomd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkjhsqh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrxjsaj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowalerm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhwqbsu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvztshv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkboyyc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tcznrwqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrcngxw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2effxozle.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyayjfp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwruhebv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhbpugw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdowfhyf.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjypvtet.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnguyzdw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlvavk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2njfyheoy.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2yehfyijw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2cysztscf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrwxnkb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpryhby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxahijht.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiqfuiy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2qszhjvbi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqzjlzr.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpvseud.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vscjauih.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2aevbmtih.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sobkatxg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcnhxvk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2znakzpjm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bccnottu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2shzzybmm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2utgxpdgk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdghthz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkoofgj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2vltkwxad.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2worvzqmz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbsidpi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzssslk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlwzmfh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjrsemd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdbnlvq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlwkukz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqwtuqj.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqonrmo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xslfypam.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2diyevegm.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqitgaj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljauphds.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2deoeeebq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2gfshvslz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ereoyyou.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzjctes.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkwjrqe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pphxqnyl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdlamli.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmtgbsd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfayuoir.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2txirmhqw.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwmvhul.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlpxgyq.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwtlen.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcbypdz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgtveon.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzmiets.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkctwooi.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wufptbyb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzuuzvz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rheciawb.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnemvbx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjmiqik.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nzshnruh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nothvhyo.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdrqmzu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nptefdgi.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbijvbhz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuiikad.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeewoax.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuiooft.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mekxshwd.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeeljyp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvyafwz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpmbaqm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2eptdgupy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbjbpux.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2asmiqdlq.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrdcnsl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmjlaqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfplhfm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbfczdf.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fymjahcx.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmntujc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iwukhgot.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvhfwyq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgforirg.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fijidvoc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2yolqdokl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmyctnd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2txuzctym.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zknndelm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2luqrtufo.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckktdypy.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnbmtys.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prltokrc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevsjdh.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeucfeeh.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxtcciu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2frueunaw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmjusal.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmpwejq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcazsahq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2slzgdcgh.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2veanosfq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sydixqjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2llcznkvf.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdmwnzt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvlqqfj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfskasax.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewsazaa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjctaxxn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2osfuoawq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlluzhq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnfwovx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmarxju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrowet.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqcllxs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzpymau.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlovlhj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeplqwf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvblhysc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbprvrc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqibbunu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2oetzyhmv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2uughuwdg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2bizxyebm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpssihtt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qvphvfuz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iktrtxcq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsadiii.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnblakh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrspnph.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zegxslhy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psenfuzq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2buudmfew.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mojxkrbm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdmfhim.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdukbrvm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlceozlq.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtyuguc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqapgbuc.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2drirhoin.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkkhidf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcrtzdd.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iumvxdwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsafgnyy.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcthtto.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2lorbivla.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtonhuk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2himptlnx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rusulyog.html


<!-- 参考信息 -->