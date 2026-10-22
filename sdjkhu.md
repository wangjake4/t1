代发 wailian999

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2goysaxvb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qzegasvu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhqwnoj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpmpkge.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhnvmij.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2httrkecd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjdykjd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2yplwuaer.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bauayjgb.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyrwwgi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2uosaiqig.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbxtkle.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqupijkl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2yplnmvus.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiftlijx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgofkpc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdfquqq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxmdmog.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvitrrf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxafvhl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2saoxzelu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2isgmuqhv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcozzboy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hleosith.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2daspyymd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hggcmtbf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpacgrk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfzqzdp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zndtimdr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkgwgko.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmlogix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quuxqcxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgliamh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhwqitq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rknwzadz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xghyonmt.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwljzhd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2roynmnfe.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2neatcxke.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdrlaoj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrenxih.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamjwyg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2zydqtwgm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnpknvu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2kujnwnug.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kagwyjdy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdeupfv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeazfws.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxbrttj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzadwrsa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcifjev.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdrtlwu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2oqubmkui.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2uswgsbjx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfnvgot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2femnyjoj.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kgateris.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uauedfgx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfqqrvi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzejpwgr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2orqharxh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aewucmhk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcluoyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyacgbdd.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjdzwyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjlpvyp.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2halycirc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2dktfagbi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vapdewzb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmjotjr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2featfvzc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2nudgvjll.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmsrxed.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2oodbgptp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2trydwaev.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2viegaoka.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmdpiom.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoigryf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yttlkicy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhyffwe.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pozceyxz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iamurhbt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eamempft.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbsechx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqcituq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwynkva.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sswmgxuz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2eluzsgpy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zulbzbdi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspmbmwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoriggc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nchdkyjg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2arjlksrn.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irifbvwd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpxvmij.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddveyoay.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuavuew.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcjplua.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psmnnqut.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ditmvbuj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2efprkjjl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkdiudw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tuijviag.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2icrnsguu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2prvzusmc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulprgmfi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfaljug.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjyzjnu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxfyqvn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2olzfjnxs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2evgnyxqj.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mysyfupn.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjinyief.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qusfokag.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fcamwcii.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xryqilcs.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoqmupc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcamvpsu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kifjxfex.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzljbkak.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uesfyinu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaedxin.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjqtlcq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsblymvh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdjwjkr.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nscetnka.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvfrfzt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlivlnjn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwpwaj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfowtddx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sthphubz.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjdjplm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yffqlelt.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2manprufw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlifjvky.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oomfdout.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hckdzcxe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqoxyb.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bduzsiqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgydotc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnupzdzz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2huuokdes.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefjdomp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxahxqg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbhypxm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jvigdsld.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2npghcutw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkcugxz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vliqpdww.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxxhdgv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjiljxq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzqnrhs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpishis.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pweksmns.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmhfnuf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2taeknczn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdtmwzi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnzwbhw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xopqelhd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2epxfpxop.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuaidt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwcdueu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagydwei.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cycwamse.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaiznoe.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2utqkwlgt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2posybnmg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2riggwfil.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgudeapc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeqrzmv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxvplen.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqskygz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixpkdxv.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2clcdngwu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fchbbtra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnoiplx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjggkeq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmgefi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobjgmew.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaeebdu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2txeflnxk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjnkqyl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2flwzvpsx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tibmhdog.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmyszgb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2glpxzjcp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjcjftm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqlnye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkdqcyl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnocyoq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyylbyjq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cupbypbp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2icpqkhwt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xngixiqj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxazacx.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfvyypa.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2shrkmyjf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkxsqcy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2nlklqjfz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvyzhp.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkbvemb.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2brirwhft.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjncrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceykemtx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdaors.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yomlhcxu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhyorxx.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2xkryudvs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wskextns.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2igewhqct.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2smimefws.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csekdsle.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzumollr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okaqgppd.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qclsuzho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2agbjtjau.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbanbmzi.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlxewpp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwovsgsd.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpphgyn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ckihpgsb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwhplyf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlobizz.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfdzhap.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jldxgnur.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kugkmmyw.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkqjtsm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dscdfquj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqmfggw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbdwndg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwxrxlk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmuywgx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqcbewj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyyjtze.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjvbay.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckppqbkf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2avtckcar.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsyxgvl.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpvylbp.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvalssh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjfqpjq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dbygshnd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2njiaefjj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzivpro.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxyujac.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyqfchf.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdxzexo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hizzxaip.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2awbprsyw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqsjeqh.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsvlias.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqowvdrb.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xapaxhrz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcxunwy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhzcert.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhckhftt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdvubdh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mftqofau.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbrwutg.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpfmcqc.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqojjhbr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kidaqbai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvbulh.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjdlyvo.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qxygjubv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbatmzzo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwwryon.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwzkham.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrzsenx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyxvfih.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgemmlh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2dppiscal.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfprnzda.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edjmttbf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiezsjrx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uspfcarg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejuyvhk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtuzkvm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmipiwx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmgqmwk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2quairgoh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdeetlc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2hatqdqcq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmlcmfz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyeeidq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfoslsg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2afqjfqta.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjvherz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2jalgipuc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epkawrss.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awubuizs.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyliat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2twagoagp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchbkjif.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciydsgub.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2bygfoqrj.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtsanqi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2wresqorl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynugeich.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofmupno.html


<!-- 参考信息 -->