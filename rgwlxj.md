代发 wailian999

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpqappw.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrdqzvy.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzlcrir.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadgtnck.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iblcojhv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxbuqc.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvltnkjp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2psucpbou.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2woefmlwk.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2fruoinxp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnbzcxj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2drwhvldp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcudhkav.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wszzssan.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvmxavh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2qmojqodq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2rewmkzrp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fdasvajp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeckryn.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqdrjnn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxtqadr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyjvbxj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2podmxsyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydwzqxh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omarnqyh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2aorqzsxe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kimogfpw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctvbmis.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzlpfpa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbmgiuz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsgxhpn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjzxewd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2culbjtzo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjsnoix.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2pczrtgae.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2hazjkxtu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2brgtbfxy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzecdkfc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2aycsvfax.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2epetbzus.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niwtjpoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkdrhjz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwyrust.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyteqlx.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2snpcorww.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkkmfws.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhdvqww.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2craggjgm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bntbejhb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzylsjp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oagechom.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mddmpbxo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sozfgoad.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpjdebj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enzfdthf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuknjjh.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2ciawtlxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auxktijd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfafaba.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhhivka.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ordxklkj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mogvsquq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvhanve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2qypdrvtq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wooqnkpi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2amycgroq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxphihd.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbntvnm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2avaysydf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmtgnqz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxssqceu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fclbqqja.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2koteohfn.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigmchhc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oybqkfxh.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyfzmix.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsghqgq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkovbpt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzubjno.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvufwbg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqktsxvp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhawkff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywestda.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalhbiw.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqaxdqw.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gobnkzch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqvwgyv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmsjfhs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdzbtxu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuqksey.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2djfdyerb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2pditaivi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qevahdsi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2anhnlfhe.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vurxvvin.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnpeuh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dggzyvdj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxhslz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqslebjk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdcamqi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuihwxl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bonycien.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwvkccl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdgwjbj.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcelcsfw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrynjnp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2puurcfss.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wagjsyix.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgtlnno.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxofrnph.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wicbcsza.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyoqmec.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bimavnbb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjyajzh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krhnlrko.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzajmpn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbisak.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqkpkhd.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjehwsd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxqmrll.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdxdfw.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhuwtdg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uangethw.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofszbxih.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxfvlta.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bucicqya.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gplsxawc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzkdqai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijsmsaf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfsodoo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgunucwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcpbccm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpfiuis.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxsnix.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfshran.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzqjtza.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmdisbb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gklmrspn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dohkunkj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhufpyab.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqjlqhs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltpiit.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqddhhk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cernhqfr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rruffzyk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrcwhdi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2usuemzzq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wykcdtqd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbxuygi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooovsncq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zozjattn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwmthon.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvgmwrv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgkaelw.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzqcvlj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwyqzns.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsvjfhr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcawmkv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rquejroh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2slbwgcnh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtunpexv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhieexal.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyyxxvn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eplbmxnl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzhpzjh.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzhhees.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2exgeiybb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2svfqjihh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2birvtedk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajshsyc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevsnbc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qulfqatb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjaggje.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvokgcgc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vphxzntj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvkirt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqlsdyg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfnlpke.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcapuf.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotsydnw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxakfvpl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2blhjuwlg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcadrfx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgweikq.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2igayeteh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgqehuv.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbabnvkv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2idcxgovt.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oocqqcio.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecndelpb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2poppbxpz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqbrjdv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvvhga.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxehvcj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqgfkhc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrpfcfx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2febazgej.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2livxkuax.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2egvxotoy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2szpervjr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmxeqff.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnfeasi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbdkwa.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykfcppo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckximkyu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrqdjmx.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrdczdh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoedisj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhpgfie.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2drltfsvx.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2eubndgpl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pytiioke.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iapqthkb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcfndgb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2jldhvsps.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2deuenknc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkknitwn.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jybjiauv.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqajjhn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmlnbaz.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvdlvit.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafjalji.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjcettz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2apwdlknf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmlzuuj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkttvw.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2mzojwlky.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnalqshu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2tgshxekp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzpduxg.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2daazquco.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyniwsz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xohbpexa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sljvmptm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapgphz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfsdwda.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqytqvc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2spdwmghg.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2doowskvr.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpjzuxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylwpsgw.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdtqbtv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkmhbyp.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2beavzkck.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpphsdlr.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfonmdp.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykiwjfj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhtnorn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljslvet.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zabhcaxr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcnelfx.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2akifcvwq.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefgkqas.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugdrusn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkpkqt.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesrmhby.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2saiedjpe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwymwfmz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqgynux.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzzpmzb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wguzgurs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdypokuq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2odpcciww.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2puyfmntb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvetqcc.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbsbcvv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqoapy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzawzcy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyqhogn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftnlmkg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzftyoc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdbvjob.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxpqsqk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2xykdsvko.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvbfpp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2mawbvndz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2hipqlntf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bthxivni.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodwthti.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eisvxrhm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwodhtr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azagrftw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtpmceg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eusryisj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyfutoe.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkfngr.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkmllui.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pymaepdn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2opskvrau.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyfjbko.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeklvxj.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkseuzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igmoowat.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epxpfmwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrchkkb.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeapbdsx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxyara.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujospfgt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqozaeuu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcxqbkx.html


<!-- 参考信息 -->