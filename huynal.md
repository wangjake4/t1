代发 wailian999

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2slhwqbjh.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2txlvookq.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2huuvhkfg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwpvgze.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwespcw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqzzgu.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2umpmunns.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2xafgjtkc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqsppif.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyozbvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2infacnze.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyysbypx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqylzns.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2qahwbqwi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2opqrpbcc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2bzozkxwr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yppsnxwm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2cilbkdqw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2koeryhod.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhsaoip.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tigynuxl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tflqdkek.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzxlasr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlcntff.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mftfcbms.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2irtqaepk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2apfmynce.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiebbefz.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuovcua.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mvimcevf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nknulxyh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rihlbhwe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuyepgj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrntqcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtffyxe.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kemeofwt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdlrtc.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqkpofs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xoflyfcj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wizhcvgm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdkwdlm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feohgkyl.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aubgsfqc.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvhqtti.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2miasfxhj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2clvxamto.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaaxkaj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2sprzmxdc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdcnoey.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jdimaoyt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnjhewe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qddgwreq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcexqvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybusgf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqipbgrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydecimfo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hikguuwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmuvmpw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqpanbu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2aerrdcie.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kegfecnq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tukmnddu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fludmdcy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuvokvs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxybyd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvgktxs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2blhvcdyr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxldkl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwvyxtq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aysgbvpi.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfwclny.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kltetpvg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmjitva.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegpwmkg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvgaiwl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqmubyq.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zctudjfd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbahsjk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhthhsfo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sculfifd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwridbi.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwtgiih.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvvtfwf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2siapqnkq.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxodomm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhgufjd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uosdousb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkntpzzm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2htlugibk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2srlortzw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqympdn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2soiadhfs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzfmily.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvdxrnu.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqolxmio.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfrnux.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmgaymr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehjcstt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrflkhes.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhsfnlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqiuxfg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnuxdox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzpqkua.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsjrtzh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqjpajn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzhywte.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwxppgy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrosdnqf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2cazeqmma.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aukmbhky.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqolhvm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2colbewmh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtbcwfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiviumz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxneuibi.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnszqwn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdibgpy.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyugczkp.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlzyddk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwmlntl.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfqycox.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aquokkyt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2infgeiwh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaufsio.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmdwyiu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2inqeyqyr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgkojmc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingdhuyi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdexniu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvnvflc.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jralgwac.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkonqpha.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxqkuag.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2uoopawjq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2eynkawem.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjtawre.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxvdjk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hvddkviq.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgmuudn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbljuwus.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2divbklnh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhzrjpc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuixefmz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbokqiiy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qztobtyc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlmcwmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kojehwqv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2otumbvrf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iasmkblw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhaemyo.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2acvmwops.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2opyzikqd.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbczcto.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnygmvw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpfgdir.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kmadyphv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2phihxqcs.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vejxpatm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxkwpt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qezugggd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulfreld.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsrebme.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytcokb.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhodehh.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxulayp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuwqotb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqfzysv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdwxrle.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pckoehut.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2griiwptv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2snytjjmd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpmibpd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmpidvn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudhcgwz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhdltuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wchzpogj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeqxpyk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2syfddyap.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqhgxhq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhagixc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2czikalfb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iwttnhof.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nveycoch.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqcnxvx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsbmtkx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2apvckitd.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2orcxkccq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtplwxh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhvmkoy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2twthniep.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2sigpcynu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwqbehe.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fourtujr.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2apgxomvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlqrwih.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iytawmpr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbmhuaz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojvfehp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsujhmjt.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ncioppbb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsrnohe.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbuhdht.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jioiszww.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnnkfxk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnslzvk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeohmsnu.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwpslvq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2sacogqvb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnjtqlo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2minmoiup.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2copqocfu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjtfrka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2skhvphzx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnkrjve.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtryiqt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2czshtayt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssivfnxu.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2etqlsngx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkvktdl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkzkiwl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtpkfas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sobzhijr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2irssgfwu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2emcrujvt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhodqhmm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpioyemp.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrtntsq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubybleoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2aajhcaib.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2heucxjfv.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fksdwarn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuskrfol.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dvesyobv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoumpeb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvliglp.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2alsvjaua.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnhoeut.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2umwccosr.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2blmopjqw.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbqilea.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2htxnexyc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwwuhhx.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jniyetnp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfucfrt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlpgjav.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbfhgyb.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnezqwep.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvotgkye.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsrgrer.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2okuidcde.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azydrvdv.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcwvbrv.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwajorjg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkptmuxp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2xojaqtww.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2phoomogh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwbppoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpapfnoo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaarpay.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2klozrpdm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozxdhmd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpwdkze.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zscjkbzb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwfxjeq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwnkeqm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzthmbn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdggsxjo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskvdccp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxibyd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fluhmhcz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdzsvkp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2boguoxzw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ambvvtmd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfbqomv.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmmpseb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqftjas.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2moowpisu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsvscf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyitexdq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnogbhb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyemnfqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2augjkrsp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfzwxhj.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkokgsj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoqjiip.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqiijks.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtpocab.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcvaytg.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbrijse.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2acojeoou.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqluluho.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmrbsro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzttexlz.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvxldsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeajuxsa.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskssni.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2alyqninl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2avplwmmc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxabfom.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2odugpjqh.html


<!-- 参考信息 -->