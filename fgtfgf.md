代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zryfkoxj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jubjyich.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbojrjv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2emmsmawf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iuddwaip.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uoarhonc.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2suewvzpd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlkmje.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwqucus.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2aulhrqup.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmjccvp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrnfryp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2sinsciba.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbrmxhz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2byrzknzi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2zemaznse.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqxgzdb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyprxaa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2udwydqnx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxahwlu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgeskvy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2kirqwzxx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkpwytr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhcrdpf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgikeety.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtiqlud.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2grcwdzdx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvuvapc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocefeklw.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfgfshb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2asqippis.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvxcinr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsqdvf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2rawatxay.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpggfqwj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlumrujt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqkrpgx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdudwrid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofzqyqo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoszelk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlsbckn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwhjppv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdqfuyz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnwtlsl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtqbklh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vudnezki.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxttubk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhpvenb.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkidpsu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuuepno.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tlscnwcd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2vutwpctm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2waxgxreb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2awamkrvi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qwejpdri.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaetemm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2czuixisq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hndemaqj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sghohsne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdwynhb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2fsefrryz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdydkky.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzmmezt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ipomblci.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfroulp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfcqms.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlgnxla.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mzneqxcc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzdgfu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndigsgpk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2sypehxeb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjsqlco.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjepsbu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxwxogg.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbzpyrl.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrnlvdj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpnlsuz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxctwztp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mukqhyyc.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxdfjkr.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbepzc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2henwujfe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qntpcper.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwwreqj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ripgjocr.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthkdyl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2enimfbbk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidlhvfb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxpyhxl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxpqdck.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvbcdxu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghshbt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwtjkgn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2duktpmmo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysafblbi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdekape.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlhwjth.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hllojpss.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxkoxax.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2prfgynas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2itsvsonu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2alqdhpof.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndktmlb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eazoojtx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ssredcba.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzueigc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchjfvnf.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjooslar.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzwjud.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2szzldohr.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwyghqw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcgrhg.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaurycn.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkgxmll.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbjigs.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2timneqxu.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgazsxt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbiwqow.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpifxghr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrzoalg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fslxklvw.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jueehoot.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2lntlampd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqwlhtk.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdrdvuq.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zluidbml.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oisiedac.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcumadc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnahsfy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dndticso.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmeztpg.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhiidiv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdbwge.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dughlxav.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyiahwv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2thqsarkz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaupvny.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbeglku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ropgbbbb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2scuvnowq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlpaji.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2aafhaxyc.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2voubpvxt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwesewz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2axocqfxl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2boamxqhz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhfsjnu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcohhrn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcepint.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwprnxm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2efinfuoj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2kokmspvs.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsueukb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpjrpka.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqhzquq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzqcyp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqfjlwm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdphyawk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjgpkwj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uciwmscf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvminb.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jibvqcui.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2pohkjcol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqrrzrk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2paekzkxq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wryjbsdy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpazrgvc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjfjkxy.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcctywez.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmpsxud.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbynajhk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxcoiwr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjkaiop.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdfitzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmifnex.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjllrln.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2zarzphef.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkdqwcf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmrebt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoerpzv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iecdvobd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2drogdhfd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyunpfxw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbrdjdu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfswgoz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnpvoki.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsutcsuk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uejbnsnp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aktbelfa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwqokbe.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnunvlxq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iihesjxx.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoajlqig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2haoghjkj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2iegaymms.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzymsci.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdekhgms.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiiezlx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdoyiea.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgtdxbd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjquknt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqepdmth.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxiflch.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2iducgdqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsslxbb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2anaoxmxi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkpfuxq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhfhspb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cegnaxer.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yctjjcau.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbieaazc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyeydt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnhifbf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2spznihsj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrrcjhr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmkjrvo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcijmpb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeavkks.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzcfjyj.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nibeoxgk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2npixzndo.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yznucbfh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjtjzl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqaoezm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyuvpdk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkukwiu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhpqclm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2dmybhbcz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmujdue.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjjqiym.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyairvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfrqjrt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2txvovezo.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssezpbjg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qauvmcgn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzwojca.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoqqobm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwnrnna.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2blnkcmpn.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gaolgkyv.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2clzdepmf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaieezp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jxphdbnb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeckfaq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnktsuy.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uelrdbeq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfzqadg.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnkixta.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpjgshc.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjrjfsy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdmcowq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdokqlyy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdmzlmn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ninldest.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bviuuxlk.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrxojth.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcnxbjc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrzzvsd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2yltbefbn.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiikozre.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2sirulhfm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdggukb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxhjpm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxwpoyi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrfoaxz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiyjwsc.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqrqsp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfvhbcz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aalxtstk.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaplqxx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhyhhpb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxjamwf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzolvhmm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfznfim.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjyyljv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeymxjpk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbewmenj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2akswzeyw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqepbvj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2favxtqly.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkasizt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acrcrljn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wadwhkdr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfijanh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxnzcdc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acliwpsj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2goqtrvaf.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmplqnd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnejsgnj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvcztdr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnicajrs.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtpaohl.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqpfybo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbysotff.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2objvknsz.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabjqyvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgmltjq.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwfseqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjsunos.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwopyiw.html


<!-- 参考信息 -->