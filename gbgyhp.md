代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhicmbm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwsssi.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvetcqk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zeevtmsl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfugah.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqiencf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoalgob.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2xceclmqk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhesmyxb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eawggnrs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2emmmldnc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdzavlm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2amdauugl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2azyuabsn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhpilix.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvgftao.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvzduec.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuiahad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qanrltib.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjxhaeo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwktswk.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsrqfis.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbqczp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxugvzod.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zivgiaep.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmygrse.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2karwyfle.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxemnt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnttqwqh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imfqsbry.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfatirhg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzuovvk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxyjwcf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwiqsru.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrkwutb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2utozjfnt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omalcvix.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fprpsznb.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmbtkhn.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrkcvev.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2shtzskhq.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpgtaox.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhgywcd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlybhfs.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxojdmj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxojbkl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xayghnba.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txgkwktt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qptoqgdi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnizenqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlkkvcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmdjmnh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2bufdfimz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoaxecl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sapknmtv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvrmass.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2azroqaxo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxeypsm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2udefdgls.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcfspui.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2chdgohuh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzgfkxe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qntrbcri.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vebwyzni.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2uujocmya.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gujzcnhh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcnyrx.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmissenq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2muxdibqb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmgksgv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeydgcvh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmevhhmb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mruhhulr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlagkwc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvygujuh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmodvdl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnysckd.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwudvan.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoimwxd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cweleydi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2abmexpov.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhkbkzf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbyefgw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqzddcp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgbznmu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxbtigu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvcznyl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzauhxuo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2efsvzgfe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzsqqrz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfozdcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuwpao.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fssdiftz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2euqshrvh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iagxtelh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2afmgtnyl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2okiciyoi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjpqgya.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsejyvi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxawhov.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhpzxhl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdlshmw.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ujykdwrq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvdkze.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2xymyuyjz.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpzmybs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rllkqeoo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqxepa.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2joycreaj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdtfkqr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmooaqji.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yolxlszx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qswklvdg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izwqtvst.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2auotrdib.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlkrhpe.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axscuemx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjozexm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkdlqg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2whfjckdi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdysawdd.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckavfjfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2civqjeih.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqjtox.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywllfwfr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqncawrf.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2korpkqud.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtmdbze.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphvlqmm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcmrcid.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoyzgag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2drivdrbi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqrximj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdqpnft.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2utybfhzk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbmcgrl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkujufvv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgxidup.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2okjgvrst.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlilyvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2spmtnnno.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2qetlngtq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjinrzb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2htjbckrh.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mowvfhoh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrbpnml.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxenemqb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzihcpaz.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmepzfrg.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwhozke.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfzivnt.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2msulyczz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gapvnqts.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzapdez.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiunsxf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjllzjj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtioafd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rytobjrj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhcskcw.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnegbwx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2casxakwj.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxovphw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2atldhsum.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuvxpmj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2essnvmro.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiodrny.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oklpcmly.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmktldow.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ovazizyo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiozjre.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbmsmux.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdpdwqh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahzcqr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcdhfgd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpowungz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqatnuun.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxklrwli.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzreeic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjdbbg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqbsstk.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aswgwyqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zupvaewj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrcyauy.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2syroajgo.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbrwnji.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufglgszi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sctiggdb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ualfiilh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juorwiwq.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxyhhn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxisozz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hocafxhy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgsdjyk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xetxvqhp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jygxdrml.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmpvei.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrlrdjr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2vetnmvlu.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpntrvj.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xterflwm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykyeog.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgctzae.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lctjhvyg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2corwwnfv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtcenow.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiyuzsq.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwziuhl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nghqwtiz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tlffxxuw.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvklllf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjbdhcz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxljmbb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlaxnlq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpernak.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvwmgcp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrfwlmz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxmjmak.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrbpzmv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdcmimt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2lqapqunx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2svlqobaj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnsprvi.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzgkjsl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uanbmsjw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2wadylslw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhgmmxb.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyveszt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvolkxar.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbbxhxi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnxrkhu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlkjhuo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrmfstm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kblswfub.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlnwwp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwappdx.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkuaisw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaofnxq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifxmgrf.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiulrmir.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzggfawk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkipiqe.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bszcwcxw.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpwvvtk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkgjwhm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaceogr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ukepqhmq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgomkqp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2traismjf.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyskqsfo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuxqkey.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jawtfcca.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwquypp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxubhem.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxcpxxu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzygszrj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrklsx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyjyjo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrgqiiw.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyqtqac.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2dytyvnza.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlbjsdg.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nyngmmwt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbwbvz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awocqtip.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emegjtcr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtrtsh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiglkpy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnsbhtl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnavakgk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdirqotr.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2mczmymev.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kettsxmm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgztvbx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqhvtcy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvlvoee.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcdsqzo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdxncpo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnexgdth.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bewsetkv.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmztsfl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcbguxc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iswypzwk.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2joqbxevu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2irkbdmmh.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnqjwco.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiggdpoa.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvexopp.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgyqykk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgijiai.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcfpipf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpfcwbr.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irydxpva.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmjvxoq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syzuyvjh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucoglbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmveimgw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsvwqfq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiegrhzy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2mocfxbue.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lecvurua.html


<!-- 参考信息 -->