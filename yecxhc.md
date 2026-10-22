代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmgvnth.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dndyjbbw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2offhynmq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bctlgcoh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnwgllv.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoqtpji.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2rgplgtxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsnnvfv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjnaoae.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqttpks.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpmhpvm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxnjafg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2amefohtl.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcssgct.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvwsafi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcbwymv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiwegmi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlessut.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tiikbiby.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2baavvyiz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2spmmsuij.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtqqdxz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhggrtt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2yugkkmmt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwktjldz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntnurhu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtifwln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfwoiuz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpefiym.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2iubkwric.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sljmrcdv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexwiud.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkltdnur.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2atquswxu.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjsfkhr.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iumkieqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akdafhbb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tymgrpag.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpadvwf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfidavc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2loariwxh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2detejurf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsahtcb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2iymutkth.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjndvz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2navtwojf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ozccyqih.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fusqdtbo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfdfick.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkeowhi.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2isfckhmh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjlibhn.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2texjxowg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2brjcwgfb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgfnkyi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqibdrvs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2daathnhd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvofrbl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jptpbazj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrongys.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwcbgge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqxuuur.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xouelcwx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgapbrb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfhfxxa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqgtltx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2geowscaf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmrkmv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvowmpck.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhagcyaq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiuqlyc.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlldmqx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2losicdbs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdvnrty.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysagsmf.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwmbxqa.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyeeatx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzimcvdb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxmvfkv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyounzu.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiswhqv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejwtwxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cffceuic.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2sppljqkn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpshtfv.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eriyiars.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xenecjph.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfthnypw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpohehv.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcximqfz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oclvdtxt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lijobkxy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwpcpaf.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hezxcdix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnwugws.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsjblib.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeynaoql.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcupekgd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwozxsd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdetyyf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaqmkti.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpxcvrd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoxxlrh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vncejapm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ucilnuke.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgwclvi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcqetcl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qeytfflk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2icwhiypg.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2efykhtxp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2egzqgwwh.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvcmuqa.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2vznfmtsb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtpfupa.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2paaymtsd.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2okihpzsj.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jlklbmrc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwxixbo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqfkulj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjcmrpw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsevrdmi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwxxlto.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwfenhv.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cduyljum.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmojnk.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbruqjg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmctaldi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlccyzb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxphdbq.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfafulp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2edtsnrhr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2byyhcrrg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrbbpmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzcgjsg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvftdry.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcaucqe.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxhumqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrvaiaj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2advmjrfz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtcsgll.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjomxchr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2djmiskde.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yulygyyw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkddilbw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zraoogsx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrxpcit.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlrcxiy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuycjid.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xppljupp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfjlsrw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sftkxjqa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnvaink.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaadzcl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqsbsrv.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvgtxtu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcwcfvo.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzearkup.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxhuyxi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxviqxk.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2grwsaupm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2llqkzcoy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2giajdzwn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2caqirrpg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpcsnod.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkmdfpz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhctbys.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nadprepu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktmgroz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxydgolc.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuzuolr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlauaqz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzhbigs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknzdfic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tetsqltm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdivamqa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gntzgmnj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhtnjzi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieocufkh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwfovxr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsvnqbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zccrrbft.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcgyfry.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckxbckg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkrcbri.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaoxsno.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtmypg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wswoqkke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaldonp.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dlooguru.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkesvbnk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmijkp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2woehtllo.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwsgupc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlibrhd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ldggimov.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2uvysoqnn.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dloefgxm.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2rquwyzek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gknfnamx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnzjlfa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhtnbeb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdjudbi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzslatkb.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhalsah.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnfojul.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2naiiykhy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gdasumol.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftuczum.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkiided.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzdqufv.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofiwilo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xninggdk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2regwkkxa.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszwiqy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2teicpbyg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdiuuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtgliqs.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvtfvdr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2eitvtnna.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjepidg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iplfbqwy.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfzjgtd.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2bawnvyih.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwpmghj.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwtalff.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqymqnvy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvxabuw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbyffnp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iubkskij.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgpumzs.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2zbygwdlg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcnrtik.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rexxghgk.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaamhwrx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrnmrnt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvthvxk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvkxgmz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2euumumqb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvpeywy.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2frbpgmvc.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiorpjo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhqcyaj.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpqyzmz.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmcgmm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbpsaon.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiohdayq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgksdti.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjhyav.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2baeywisy.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjnozwf.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetkgpte.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyromrt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxshzqo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uplaefpr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fitnzzcy.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrfufoj.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekitllzu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkgcwnt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyuwmvp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjnnpuu.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhawcgb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwdciy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2noazizpq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqsnfud.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2emkicrvu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yukvicdq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhhvdbz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkejodt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqwtltm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zccueshc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wboiorui.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunmmdra.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaitpikr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsmgbho.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmkxvbs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2piheopod.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyhgpof.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjllqh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlerkhu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbqxbp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxejjhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hngpxqjy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2guqtretm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvezzkg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2rctojxou.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2siclzkgy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azulxmtg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoqexkf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdczpuhj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aibcsxzg.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2adqfhaft.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyteauzn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqatgqtp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjaaud.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxauoxf.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2alnwipow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2megqcxwn.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kemjndxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rccbisgf.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxtbwg.html


<!-- 参考信息 -->