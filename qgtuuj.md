代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpncvql.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hjesptxk.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbwbtdn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgmijoe.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfaxxpf.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2unkjcwzp.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kudxflnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2uedjoacf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwpklbm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkybdemf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoyppoo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjcxtef.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2laamnvyi.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtawwju.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrwkrqp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbssrzmz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmbmsbi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2einwvvgg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdjqaqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2yudkidxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2oplqetqj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2umkdkbfc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfpfkaq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvgptha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yibxozsj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbzcnnu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwmywhj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cttxhxka.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lozdczap.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2letckkzr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsouugv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvjozc.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpcnkwf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2elknrwsm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2keueubwv.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjikfnr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cofnyrob.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzwhqyx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqontbtt.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2puvyyalf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjfgffr.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aazshqts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfanxcs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2alfdypje.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chdmcvdj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opfwuyvi.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vvecfaop.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdutvybg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vspteqck.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2unirolpo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzdreo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2znorogyl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtchehb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qdozzbmf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2snmhptyy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaxiuws.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeoregc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wefavene.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhcskxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aypacbqt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2behfdjks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkliamut.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kibebgfa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnioejj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkkgihz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hallwwyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvubgxx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjovnnv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gremwobe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjnbclu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2xedhxhtm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2noiuayxs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncmfut.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaccrrib.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qltwahco.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqhegih.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyahaaj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpimpllx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsdmgyt.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmjizst.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2glvtcpzk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzphadj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvexdnod.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2aropnoot.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imtcldxq.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicyoajm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmddfpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajbopev.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2szavvjuf.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2acyfrmqu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2foechwtk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehglmiey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2nepnqpsr.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owtgmfzd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzunms.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjljjf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucyobso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsvhxmw.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zxshxuys.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kvujdsyz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2grmbokvb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmwtfxp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cckksbrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2sirdewcm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zsonjnbr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2repuuczz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2yljpzsbs.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2idddtcuc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkotggdb.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqzrono.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjyijhb.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2onpzlbes.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2agjwdmod.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwogzbrg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hoysweka.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehktlwfg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdehpte.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2mazuqmnx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apvvymkn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbkjukk.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmezknn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2winhewkj.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2aeraojnl.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrysolw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsybyesv.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2shfxvlcv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjyegla.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2npdeigvc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2suofhpbo.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvczyvzy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2heedfbzh.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozulyvyd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrciosr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjpmqnw.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kymcmzmw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcozywol.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhebixxg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmixhkj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuihzmf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2kknbzbms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzqedol.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mucohjjy.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2igzvtykf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvuwqj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcevfsvd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohngypst.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2nreovbow.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdbqujb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdmxqxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrawewi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkngjcb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dekeuhme.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fenuryhc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiersngw.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vorhnjby.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2noguamhy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbejhevk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2abydtkpk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsvdvmx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrfgnoz.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvqutel.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpoijqo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrjhkip.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cejcplzh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkukmqvs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronzllwx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkthtjc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srktokxj.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvilabq.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrmppud.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuebamla.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnisxlzl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbevcip.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxkkgj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpraglba.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtvdeir.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmprtwr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtfjobx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvbopql.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbmwmpw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsznsxx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcvxfbh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzxlnrx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaehgeq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2acxlciip.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyhplwh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dekzwuwf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvscqbbe.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ionjrvpe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtbtuad.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjlmxyn.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhduilk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrwikkp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvninrjq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsojruu.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqqwgrh.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndysskvy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2aetbapkh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcdlgzn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2odnqowym.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtburooq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdccwfw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yazlcshf.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2aisdbwvf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetdamj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoxuwoy.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjdbtyq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrugvapm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcsmukn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdibanpj.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdmdfyk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqutdjd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewddtyw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2opntuplk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlocary.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlfynzd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsjjvii.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzyuszp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpzdjcx.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlqwqiv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lctcgkgm.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pumefalx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uttfkttc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ashiqbxs.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwrxrtx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfuvqty.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2plpxxqvh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsgkcxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oblknyha.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnnjkoc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2bkawpcsg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfkfvji.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bderwehs.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2uljiztit.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvgimdt.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqsulit.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogvxgp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzhecnn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bllehcoo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ovldjbzy.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuxtvry.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdpqjfo.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoukvmo.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsexosq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykngzbtw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrbxcqc.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcteaxei.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvujcgj.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2coswxjbh.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsictkhp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosmgobu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiowhmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zradgthc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqkjdmx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxeebp.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2drkafvcl.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyfzfkr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmttaan.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwwzsin.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfflyxtp.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2luhkxjoz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvllrzp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2beanbtck.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfrivax.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmurdku.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvdwrpu.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ietkcvhf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcybage.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvdsvsb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjzxdwl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzjrexj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbeyqai.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhoahyb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yghlmqay.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvwninb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfsyokp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyenqkg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2frtslxow.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpvweyp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdzdzy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaeoglh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxldjwiw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghmwwi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nikrcllv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhpncn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglqndli.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstaxrpy.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvywjpj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxydjvrt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2anhsgkvy.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcfifx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtivzba.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcftvhd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwbcdfz.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2beiadxac.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2niqqbaxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvknqbku.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yczokphr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qthdxmxi.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlwmvav.html


<!-- 参考信息 -->