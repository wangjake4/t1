代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sotrwcki.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2szhosthl.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqjrkzy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoxpngb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjmzxsm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmrhybm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2oppdjujm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2prypprxg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2omkkbycf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfvrnms.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpohcbi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2nphrfnfk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuapxea.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkulaae.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiatfcwv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxfjsvo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzavmnf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxgpabq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqetjrka.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skxjqgcs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrfnxki.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2chkuliyg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsravom.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2isrenhwj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtpdfnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqmtxzk.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zarhoesj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoqyyzz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cexriljm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlkorfh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rywpusfs.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhbblrs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2uabbqhvx.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqewxqi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxujxar.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmfgpeo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2figpbpwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekudfztj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mssjnrpg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2azvwtisf.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpcsvmb.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzksisg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hxctuwhx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjkwovh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2emmgpfll.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwgbwoj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oferbxhx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhcyzc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2czdgedot.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgzwaf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oakcxued.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awjiwvph.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ewquvhxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2secmjjnr.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2llryntfw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ieusrapt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxslsnb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aaedrqkw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwadjaf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkizggf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuydddx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhngxvj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2anmkfvml.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yshegmll.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmabqdt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2njdiugau.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsiwzcd.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2raphopja.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jywhtjnp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2perfrroo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoikukb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgjhtwf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjjihmi.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmujoiws.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njfytnhd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcvjvkz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgrcmk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyjudlk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdkpofh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzhlibp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stvtifdk.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzlsejw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfzuum.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnkfzxv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2syncaatd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgyecsj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hokfhvzk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzdxdbw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdoobn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwojlnq.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyywzuj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqsrxgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pemmurom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mncwvpec.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgtddvn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkpfyyt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vugxuwhk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaxuenj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2znrgatmz.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiesqre.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuptlsj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrdovgu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uylyjclc.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yplqqfbz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwaybdw.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twzlpokw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbozkar.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmzqclx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaxnhla.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2chppjxkj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jicqiksf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2juqpdofq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoxzjja.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvphmfiq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzwinyf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlhxkwk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhqvzo.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaenegw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dosztzgh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwmsumy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphsawkc.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzgyubk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmbanlx.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvghctmk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhaglqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpiujnn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvdbqqd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhxkrkb.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erdjduua.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2lubzdabe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2exgegnyq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyceplfd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnrmema.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgnudxg.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpozjdvq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuegneb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uildgaqx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2soabuiyi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhonqwl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxapxwvp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnswhb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhwpzdy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2geivexsc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwqzhfz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wehpklvt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdnibcn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlennqo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2jizsnklv.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oosuviel.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsquqzi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2seaarbwv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqyyxll.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhyeyzb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2uyojqeik.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnemdiu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pepxbhbr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklicxc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahzmjx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2okgvsvvh.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthihytt.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqiqsma.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoitppp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2biaicbse.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwfzdob.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnoqzlh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2onlzmnip.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiizqhn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsweuoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xqapopaf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkwldks.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmntvheh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2pucuvzgy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwwnced.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2spaoksiv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxusex.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2splsybox.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdgvsl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyioypp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzmahao.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kejyzksq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppccskgm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjowcywz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2syyckuwu.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjaafak.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2klkwlzxy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtbmiol.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iiosttsp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2xktgzstg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kotmcypa.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjundkmy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgkgzyx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrinbfx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nudemnnt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyqwlfu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfjersd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdowdnr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiarmhm.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfhjsxj.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2szyinwpi.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhdmixt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ersedkvu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gghdbwdr.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsjskaa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mojiiszi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdmakjd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2pthfsyvo.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwerkza.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcamqtx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qriepkxt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsrwev.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tovotbgy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhloskkc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzwmgxr.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxltmkvp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2jumzapuh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylikhjvo.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qzytpwpb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtwdyhp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnzhhes.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2driervij.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwdwsms.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2diwnyitm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2bvafkddj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqlzkrg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfisauh.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2rablbfxl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eldevegk.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmqjwau.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2scylsrpq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lxylzraa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2hoicpgtt.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwzuaow.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsamtuh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2syqettsg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2conwtiiy.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2qrifduwp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmgwna.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeasqqx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axyeufrk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2inkpstnx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqaract.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuegmvhb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpbpyco.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdapqmde.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtgnkan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dudzwdlp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefjfaqh.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmknhago.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2laxodabb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yopkitge.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmmcjxm.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vidkmnbm.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2znreusnm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgfzjah.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmumsh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dynemecr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkuxvpj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2efgkfact.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbieifq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgwzjwa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2danhzpyi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhcpkbh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcqgoz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrtwspo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pudidiem.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxornhu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aquqhkgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyewugxp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2igjlpyse.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqmwxzy.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jkylfdrc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2eofbgfnn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2efljlmsc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohjiugk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnwknwj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cipwzuxs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2otttgnpv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcxylaz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vefdcfde.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lcepqvpx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hoktmtvv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cldqkfnx.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxrhxlz.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaeehrh.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2myjdhjts.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbfwtcm.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2csxeplmv.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnetnopr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soqhkwmu.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsnayfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpyqfhc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rigffylr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqlqubb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kujfuzyy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwukzywq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyzvjzr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owwplkrd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjbltai.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrkvpst.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdfypwx.html


<!-- 参考信息 -->