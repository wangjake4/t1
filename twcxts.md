代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhfwhpr.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qhljllsj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxwtdds.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpexfxz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cqivdlrq.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxugksn.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2dluqjpcs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2oougoicz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvtukja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbprtgep.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksorthm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcdmlwc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yslkbapx.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ithwaiaz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wewwesrs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfrpgwx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxthfybr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzwusnd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aolknmbf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvbptrp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsfddau.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2sioomigx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlkxscd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnsqitm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxkdqtq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlneqpn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgxmuok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znladpvv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzzfisi.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbhlkbq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2chcejnvx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygwdcok.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uauhlxjo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2favbsenv.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmccbglv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pteggiri.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxqljdh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekbcqys.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnsrwvy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fimuvxfe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcjkori.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dccmhnts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2smzfixli.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2huryzxib.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcurfjqm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnwwuxj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhwnljo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nltbmpxr.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2wahgkcjg.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfyfdkt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2aorqxogu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sbubwvnd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqubwvz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuxyuya.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2keuubzqa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqrcnbz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2esnsxdlx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oawgsymr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nszkiero.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygikeamg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qqidrteh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpcsfsn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofekolgb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoggpla.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mffqjsft.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskirft.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjwmpaf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgvvifl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgomweik.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuyuzwi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgtplq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsoehgf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2depahzsf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxicscr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoptyjf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdebkwj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shykkvdq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafvrjru.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyyinmt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmagmyh.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqozulwv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdjirxt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zacqolea.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjbohgc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptmizi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsjnhcj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrtzpvi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszojnqc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlerokh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jppiawax.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbbaec.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikxxzyi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrnguba.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqsdkfr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxyqkgw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2snklsyfv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzupvlv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvlabaz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2depqctvj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ontfvkia.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlwcuhq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jigvavsd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbglir.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zinsqhbm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkgnvsp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kgutnzvq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawjpujx.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tisvvlma.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjyhqz.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdshekk.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlxtyug.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2defxoqml.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2yafuphnf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltifoza.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlsuppj.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqnirjr.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgofmlfx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2edxqzdpj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmybeua.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmypzevs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhbvhkg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2niwxxljt.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpsuley.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecekzadc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoqieug.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2exflgruf.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiwwthl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzjrxkc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mectolsx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dueexyva.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyibrcrj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2euirmrvh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flaicvfy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkkglrx.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2gndqbfpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2isvzzhog.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aakjuydn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2izpwafmh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhadtnrx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaghzcwd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfgxepn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnqtzxs.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcrther.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwtqrlk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qchrrbhc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrydhfs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxundqv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgtswkn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwnqpuz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjtnafb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdyrebq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbchpvs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrkmrki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjymyjev.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtwubzq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwrbfwa.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsslhzfi.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsrfhxt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzrmjzq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoedigl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvsctco.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnvgccl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkyeil.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bumhybtl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2erpccsba.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oblrjieq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wszbcrad.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcaypcn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqotwmrw.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziurvufd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2paylfcqu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zudjowpe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfdhftv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pedmprhp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbtiujr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrmehzn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfdgqnz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfajimal.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwakenyp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaodttfz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yowbsntv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkemocu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyobspbo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2blixtkrs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdduoiv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utlbelwy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnxxne.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnowpao.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoxzfwb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbpgqpm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2enjmohmg.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmaacdn.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwwizty.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlapldg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwrylkj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtnctan.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiicpcua.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzubwlx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxdejm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2omltmoqg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpzcpdm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2usqziuyo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiyyxto.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2psmyyjhb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ducnmjzw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtkbid.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwgxvmw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2efolbaqa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxiwzph.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kapklahg.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxmayv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eggbzwka.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqnnahq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2utnhcjxi.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2eonarzse.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpomfld.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hdllutro.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeayzbm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvtavve.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2edkaveiu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwgwilw.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2summhrfr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2behiferr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tckbybrw.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jcshqylr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2juncfeuj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2uarvtgkt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2rbslyxvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgzqvkj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqomzdio.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zrciglci.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvsoxcv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgelvd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrnryo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeggxjo.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2haudcumg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnuxatd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ipabfhft.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvefzspw.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxcuxfk.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkfwcdk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2geporccr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmmdfro.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuwjski.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rblkwrei.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlsvbeu.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fledqmjk.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamstvqc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2egqtnwwy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrmkcpn.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklhrytf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbayaygv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyankgjy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdsfqkx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehmrqwn.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaowvrl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqnuoxx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuoemia.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjnhley.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwxcnox.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2agtxkqyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkqzpei.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skmtrvwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwwmyr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmmewwk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhirouwv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzowceu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfkrulz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2youyjpta.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrrstt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2elgsrgum.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhohdhid.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwwzevy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ethhclsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnapabjg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdibsml.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgplayb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2esjbunmd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2aemloogr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpvjgqs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2racgjppz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gytvufby.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntnglhw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvcxbgj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2toznomfx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtssrmv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oljeyvie.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfccdzbp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqonzya.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbtmzdi.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtnkbyy.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kubpplfc.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyszeck.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgrbvly.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rupumfoe.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidpjxha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwpkigm.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzviojr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyzmdii.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ektmuvhv.html


<!-- 参考信息 -->